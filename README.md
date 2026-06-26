# Zama Protocol Registry

The public source of truth for **Zama Protocol on-chain contract addresses** across mainnet and testnet — consumable by people and external dApps. It publishes only **shareable** registry data; internal operational details are not included.

> ⚠️ **This repository is generated. Do not edit it by hand.**
> Its contents are produced from Zama's internal registry and published automatically. Manual edits will be overwritten on the next publish.

## Contents

| File | Description |
|---|---|
| [`mainnet.json`](./mainnet.json) / [`testnet.json`](./testnet.json) | Machine-readable: contract addresses, chains, and LayerZero pathway config, with cross-references resolved. |
| [`mainnet.md`](./mainnet.md) / [`testnet.md`](./testnet.md) | Human-readable: the same data as tables, grouped by chain, with block-explorer links. |
| [`manifest.json`](./manifest.json) | Integrity: the `sha256` of each published file and the source commit the data was generated from. |

## Consuming

Fetch the machine-readable JSON directly via raw URLs, e.g.:

```
https://raw.githubusercontent.com/zama-ai/protocol-registry/main/mainnet.json
```

Each file is a stable, sorted-key JSON object: `{ schema_version, chains, contracts, lz_dvn_configs, parameters, operator_staking }`. Contract entries carry `address`, `chain`, `type`, and (where applicable) `owner`/`owner_address`, `symbol`, `note`. `operator_staking` maps each operator → role (`kms`/`coprocessor`) → its `operator_staking` and `operator_rewarder` contract addresses.

## Integrity

`manifest.json` lists the `sha256` of every published file plus `git_source_commit` (the internal commit the snapshot was generated from). To verify a file you fetched, compare its SHA-256 against the manifest:

```
sha256sum mainnet.json   # must match files_sha256sum["mainnet.json"] in manifest.json
```

Publishes are deterministic (sorted keys, no per-run noise in the data files), so identical source always yields identical output.

## Reporting issues

Found an inconsistency or error? **Open an issue here.** Data is corrected in Zama's internal registry first (where it is reviewed and version-controlled), then re-published here — so fixes flow upstream-first and this repo always reflects the latest verified state.

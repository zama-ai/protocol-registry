# Zama Protocol Registry — testnet

> Generated from the Zama Protocol registry. **Do not edit by hand** — see `README.md`.

## Ethereum Hoodi (`ethereum_hoodi`)

### Token

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `HOODI_ZAMA_STAKING_MOCK` | `erc20` | [`0x58713Eca04e01114480b30bE8Ca0d8838F342a55`](https://eth-hoodi.blockscout.com/address/0x58713Eca04e01114480b30bE8Ca0d8838F342a55) | Mintable mock ERC20 for staking contract testing. Symbol: ZAMAMock. Public mint capped at 1M/call; ProtocolStaking contracts hold MINTER_ROLE for reward payouts. |

### Staking

#### Protocol staking

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `HOODI_PROTOCOL_STAKING_COPROCESSOR` | `protocol_staking` | [`0xe41B550CA6F01b756926Be7D593c9F266Cae6221`](https://eth-hoodi.blockscout.com/address/0xe41B550CA6F01b756926Be7D593c9F266Cae6221) | — |
| `HOODI_PROTOCOL_STAKING_KMS` | `protocol_staking` | [`0xB6CE80007422D411825a712e522AE1dcA2746033`](https://eth-hoodi.blockscout.com/address/0xB6CE80007422D411825a712e522AE1dcA2746033) | — |

#### Operator staking

| Operator | Role | Staking | Rewarder |
| -------- | ---- | ------- | -------- |
| `blockscape` | `coprocessor` | [`0xD86AE01b0c578D93fB89F0d181E8189B5c463cFE`](https://eth-hoodi.blockscout.com/address/0xD86AE01b0c578D93fB89F0d181E8189B5c463cFE) | [`0x35a4A730911a9504b2E47DB130B211cA8452e2fb`](https://eth-hoodi.blockscout.com/address/0x35a4A730911a9504b2E47DB130B211cA8452e2fb) |
| `dfns` | `kms` | [`0x5278AB58212949C60A8EEEf1E3cBb7bc6588d7b9`](https://eth-hoodi.blockscout.com/address/0x5278AB58212949C60A8EEEf1E3cBb7bc6588d7b9) | [`0xA70BBDF02803e22f35Abc4EEd40752653B0236F0`](https://eth-hoodi.blockscout.com/address/0xA70BBDF02803e22f35Abc4EEd40752653B0236F0) |
| `figment` | `kms` | [`0x6570756591Ed9351D0D53D840D3e8F321887F4Fa`](https://eth-hoodi.blockscout.com/address/0x6570756591Ed9351D0D53D840D3e8F321887F4Fa) | [`0xB8feeB695247810A81BB0e2a32D3b1c01D8fE01A`](https://eth-hoodi.blockscout.com/address/0xB8feeB695247810A81BB0e2a32D3b1c01D8fE01A) |
| `zama` | `coprocessor` | [`0xC1Ba8ed5c9bFE4E1d185D81ddCa1EDF999E45107`](https://eth-hoodi.blockscout.com/address/0xC1Ba8ed5c9bFE4E1d185D81ddCa1EDF999E45107) | [`0xdBE943948D4970ed6f0527fDCdC2a01A58A530c9`](https://eth-hoodi.blockscout.com/address/0xdBE943948D4970ed6f0527fDCdC2a01A58A530c9) |
| `zama` | `kms` | [`0xbFb717A712aC94204aE9E7049332641f3332C82f`](https://eth-hoodi.blockscout.com/address/0xbFb717A712aC94204aE9E7049332641f3332C82f) | [`0x1F00Fdd750Aa2d627a370a66D71BfDb396540434`](https://eth-hoodi.blockscout.com/address/0x1F00Fdd750Aa2d627a370a66D71BfDb396540434) |

## Ethereum Sepolia (`ethereum_sepolia`)

### Token

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `BRON_MOCK` | `erc20` | [`0xFf021fB13cA64e5354c62c954b949a88cfDEb25E`](https://sepolia.etherscan.io/address/0xFf021fB13cA64e5354c62c954b949a88cfDEb25E) | BRONMock. Mock BRON. Minting restricted to 1M tokens |
| `TGBP` | `erc20` | [`0xf6Ef9ADB61A48E29E36bc873070A46A3D2667ff3`](https://sepolia.etherscan.io/address/0xf6Ef9ADB61A48E29E36bc873070A46A3D2667ff3) | tGBP. Official tGBP testnet erc20. Minting restricted to tGBP org. |
| `TGBP_MOCK` | `erc20` | [`0x93c931278A2aad1916783F952f94276eA5111442`](https://sepolia.etherscan.io/address/0x93c931278A2aad1916783F952f94276eA5111442) | tGBPMock. Mock tGBP. Minting restricted to 1M tokens |
| `USDC_MOCK` | `erc20` | [`0x9b5Cd13b8eFbB58Dc25A05CF411D8056058aDFfF`](https://sepolia.etherscan.io/address/0x9b5Cd13b8eFbB58Dc25A05CF411D8056058aDFfF) | USDCMock. Mock USDC. Minting restricted to 1M tokens |
| `USDT_MOCK` | `erc20` | [`0xa7dA08FafDC9097Cc0E7D4f113A61e31d7e8e9b0`](https://sepolia.etherscan.io/address/0xa7dA08FafDC9097Cc0E7D4f113A61e31d7e8e9b0) | USDTMock. Mock USDT. Minting restricted to 1M tokens |
| `WETH_MOCK` | `erc20` | [`0xff54739b16576FA5402F211D0b938469Ab9A5f3F`](https://sepolia.etherscan.io/address/0xff54739b16576FA5402F211D0b938469Ab9A5f3F) | WETHMock. Mock WETH. Minting restricted to 1M tokens |
| `XAUT_MOCK` | `erc20` | [`0x24377AE4AA0C45ecEe71225007f17c5D423dd940`](https://sepolia.etherscan.io/address/0x24377AE4AA0C45ecEe71225007f17c5D423dd940) | XAUtMock. Mock XAUt. Minting restricted to 1M tokens |
| `ZAMA_MOCK` | `erc20` | [`0x75355a85c6FB9df5f0C80FF54e8747EEe9a0BF57`](https://sepolia.etherscan.io/address/0x75355a85c6FB9df5f0C80FF54e8747EEe9a0BF57) | ZAMAMock. Mock ZAMA for confidential wrapper. Minting restricted to 1M tokens |
| `ZAMA_OFT_ADAPTER` | `layerzero_oft_adapter` | [`0x55D5258841e9Fd304007683ff4637b0a80fb0e62`](https://sepolia.etherscan.io/address/0x55D5258841e9Fd304007683ff4637b0a80fb0e62) | — |
| `ZAMA_STAKING_MOCK` | `erc20` | [`0x9216F67a276B4bf1D883C4Ec24095C2bc53C2ef4`](https://sepolia.etherscan.io/address/0x9216F67a276B4bf1D883C4Ec24095C2bc53C2ef4) | Simple mintable mock ERC20 for staking contract testing. Symbol: ZAMAMock |
| `ZAMA_TOKEN` | `erc20` | [`0xa798B04149e7a61cc95B7D114AD420e8969eA268`](https://sepolia.etherscan.io/address/0xa798B04149e7a61cc95B7D114AD420e8969eA268) | — |

### Wrappers registry

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `TOKEN_WRAPPER_REGISTRY` | `token_wrapper_registry` | [`0x2f0750Bbb0A246059d80e94c454586a7F27a128e`](https://sepolia.etherscan.io/address/0x2f0750Bbb0A246059d80e94c454586a7F27a128e) | — |

### Confidential tokens

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `CONFIDENTIAL_ARMCWBTC` | `confidential_wrapper` | [`0xDDA548CD0f2602Be317A20664c800F9b4DfA53da`](https://sepolia.etherscan.io/address/0xDDA548CD0f2602Be317A20664c800F9b4DfA53da) | carmWBTCs. |
| `CONFIDENTIAL_ARMUSDCP` | `confidential_wrapper` | [`0x2Aa3e01a8A3676C2e272d41F13B91823493f9354`](https://sepolia.etherscan.io/address/0x2Aa3e01a8A3676C2e272d41F13B91823493f9354) | carmUSDCp. |
| `CONFIDENTIAL_ARMUSDCS` | `confidential_wrapper` | [`0xedcEC2fD6A4EB5eaE928098829505E5C15e4e71b`](https://sepolia.etherscan.io/address/0xedcEC2fD6A4EB5eaE928098829505E5C15e4e71b) | carmUSDCs. |
| `CONFIDENTIAL_ARMUSDTP` | `confidential_wrapper` | [`0xd950fE9A9c32ddBd9217627C36Ad674F7F38c645`](https://sepolia.etherscan.io/address/0xd950fE9A9c32ddBd9217627C36Ad674F7F38c645) | carmUSDTp. |
| `CONFIDENTIAL_ARMUSDTS` | `confidential_wrapper` | [`0x1F9dD3AC16293D5067Db6e81aFFdBbd5d4cA70e9`](https://sepolia.etherscan.io/address/0x1F9dD3AC16293D5067Db6e81aFFdBbd5d4cA70e9) | carmUSDTs. |
| `CONFIDENTIAL_AUSD` | `confidential_wrapper` | [`0xb037DebA1a0cf7e4dA65670c0377BF972a52eD3c`](https://sepolia.etherscan.io/address/0xb037DebA1a0cf7e4dA65670c0377BF972a52eD3c) | cAUSD. |
| `CONFIDENTIAL_BBQTGBP` | `confidential_wrapper` | [`0x993E84AdDd0Ca29E723C98a2507a0e7570413580`](https://sepolia.etherscan.io/address/0x993E84AdDd0Ca29E723C98a2507a0e7570413580) | cbbqTGBP. |
| `CONFIDENTIAL_BBQUSDC` | `confidential_wrapper` | [`0x9A4Ae4951A756B4742ba3a330911af6c1502eA70`](https://sepolia.etherscan.io/address/0x9A4Ae4951A756B4742ba3a330911af6c1502eA70) | cbbqUSDC. |
| `CONFIDENTIAL_BBQUSDT` | `confidential_wrapper` | [`0xd7a31E6A1859Bc42D2C7ef8c34D7c92AC3780b4a`](https://sepolia.etherscan.io/address/0xd7a31E6A1859Bc42D2C7ef8c34D7c92AC3780b4a) | cbbqUSDT. |
| `CONFIDENTIAL_BITWISE_USDC_RWA` | `confidential_wrapper` | [`0xc8971a7ff76A16bB052F118d982985aF23325965`](https://sepolia.etherscan.io/address/0xc8971a7ff76A16bB052F118d982985aF23325965) | cbwUSDCr. |
| `CONFIDENTIAL_BRON_MOCK` | `confidential_wrapper` | [`0xaa5612FA27c927a0c7961f5AEFEE5ba3A0F9C891`](https://sepolia.etherscan.io/address/0xaa5612FA27c927a0c7961f5AEFEE5ba3A0F9C891) | cBRONMock. |
| `CONFIDENTIAL_FAUSDE` | `confidential_wrapper` | [`0x5f7b705c4877a1A509aF415De21DAAeD0B137801`](https://sepolia.etherscan.io/address/0x5f7b705c4877a1A509aF415De21DAAeD0B137801) | cfAUSDe. |
| `CONFIDENTIAL_FCUSDT` | `confidential_wrapper` | [`0x9ED813cf5572AdBe0A62DB631293e806a5c104e9`](https://sepolia.etherscan.io/address/0x9ED813cf5572AdBe0A62DB631293e806a5c104e9) | cfUSDTe. |
| `CONFIDENTIAL_GAUNTLET_USDC_FRONTIER` | `confidential_wrapper` | [`0x44F5446cCE7A49553Ba1A0d115c9Bc5E69F21781`](https://sepolia.etherscan.io/address/0x44F5446cCE7A49553Ba1A0d115c9Bc5E69F21781) | cgtusdcf. |
| `CONFIDENTIAL_PENDLEUSDC` | `confidential_wrapper` | [`0x433303C2B462EbA4bAda3E2665EC45dbA6478Bb6`](https://sepolia.etherscan.io/address/0x433303C2B462EbA4bAda3E2665EC45dbA6478Bb6) | carmUSDCl. |
| `CONFIDENTIAL_ROXCUSDC` | `confidential_wrapper` | [`0x53565fCE8b9D81CC4000f635aF97f394F0209fCF`](https://sepolia.etherscan.io/address/0x53565fCE8b9D81CC4000f635aF97f394F0209fCF) | croxUSDCr. |
| `CONFIDENTIAL_ROXUSDCY` | `confidential_wrapper` | [`0xA88CF3eE286CEAbE600BEc431BbF2Bf4007d78a0`](https://sepolia.etherscan.io/address/0xA88CF3eE286CEAbE600BEc431BbF2Bf4007d78a0) | croxUSDCy. |
| `CONFIDENTIAL_STEAKCUSDC` | `confidential_wrapper` | [`0x3f07Ef5A0C1E633DDfDC59b96218f8ED5b1d6f71`](https://sepolia.etherscan.io/address/0x3f07Ef5A0C1E633DDfDC59b96218f8ED5b1d6f71) | csteakcUSDC. |
| `CONFIDENTIAL_STEAKUSDT` | `confidential_wrapper` | [`0x3ddab417b351282676c5E38AF5c5dce66C131298`](https://sepolia.etherscan.io/address/0x3ddab417b351282676c5E38AF5c5dce66C131298) | csteakUSDT. |
| `CONFIDENTIAL_TGBP` | `confidential_wrapper` | [`0x167DC962808B32CFFFc7e14B5018c0bE06A3A208`](https://sepolia.etherscan.io/address/0x167DC962808B32CFFFc7e14B5018c0bE06A3A208) | ctGBP. |
| `CONFIDENTIAL_TGBP_MOCK` | `confidential_wrapper` | [`0xfCE5c7069c5525eF6c8C2b2E35A745bA20a2F7CC`](https://sepolia.etherscan.io/address/0xfCE5c7069c5525eF6c8C2b2E35A745bA20a2F7CC) | ctGBPMock. |
| `CONFIDENTIAL_USDC_MOCK` | `confidential_wrapper` | [`0x7c5BF43B851c1dff1a4feE8dB225b87f2C223639`](https://sepolia.etherscan.io/address/0x7c5BF43B851c1dff1a4feE8dB225b87f2C223639) | cUSDCMock. |
| `CONFIDENTIAL_USDT_MOCK` | `confidential_wrapper` | [`0x4E7B06D78965594eB5EF5414c357ca21E1554491`](https://sepolia.etherscan.io/address/0x4E7B06D78965594eB5EF5414c357ca21E1554491) | cUSDTMock. |
| `CONFIDENTIAL_WBTC` | `confidential_wrapper` | [`0x4bCCb68Ab353cb1472DEA27577d30aA345402cC7`](https://sepolia.etherscan.io/address/0x4bCCb68Ab353cb1472DEA27577d30aA345402cC7) | cWBTC. |
| `CONFIDENTIAL_WETH_MOCK` | `confidential_wrapper` | [`0x46208622DA27d91db4f0393733C8BA082ed83158`](https://sepolia.etherscan.io/address/0x46208622DA27d91db4f0393733C8BA082ed83158) | cWETHMock. |
| `CONFIDENTIAL_XAUT_MOCK` | `confidential_wrapper` | [`0xe4FcF848739845BC81Dee1d5352cf3844F0a60C7`](https://sepolia.etherscan.io/address/0xe4FcF848739845BC81Dee1d5352cf3844F0a60C7) | cXAUtMock. |
| `CONFIDENTIAL_ZAMA_MOCK` | `confidential_wrapper` | [`0xf2D628d2598aF4eAF94CB76a437Ff86CA78FfbFB`](https://sepolia.etherscan.io/address/0xf2D628d2598aF4eAF94CB76a437Ff86CA78FfbFB) | cZAMAMock. |

### Confidential DeFi

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `BITWISE_USDC_RWA_LENDING_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0x64D3E697543C03AA37639d671A46F521C3b0e6Fe`](https://sepolia.etherscan.io/address/0x64D3E697543C03AA37639d671A46F521C3b0e6Fe) | DepositVaultBatcherConfidential. Batches confidential assets into the Bitwise RWA Lending vault. Deploy block 11613164. |
| `BITWISE_USDC_RWA_LENDING_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0x6475e7D437eC86C0dB95F97b603998F712682c92`](https://sepolia.etherscan.io/address/0x6475e7D437eC86C0dB95F97b603998F712682c92) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Bitwise RWA Lending vault. |
| `BITWISE_USDC_RWA_LENDING_VAULT` | `erc4626_vault` | [`0x5461A9daA6392F8f99AC4825EE1254De00d36Ff0`](https://sepolia.etherscan.io/address/0x5461A9daA6392F8f99AC4825EE1254De00d36Ff0) | Morpho VaultV2 'Bitwise RWA Lending'. Its share token is the underlying of CONFIDENTIAL_BITWISE_USDC_RWA. |
| `CONFIDENTIAL_WINTERMUTE_WBTC_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0xcc30AD76e1854bd5a192fC6407c211F2ec57294E`](https://sepolia.etherscan.io/address/0xcc30AD76e1854bd5a192fC6407c211F2ec57294E) | DepositVaultBatcherConfidential. Batches confidential assets into the Wintermute WBTC Select vault. Deploy block 11613219. |
| `CONFIDENTIAL_WINTERMUTE_WBTC_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0xaf3a7b5f437890a7B57f74155879E1F2D89fd202`](https://sepolia.etherscan.io/address/0xaf3a7b5f437890a7B57f74155879E1F2D89fd202) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Wintermute WBTC Select vault. |
| `CONFIDENTIAL_WINTERMUTE_WBTC_VAULT` | `erc4626_vault` | [`0xe5A5b28809fC23c1207cFCD4BB50C613e6bf36D4`](https://sepolia.etherscan.io/address/0xe5A5b28809fC23c1207cFCD4BB50C613e6bf36D4) | Morpho VaultV2 'Wintermute WBTC Select'. Its share token is the underlying of CONFIDENTIAL_ARMCWBTC. |
| `CONFIDENTIAL_WINTERMUTE_WBTC_WHITELIST_SEND_ASSETS_GATE` | `whitelist_gate` | [`0x3e576e446fbf5eAd7e90C8b200Af1aa918023084`](https://sepolia.etherscan.io/address/0x3e576e446fbf5eAd7e90C8b200Af1aa918023084) | WhitelistSendAssetsGate on the Wintermute WBTC Select vault; allowlists its deposit batcher as the vault's depositor. |
| `FLOWDESK_AUSD_RWA_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0x0733352a066b84be41bC001D9560de6f88e89e8E`](https://sepolia.etherscan.io/address/0x0733352a066b84be41bC001D9560de6f88e89e8E) | DepositVaultBatcherConfidential. Batches confidential assets into the Flowdesk AUSD RWA Strategy vault. Deploy block 11613167. |
| `FLOWDESK_AUSD_RWA_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0xD8a2981B5EA4c6c17277e8ce970fF9C91ba4D792`](https://sepolia.etherscan.io/address/0xD8a2981B5EA4c6c17277e8ce970fF9C91ba4D792) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Flowdesk AUSD RWA Strategy vault. |
| `FLOWDESK_AUSD_RWA_VAULT` | `erc4626_vault` | [`0xDbf85924729EB2924119f96DC52C7287507c97aF`](https://sepolia.etherscan.io/address/0xDbf85924729EB2924119f96DC52C7287507c97aF) | Morpho VaultV2 'Flowdesk AUSD RWA Strategy'. Its share token is the underlying of CONFIDENTIAL_FAUSDE. |
| `FLOWDESK_USDT_HIGH_YIELD_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0x58a699b4019DAd9b85C448510D0D3C5A59E090F6`](https://sepolia.etherscan.io/address/0x58a699b4019DAd9b85C448510D0D3C5A59E090F6) | DepositVaultBatcherConfidential. Batches confidential assets into the Flowdesk High Yield USDT vault. Deploy block 11613170. |
| `FLOWDESK_USDT_HIGH_YIELD_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0xD33f7b4a5132b6EB9dAc60fc13279F23828971F9`](https://sepolia.etherscan.io/address/0xD33f7b4a5132b6EB9dAc60fc13279F23828971F9) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Flowdesk High Yield USDT vault. |
| `FLOWDESK_USDT_HIGH_YIELD_VAULT` | `erc4626_vault` | [`0x24A3DB588181629f74d225C61625355d20B6cd1a`](https://sepolia.etherscan.io/address/0x24A3DB588181629f74d225C61625355d20B6cd1a) | Morpho VaultV2 'Flowdesk High Yield USDT'. Its share token is the underlying of CONFIDENTIAL_FCUSDT. |
| `FLOWDESK_USDT_HIGH_YIELD_WHITELIST_SEND_ASSETS_GATE` | `whitelist_gate` | [`0x2fe3C1173071A797b8e8bEfd03cB6E79b26e2Ac3`](https://sepolia.etherscan.io/address/0x2fe3C1173071A797b8e8bEfd03cB6E79b26e2Ac3) | WhitelistSendAssetsGate on the Flowdesk High Yield USDT vault; allowlists its deposit batcher as the vault's depositor. |
| `GAUNTLET_USDC_FRONTIER_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0x6e4e16009438B869D73991b415C2de103d7F1a66`](https://sepolia.etherscan.io/address/0x6e4e16009438B869D73991b415C2de103d7F1a66) | DepositVaultBatcherConfidential. Batches confidential assets into the Gauntlet USDC Frontier vault. Deploy block 11613174. |
| `GAUNTLET_USDC_FRONTIER_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0xDA5bF86A820cC74BFFadA78Fe8009932ced50F5d`](https://sepolia.etherscan.io/address/0xDA5bF86A820cC74BFFadA78Fe8009932ced50F5d) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Gauntlet USDC Frontier vault. |
| `GAUNTLET_USDC_FRONTIER_VAULT` | `erc4626_vault` | [`0xAbca19eaBB28E7Af4D4497916e3212E705Bbed59`](https://sepolia.etherscan.io/address/0xAbca19eaBB28E7Af4D4497916e3212E705Bbed59) | Morpho VaultV2 'Gauntlet USDC Frontier'. Its share token is the underlying of CONFIDENTIAL_GAUNTLET_USDC_FRONTIER. |
| `ROCKAWAYX_USDC_HIGH_YIELD_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0x6d05867023B804760616728F7C761BD5F9ad9545`](https://sepolia.etherscan.io/address/0x6d05867023B804760616728F7C761BD5F9ad9545) | DepositVaultBatcherConfidential. Batches confidential assets into the RockawayX USDC Yield vault. Deploy block 11613178. |
| `ROCKAWAYX_USDC_HIGH_YIELD_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0x63aC66266e435BB859D932080dc00FFE6e4DDE8e`](https://sepolia.etherscan.io/address/0x63aC66266e435BB859D932080dc00FFE6e4DDE8e) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the RockawayX USDC Yield vault. |
| `ROCKAWAYX_USDC_HIGH_YIELD_VAULT` | `erc4626_vault` | [`0x22ecd6Ff385BAA1728ac8F43B4C4bdaEF3B6D2A7`](https://sepolia.etherscan.io/address/0x22ecd6Ff385BAA1728ac8F43B4C4bdaEF3B6D2A7) | Morpho VaultV2 'RockawayX USDC Yield'. Its share token is the underlying of CONFIDENTIAL_ROXUSDCY. |
| `ROCKAWAYX_USDC_RWA_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0x7e07bBa1BC4BD2558D28aE58201652E1c75B8f29`](https://sepolia.etherscan.io/address/0x7e07bBa1BC4BD2558D28aE58201652E1c75B8f29) | DepositVaultBatcherConfidential. Batches confidential assets into the RockawayX RWA Strategy vault. Deploy block 11613181. |
| `ROCKAWAYX_USDC_RWA_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0x6319017ee3b68139C1F4DaE4AE789348C5D74fA1`](https://sepolia.etherscan.io/address/0x6319017ee3b68139C1F4DaE4AE789348C5D74fA1) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the RockawayX RWA Strategy vault. |
| `ROCKAWAYX_USDC_RWA_VAULT` | `erc4626_vault` | [`0x94D71dfaD007C2F5e9E9340ae72703222489c430`](https://sepolia.etherscan.io/address/0x94D71dfaD007C2F5e9E9340ae72703222489c430) | Morpho VaultV2 'RockawayX RWA Strategy'. Its share token is the underlying of CONFIDENTIAL_ROXCUSDC. |
| `ROCKAWAYX_USDC_RWA_WHITELIST_SEND_ASSETS_GATE` | `whitelist_gate` | [`0xAA6B44CCFcd20c1E682aB4cf2b4d01789C14f151`](https://sepolia.etherscan.io/address/0xAA6B44CCFcd20c1E682aB4cf2b4d01789C14f151) | WhitelistSendAssetsGate on the RockawayX RWA Strategy vault; allowlists its deposit batcher as the vault's depositor. |
| `STEAKHOUSE_CONFIDENTIAL_PRIME_USDC_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0xF66Fc55060DF981449Fa746e8F58bD003370bE28`](https://sepolia.etherscan.io/address/0xF66Fc55060DF981449Fa746e8F58bD003370bE28) | DepositVaultBatcherConfidential. Batches confidential assets into the Steakhouse Confidential Prime USDC vault. Deploy block 11613191. |
| `STEAKHOUSE_CONFIDENTIAL_PRIME_USDC_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0x9f3cF93246cBf333C6BE65fb7277724eC0c38543`](https://sepolia.etherscan.io/address/0x9f3cF93246cBf333C6BE65fb7277724eC0c38543) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Steakhouse Confidential Prime USDC vault. |
| `STEAKHOUSE_CONFIDENTIAL_PRIME_USDC_VAULT` | `erc4626_vault` | [`0x3DEcCf4D7C98B573faBA29f695CA06f568E2801f`](https://sepolia.etherscan.io/address/0x3DEcCf4D7C98B573faBA29f695CA06f568E2801f) | Morpho VaultV2 'Steakhouse Confidential Prime USDC'. Its share token is the underlying of CONFIDENTIAL_STEAKCUSDC. |
| `STEAKHOUSE_CONFIDENTIAL_PRIME_USDC_WHITELIST_SEND_ASSETS_GATE` | `whitelist_gate` | [`0x74050Fb3dC7D3c427862Cb3d5bbE0D3Df0c1678d`](https://sepolia.etherscan.io/address/0x74050Fb3dC7D3c427862Cb3d5bbE0D3Df0c1678d) | WhitelistSendAssetsGate on the Steakhouse Confidential Prime USDC vault; allowlists its deposit batcher as the vault's depositor. |
| `STEAKHOUSE_TGBP_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0xd12d907611f4ACb9F6C84bCac8539b5aDbd1Ac78`](https://sepolia.etherscan.io/address/0xd12d907611f4ACb9F6C84bCac8539b5aDbd1Ac78) | DepositVaultBatcherConfidential. Batches confidential assets into the Steakhouse tGBP vault. Deploy block 11613185. |
| `STEAKHOUSE_TGBP_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0xFA57F75d2861D0e425D91e2a9fB4B7D156D19396`](https://sepolia.etherscan.io/address/0xFA57F75d2861D0e425D91e2a9fB4B7D156D19396) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Steakhouse tGBP vault. |
| `STEAKHOUSE_TGBP_VAULT` | `erc4626_vault` | [`0xeA496D703b5AAeD1fb090C9A93A02499745E5A9A`](https://sepolia.etherscan.io/address/0xeA496D703b5AAeD1fb090C9A93A02499745E5A9A) | Morpho VaultV2 'Steakhouse tGBP'. Its share token is the underlying of CONFIDENTIAL_BBQTGBP. |
| `STEAKHOUSE_USDC_HIGH_YIELD_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0x5964855395836727Cf62E32d534B54Ccd855eB03`](https://sepolia.etherscan.io/address/0x5964855395836727Cf62E32d534B54Ccd855eB03) | DepositVaultBatcherConfidential. Batches confidential assets into the Steakhouse High Yield USDC vault. Deploy block 11613188. |
| `STEAKHOUSE_USDC_HIGH_YIELD_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0xd06F2a95A810F25745f9dCC1EBb8755877A81726`](https://sepolia.etherscan.io/address/0xd06F2a95A810F25745f9dCC1EBb8755877A81726) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Steakhouse High Yield USDC vault. |
| `STEAKHOUSE_USDC_HIGH_YIELD_VAULT` | `erc4626_vault` | [`0x8c309e5F28CA7fAdE124ac2436F8d476bd6C6f74`](https://sepolia.etherscan.io/address/0x8c309e5F28CA7fAdE124ac2436F8d476bd6C6f74) | Morpho VaultV2 'Steakhouse High Yield USDC'. Its share token is the underlying of CONFIDENTIAL_BBQUSDC. |
| `STEAKHOUSE_USDT_HIGH_YIELD_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0x94366Be3557b4e2E2e842071888A3168C671EA6E`](https://sepolia.etherscan.io/address/0x94366Be3557b4e2E2e842071888A3168C671EA6E) | DepositVaultBatcherConfidential. Batches confidential assets into the Steakhouse High Yield USDT vault. Deploy block 11613195. |
| `STEAKHOUSE_USDT_HIGH_YIELD_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0x3cA6d36f42c9DAd404f68FA1e2842BEd2C4B0395`](https://sepolia.etherscan.io/address/0x3cA6d36f42c9DAd404f68FA1e2842BEd2C4B0395) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Steakhouse High Yield USDT vault. |
| `STEAKHOUSE_USDT_HIGH_YIELD_VAULT` | `erc4626_vault` | [`0x1679949B5a13D8DC7d4256F073F6a9b2715021e1`](https://sepolia.etherscan.io/address/0x1679949B5a13D8DC7d4256F073F6a9b2715021e1) | Morpho VaultV2 'Steakhouse High Yield USDT'. Its share token is the underlying of CONFIDENTIAL_BBQUSDT. |
| `STEAKHOUSE_USDT_PRIME_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0x8de304Cd4F6F46e973bac8EC68366613b530158a`](https://sepolia.etherscan.io/address/0x8de304Cd4F6F46e973bac8EC68366613b530158a) | DepositVaultBatcherConfidential. Batches confidential assets into the Steakhouse Prime USDT vault. Deploy block 11613198. |
| `STEAKHOUSE_USDT_PRIME_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0xeD3ecE0DF57AdAe0b7D11F8962b9386Aca758Be9`](https://sepolia.etherscan.io/address/0xeD3ecE0DF57AdAe0b7D11F8962b9386Aca758Be9) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Steakhouse Prime USDT vault. |
| `STEAKHOUSE_USDT_PRIME_VAULT` | `erc4626_vault` | [`0x7A9C06bB09A98E64680622aD3B7455c03e983780`](https://sepolia.etherscan.io/address/0x7A9C06bB09A98E64680622aD3B7455c03e983780) | Morpho VaultV2 'Steakhouse Prime USDT'. Its share token is the underlying of CONFIDENTIAL_STEAKUSDT. |
| `VAULT_BATCHER_ROUTER` | `vault_batcher_router` | [`0xD5BBFF95F3401aeC3B111664F6b72EdAe73814e8`](https://sepolia.etherscan.io/address/0xD5BBFF95F3401aeC3B111664F6b72EdAe73814e8) | VaultBatcherConfidentialRouter. Ownerless; fans one confidential deposit or redemption out across several vault batchers. Accepts only wrappers listed on TOKEN_WRAPPER_REGISTRY. |
| `WINTERMUTE_USDC_PENDLE_LOOPING_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0x741579B27A8bdD5A09Ed999697FE4D61dCA0A778`](https://sepolia.etherscan.io/address/0x741579B27A8bdD5A09Ed999697FE4D61dCA0A778) | DepositVaultBatcherConfidential. Batches confidential assets into the Wintermute USDC Looping Pendle vault. Deploy block 11613202. |
| `WINTERMUTE_USDC_PENDLE_LOOPING_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0x1E948730EB6fe0a29293EE687315ecD8634dA71a`](https://sepolia.etherscan.io/address/0x1E948730EB6fe0a29293EE687315ecD8634dA71a) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Wintermute USDC Looping Pendle vault. |
| `WINTERMUTE_USDC_PENDLE_LOOPING_VAULT` | `erc4626_vault` | [`0x6A3CE25499643a5Fe2cF80FB6fBC508c27513436`](https://sepolia.etherscan.io/address/0x6A3CE25499643a5Fe2cF80FB6fBC508c27513436) | Morpho VaultV2 'Wintermute USDC Looping Pendle'. Its share token is the underlying of CONFIDENTIAL_PENDLEUSDC. |
| `WINTERMUTE_USDC_PRIME_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0x2A4BfF538bD3389cABAf872A5290B5A9280A49A8`](https://sepolia.etherscan.io/address/0x2A4BfF538bD3389cABAf872A5290B5A9280A49A8) | DepositVaultBatcherConfidential. Batches confidential assets into the Wintermute USDC Prime vault. Deploy block 11613206. |
| `WINTERMUTE_USDC_PRIME_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0xBb0F1060c371C8b90864354ABe4A91fc30aA70F1`](https://sepolia.etherscan.io/address/0xBb0F1060c371C8b90864354ABe4A91fc30aA70F1) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Wintermute USDC Prime vault. |
| `WINTERMUTE_USDC_PRIME_VAULT` | `erc4626_vault` | [`0xA53C74D16B4c0cc5fA80CFA84E4134F2a897899c`](https://sepolia.etherscan.io/address/0xA53C74D16B4c0cc5fA80CFA84E4134F2a897899c) | Morpho VaultV2 'Wintermute USDC Prime'. Its share token is the underlying of CONFIDENTIAL_ARMUSDCP. |
| `WINTERMUTE_USDC_SELECT_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0x672E08e823d230bC7345ddD646BB620273c44E17`](https://sepolia.etherscan.io/address/0x672E08e823d230bC7345ddD646BB620273c44E17) | DepositVaultBatcherConfidential. Batches confidential assets into the Wintermute USDC Select vault. Deploy block 11613210. |
| `WINTERMUTE_USDC_SELECT_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0xff1d6A1b42ABCf02c1f753398e4E85a025110c33`](https://sepolia.etherscan.io/address/0xff1d6A1b42ABCf02c1f753398e4E85a025110c33) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Wintermute USDC Select vault. |
| `WINTERMUTE_USDC_SELECT_VAULT` | `erc4626_vault` | [`0xa20bC6F7463EAaf600a9E0720aA687a506024fba`](https://sepolia.etherscan.io/address/0xa20bC6F7463EAaf600a9E0720aA687a506024fba) | Morpho VaultV2 'Wintermute USDC Select'. Its share token is the underlying of CONFIDENTIAL_ARMUSDCS. |
| `WINTERMUTE_USDT_PRIME_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0xe82d5765BdB44D7d0ec2DC1dcA5135B8409FC8f4`](https://sepolia.etherscan.io/address/0xe82d5765BdB44D7d0ec2DC1dcA5135B8409FC8f4) | DepositVaultBatcherConfidential. Batches confidential assets into the Wintermute USDT Prime vault. Deploy block 11613213. |
| `WINTERMUTE_USDT_PRIME_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0xAb5d60425607f217Ac37aB7299A9D5B6ecdBBFb9`](https://sepolia.etherscan.io/address/0xAb5d60425607f217Ac37aB7299A9D5B6ecdBBFb9) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Wintermute USDT Prime vault. |
| `WINTERMUTE_USDT_PRIME_VAULT` | `erc4626_vault` | [`0x7e66fad0228dc080A8Ead12e7F6f43C687ECA903`](https://sepolia.etherscan.io/address/0x7e66fad0228dc080A8Ead12e7F6f43C687ECA903) | Morpho VaultV2 'Wintermute USDT Prime'. Its share token is the underlying of CONFIDENTIAL_ARMUSDTP. |
| `WINTERMUTE_USDT_SELECT_DEPOSIT_VAULT_BATCHER` | `vault_batcher` | [`0xd6B6d1ACEC2c8095F38b49c5c725930EB9B198E3`](https://sepolia.etherscan.io/address/0xd6B6d1ACEC2c8095F38b49c5c725930EB9B198E3) | DepositVaultBatcherConfidential. Batches confidential assets into the Wintermute USDT Select vault. Deploy block 11613216. |
| `WINTERMUTE_USDT_SELECT_REDEEM_VAULT_BATCHER` | `vault_batcher` | [`0x4c7438086a0F74803b7461DDfd245E6Fcf33eb7C`](https://sepolia.etherscan.io/address/0x4c7438086a0F74803b7461DDfd245E6Fcf33eb7C) | RedeemVaultBatcherConfidential. Batches confidential share redemptions from the Wintermute USDT Select vault. |
| `WINTERMUTE_USDT_SELECT_VAULT` | `erc4626_vault` | [`0xbB4BC344517c55f4cB46cC0B1726F2d8Ea946568`](https://sepolia.etherscan.io/address/0xbB4BC344517c55f4cB46cC0B1726F2d8Ea946568) | Morpho VaultV2 'Wintermute USDT Select'. Its share token is the underlying of CONFIDENTIAL_ARMUSDTS. |

### Staking

#### Protocol staking

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `PROTOCOL_STAKING_COPROCESSOR` | `protocol_staking` | [`0xc22E393D2A1C1BD65c88d34a3bE4DD77e8952E71`](https://sepolia.etherscan.io/address/0xc22E393D2A1C1BD65c88d34a3bE4DD77e8952E71) | — |
| `PROTOCOL_STAKING_KMS` | `protocol_staking` | [`0x0309b4308A6AC121B9b3A960aC7Bc9bd8256cf38`](https://sepolia.etherscan.io/address/0x0309b4308A6AC121B9b3A960aC7Bc9bd8256cf38) | — |

#### Operator staking

| Operator | Role | Staking | Rewarder |
| -------- | ---- | ------- | -------- |
| `artifact` | `coprocessor` | [`0x98B50c22245994360Ecf1F695a7383A3f983AeF4`](https://sepolia.etherscan.io/address/0x98B50c22245994360Ecf1F695a7383A3f983AeF4) | [`0x48D05E4edEC0496aF2DcA87cC478fD634358AaD9`](https://sepolia.etherscan.io/address/0x48D05E4edEC0496aF2DcA87cC478fD634358AaD9) |
| `blockscape` | `coprocessor` | [`0xd32b8E13D9e9733f21068168637e68131122C212`](https://sepolia.etherscan.io/address/0xd32b8E13D9e9733f21068168637e68131122C212) | [`0x39c5DE7A3eB8Ac69e0737F870a57c4aa509Abd88`](https://sepolia.etherscan.io/address/0x39c5DE7A3eB8Ac69e0737F870a57c4aa509Abd88) |
| `conduit` | `kms` | [`0xd6C131CD3c1243934658781a9F7A2CBd1E40f6bF`](https://sepolia.etherscan.io/address/0xd6C131CD3c1243934658781a9F7A2CBd1E40f6bF) | [`0x59d75AC4Ace54a2c31ca5E1c830F174333E00daf`](https://sepolia.etherscan.io/address/0x59d75AC4Ace54a2c31ca5E1c830F174333E00daf) |
| `dfns` | `kms` | [`0x8e0bFD7736E9628E2179fB98d44223eF9840fBC7`](https://sepolia.etherscan.io/address/0x8e0bFD7736E9628E2179fB98d44223eF9840fBC7) | [`0x9beA3550C355640ce9A6805eDE5Ef4B4242fe2f1`](https://sepolia.etherscan.io/address/0x9beA3550C355640ce9A6805eDE5Ef4B4242fe2f1) |
| `etherscan` | `kms` | [`0xDF3f304c291466F21BB711d00E48a0d9AD9D64aF`](https://sepolia.etherscan.io/address/0xDF3f304c291466F21BB711d00E48a0d9AD9D64aF) | [`0xa0F333e8478f092C83F512d8684697b8402A13AA`](https://sepolia.etherscan.io/address/0xa0F333e8478f092C83F512d8684697b8402A13AA) |
| `figment` | `kms` | [`0x1a5f6C8FFdd869b30FFC73cC9424025829aCad04`](https://sepolia.etherscan.io/address/0x1a5f6C8FFdd869b30FFC73cC9424025829aCad04) | [`0xBA07aC6121639C00307Fb7b869eB6C28C7dDc2A5`](https://sepolia.etherscan.io/address/0xBA07aC6121639C00307Fb7b869eB6C28C7dDc2A5) |
| `fireblocks` | `kms` | [`0xe85765700Ef107E94fd57FbF1D1863ff87a2948D`](https://sepolia.etherscan.io/address/0xe85765700Ef107E94fd57FbF1D1863ff87a2948D) | [`0xDDE05a52a91E060A2912f41A3020fB8a64fB6898`](https://sepolia.etherscan.io/address/0xDDE05a52a91E060A2912f41A3020fB8a64fB6898) |
| `infstones` | `kms` | [`0x5F1310b6E8F7DcC24A9A6F74229cf66EE075d4D6`](https://sepolia.etherscan.io/address/0x5F1310b6E8F7DcC24A9A6F74229cf66EE075d4D6) | [`0x84e4aEd40682854804980F0CeDE22021b2332DdD`](https://sepolia.etherscan.io/address/0x84e4aEd40682854804980F0CeDE22021b2332DdD) |
| `layerzero` | `kms` | [`0x6c12eB5d89E6f89399610C7b3Efca40671E82F06`](https://sepolia.etherscan.io/address/0x6c12eB5d89E6f89399610C7b3Efca40671E82F06) | [`0x8552cFd15Ac9BEB27B32265C842D0d7dE1Ea6907`](https://sepolia.etherscan.io/address/0x8552cFd15Ac9BEB27B32265C842D0d7dE1Ea6907) |
| `ledger` | `kms` | [`0xe52419533D0322a57d6db28d32463aa6717FeA3c`](https://sepolia.etherscan.io/address/0xe52419533D0322a57d6db28d32463aa6717FeA3c) | [`0x4e69A50244FD864DD92a4D4C0279Bd5A19BA3674`](https://sepolia.etherscan.io/address/0x4e69A50244FD864DD92a4D4C0279Bd5A19BA3674) |
| `luganodes` | `coprocessor` | [`0xe89d9ca0579F19B77af04b201E73A26CECA07600`](https://sepolia.etherscan.io/address/0xe89d9ca0579F19B77af04b201E73A26CECA07600) | [`0x54C96af59cE8dc776D10E906F6C6d65dBaA6b8a3`](https://sepolia.etherscan.io/address/0x54C96af59cE8dc776D10E906F6C6d65dBaA6b8a3) |
| `omakase` | `kms` | [`0xb1A7026C28cB91604FB7B1669f060aB74A30c255`](https://sepolia.etherscan.io/address/0xb1A7026C28cB91604FB7B1669f060aB74A30c255) | [`0x0FA63Dd6a545fA3aAdb089232B8b498434393C7e`](https://sepolia.etherscan.io/address/0x0FA63Dd6a545fA3aAdb089232B8b498434393C7e) |
| `openzeppelin` | `kms` | [`0x76427A3830295406d4aBae5b4754749048f58098`](https://sepolia.etherscan.io/address/0x76427A3830295406d4aBae5b4754749048f58098) | [`0x515089940Cd2202D1eE49ee6F5f99DF598D21109`](https://sepolia.etherscan.io/address/0x515089940Cd2202D1eE49ee6F5f99DF598D21109) |
| `p2p` | `coprocessor` | [`0x419Bcec8A8B60688AC7EfeFECC5f83E922191b2A`](https://sepolia.etherscan.io/address/0x419Bcec8A8B60688AC7EfeFECC5f83E922191b2A) | [`0xdDb13f5266474cCbeA7C5d45D140Ce9cc45F2527`](https://sepolia.etherscan.io/address/0xdDb13f5266474cCbeA7C5d45D140Ce9cc45F2527) |
| `stake_capital` | `kms` | [`0xdd0a1B86C8bf653e5bA575bE81bBD733E59803Ae`](https://sepolia.etherscan.io/address/0xdd0a1B86C8bf653e5bA575bE81bBD733E59803Ae) | [`0xF10e5A61062f224837C199E98D362FA81F4211f6`](https://sepolia.etherscan.io/address/0xF10e5A61062f224837C199E98D362FA81F4211f6) |
| `unit410` | `kms` | [`0xFcC6F9cA8CC4A491B05306D57374a3F6c1f52484`](https://sepolia.etherscan.io/address/0xFcC6F9cA8CC4A491B05306D57374a3F6c1f52484) | [`0xE15e37219B8e468BF2174Da83925437f462c2506`](https://sepolia.etherscan.io/address/0xE15e37219B8e468BF2174Da83925437f462c2506) |
| `zama` | `coprocessor` | [`0x1504646d2e4F924db4c6D6F8e42713e5492604ce`](https://sepolia.etherscan.io/address/0x1504646d2e4F924db4c6D6F8e42713e5492604ce) | [`0xb58b77b140d6618f46B8115Cd3C10D856b3c7780`](https://sepolia.etherscan.io/address/0xb58b77b140d6618f46B8115Cd3C10D856b3c7780) |
| `zama` | `kms` | [`0x454D1738C8eD25C744aF01730EE39a27B683A246`](https://sepolia.etherscan.io/address/0x454D1738C8eD25C744aF01730EE39a27B683A246) | [`0x458E9C3e87CF8fE7FCbD418e8C0AE9D09E581ad3`](https://sepolia.etherscan.io/address/0x458E9C3e87CF8fE7FCbD418e8C0AE9D09E581ad3) |

### Governance

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `GOVERNANCE_OAPP_SENDER_TO_AMOY` | `layerzero_oapp_sender` | [`0xe57ea2f14f3051296d3965Bae8caAF86acdd6050`](https://sepolia.etherscan.io/address/0xe57ea2f14f3051296d3965Bae8caAF86acdd6050) | Sends governance messages from Sepolia to Polygon Amoy via LayerZero |
| `GOVERNANCE_OAPP_SENDER_TO_GATEWAY` | `layerzero_oapp_sender` | [`0x909692c2f4979ca3fa11B5859d499308A1ec4932`](https://sepolia.etherscan.io/address/0x909692c2f4979ca3fa11B5859d499308A1ec4932) | Sends governance messages from Sepolia to Gateway Testnet via LayerZero |
| `PROTOCOL_DAO` | `aragon_dao` | [`0x08e8a84c3c8c7cba165B1adcf67Ae4639eF84f52`](https://sepolia.etherscan.io/address/0x08e8a84c3c8c7cba165B1adcf67Ae4639eF84f52) | Primary Aragon governance DAO on Sepolia |
| `SETUP_MULTISIG` | `aragon_multisig_plugin` | [`0x6d5521B3B0b8E36F6942EAF3fc62bB9e096a6f9a`](https://sepolia.etherscan.io/address/0x6d5521B3B0b8E36F6942EAF3fc62bB9e096a6f9a) | Has execution permission on PROTOCOL_DAO. |

### Pausing

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `PAUSER_SET_HOST` | `pauser_set` | [`0xc62392B4100a1bD45AbDBf91E70f1E4349402b46`](https://sepolia.etherscan.io/address/0xc62392B4100a1bD45AbDBf91E70f1E4349402b46) | — |
| `PAUSER_SET_WRAPPER` | `pauser_set` | [`0xEd03Be6711787f3068885137723504a075514040`](https://sepolia.etherscan.io/address/0xEd03Be6711787f3068885137723504a075514040) | — |

### Fees

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `PROTOCOL_FEES_BURNER` | `protocol_fees_burner` | [`0xFda98943FB461310A5d26769606D302Ea89890e3`](https://sepolia.etherscan.io/address/0xFda98943FB461310A5d26769606D302Ea89890e3) | Burns protocol fees collected on Sepolia |

### FHEVM Protocol

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `ACL_HOST` | `fhevm_acl` | [`0xf0Ffdc93b7E186bC2f8CB3dAA75D86d1930A433D`](https://sepolia.etherscan.io/address/0xf0Ffdc93b7E186bC2f8CB3dAA75D86d1930A433D) | — |
| `FHEVM_EXECUTOR` | `fhevm_executor` | [`0x92C920834Ec8941d2C77D188936E1f7A6f49c127`](https://sepolia.etherscan.io/address/0x92C920834Ec8941d2C77D188936E1f7A6f49c127) | — |
| `HCU_LIMIT` | `fhevm_hcu_limit` | [`0xa10998783c8CF88D886Bc30307e631D6686F0A22`](https://sepolia.etherscan.io/address/0xa10998783c8CF88D886Bc30307e631D6686F0A22) | — |
| `INPUT_VERIFIER` | `fhevm_verifier` | [`0xBBC1fFCdc7C316aAAd72E807D9b0272BE8F84DA0`](https://sepolia.etherscan.io/address/0xBBC1fFCdc7C316aAAd72E807D9b0272BE8F84DA0) | — |
| `KMS_GENERATION_HOST` | `fhevm_kms_generation` | [`0x77389113d7000EcBCfc2bDed57202f5f46109934`](https://sepolia.etherscan.io/address/0x77389113d7000EcBCfc2bDed57202f5f46109934) | — |
| `KMS_VERIFIER` | `fhevm_kms_verifier` | [`0xbE0E383937d564D7FF0BC3b46c51f0bF8d5C311A`](https://sepolia.etherscan.io/address/0xbE0E383937d564D7FF0BC3b46c51f0bF8d5C311A) | — |
| `PROTOCOL_CONFIG` | `fhevm_protocol_config` | [`0x51f9AFBc89Ea792e1a21a12AB802ab58D4dbee83`](https://sepolia.etherscan.io/address/0x51f9AFBc89Ea792e1a21a12AB802ab58D4dbee83) | — |

## Gateway Testnet (`gateway_testnet`)

### Token

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `ZAMA_OFT_GW` | `layerzero_oft` | [`0xcE762c7FDaac795D31a266B9247F8958c159c6d4`](https://explorer.testnet.zama.org/address/0xcE762c7FDaac795D31a266B9247F8958c159c6d4) | — |

### Governance

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `ADMIN_MODULE` | `admin_module` | [`0x53dB449A96d0319DD1f90102dA116Bb9aB0483bB`](https://explorer.testnet.zama.org/address/0x53dB449A96d0319DD1f90102dA116Bb9aB0483bB) | — |
| `GATEWAY_SAFE` | `gnosis_safe` | [`0x3241b3A4036a356c5D7e36a432Da2B8e5739D9c9`](https://explorer.testnet.zama.org/address/0x3241b3A4036a356c5D7e36a432Da2B8e5739D9c9) | Only partially verified on Blockscout because verification of transparent proxy is not supported. |
| `GATEWAY_SAFE_L2_IMPLEM` | `safe_l2_implementation` | [`0x43cdd2cCbeB38Eb62fDf54e17aFBabf450ebBB01`](https://explorer.testnet.zama.org/address/0x43cdd2cCbeB38Eb62fDf54e17aFBabf450ebBB01) | This is not the proxy. The implementation is unique and can be reused for deploying new safes. |
| `GATEWAY_SAFE_PROXY_FACTORY` | `safe_proxy_factory` | [`0xaa5f197a549685a2C4a088069aB5793d3887A090`](https://explorer.testnet.zama.org/address/0xaa5f197a549685a2C4a088069aB5793d3887A090) | This is not the proxy. The proxy factory is unique and can be reused for deploying new safes. |
| `GOVERNANCE_OAPP_RECEIVER` | `layerzero_oapp_receiver` | [`0x998E9484Aa2a9Ae5B0C8a93B4bD2ea2a5C1B6fF0`](https://explorer.testnet.zama.org/address/0x998E9484Aa2a9Ae5B0C8a93B4bD2ea2a5C1B6fF0) | — |

### Pausing

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `PAUSER_SET_GATEWAY` | `pauser_set` | [`0x057dC9855536470A6D8C21d075bA17EA062A5dE7`](https://explorer.testnet.zama.org/address/0x057dC9855536470A6D8C21d075bA17EA062A5dE7) | — |

### Fees

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `FEES_SENDER_TO_BURNER` | `fees_sender_to_burner` | [`0x826106E9428460449d35F724F7098d0a67369AE2`](https://explorer.testnet.zama.org/address/0x826106E9428460449d35F724F7098d0a67369AE2) | Sends fees from Gateway Testnet to the burner on Sepolia |

### FHEVM Protocol

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `CIPHERTEXT_COMMITS` | `gateway_ciphertext_commits` | [`0xE327808C4aD514D6bd405e1f12cC86Fcd08e5228`](https://explorer.testnet.zama.org/address/0xE327808C4aD514D6bd405e1f12cC86Fcd08e5228) | — |
| `DECRYPTION` | `gateway_decryption` | [`0x5D8BD78e2ea6bbE41f26dFe9fdaEAa349e077478`](https://explorer.testnet.zama.org/address/0x5D8BD78e2ea6bbE41f26dFe9fdaEAa349e077478) | — |
| `GATEWAY_CONFIG` | `gateway_config` | [`0x94153006067B89399e059284f5a7Fe016940E332`](https://explorer.testnet.zama.org/address/0x94153006067B89399e059284f5a7Fe016940E332) | — |
| `INPUT_VERIFICATION` | `gateway_input_verification` | [`0x483b9dE06E4E4C7D35CCf5837A1668487406D955`](https://explorer.testnet.zama.org/address/0x483b9dE06E4E4C7D35CCf5837A1668487406D955) | — |
| `KMS_GENERATION` | `gateway_kms_generation` | [`0x5779Ac320BbDB267Cc4d1b77195a203F926bBC60`](https://explorer.testnet.zama.org/address/0x5779Ac320BbDB267Cc4d1b77195a203F926bBC60) | — |
| `MULTICHAIN_ACL` | `gateway_multichain_acl` | [`0xe877cA18d8Ea5490e9256e4B28414320726a8c3c`](https://explorer.testnet.zama.org/address/0xe877cA18d8Ea5490e9256e4B28414320726a8c3c) | — |
| `PROTOCOL_PAYMENT` | `gateway_protocol_payment` | [`0xAA1d9D4927A62f842F0DE5AD6b8dFDB074Fa62f2`](https://explorer.testnet.zama.org/address/0xAA1d9D4927A62f842F0DE5AD6b8dFDB074Fa62f2) | — |

## Polygon Amoy (`polygon_amoy`)

### Token

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `AMOY_USDC_MOCK` | `erc20` | [`0x8516e725223e3F829537D6A877E1aAE954811B69`](https://amoy.polygonscan.com/address/0x8516e725223e3F829537D6A877E1aAE954811B69) | USDCMock. Mock USDC on Polygon Amoy. Minting restricted to 1M tokens. |
| `AMOY_USDT_MOCK` | `erc20` | [`0x164F5A056166d8F2ce09FdAc6d040209a8C94d01`](https://amoy.polygonscan.com/address/0x164F5A056166d8F2ce09FdAc6d040209a8C94d01) | USDTMock. Mock USDT on Polygon Amoy. Minting restricted to 1M tokens |

### Wrappers registry

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `AMOY_TOKEN_WRAPPER_REGISTRY` | `token_wrapper_registry` | [`0xF486c3D4F4562760A43883e72E8D6f6Cf2EFdA94`](https://amoy.polygonscan.com/address/0xF486c3D4F4562760A43883e72E8D6f6Cf2EFdA94) | — |

### Confidential tokens

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `AMOY_CONFIDENTIAL_USDC_MOCK` | `confidential_wrapper` | [`0x7a1728f2A07cE4D62167dE1348af168509011b7b`](https://amoy.polygonscan.com/address/0x7a1728f2A07cE4D62167dE1348af168509011b7b) | cUSDCMock. |
| `AMOY_CONFIDENTIAL_USDT_MOCK` | `confidential_wrapper` | [`0x2ABad2203Eba104b52cf040cCcFA100Df15687F8`](https://amoy.polygonscan.com/address/0x2ABad2203Eba104b52cf040cCcFA100Df15687F8) | cUSDTMock. |

### Governance

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `AMOY_ADMIN_MODULE` | `admin_module` | [`0x43cdd2cCbeB38Eb62fDf54e17aFBabf450ebBB01`](https://amoy.polygonscan.com/address/0x43cdd2cCbeB38Eb62fDf54e17aFBabf450ebBB01) | — |
| `AMOY_GOVERNANCE_OAPP_RECEIVER` | `layerzero_oapp_receiver` | [`0x696fCA81b616b4cd08Ea436492a443046fF3c6a6`](https://amoy.polygonscan.com/address/0x696fCA81b616b4cd08Ea436492a443046fF3c6a6) | — |
| `AMOY_SAFE` | `gnosis_safe` | [`0xF0b1FE5DecfFe400fb141BBEAF9B181bCF76E3Cb`](https://amoy.polygonscan.com/address/0xF0b1FE5DecfFe400fb141BBEAF9B181bCF76E3Cb) | 3/5 Zama wallets |

### Pausing

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `AMOY_PAUSER_SET_HOST` | `pauser_set` | [`0xbD005B85E5de614661111930684d6F61D4a914a3`](https://amoy.polygonscan.com/address/0xbD005B85E5de614661111930684d6F61D4a914a3) | Immutable PauserSet on Polygon Amoy. Registered pauser: 0xb7D919BDC506E23BE2f34E9dBa25B2Af4C5141f0 |

### FHEVM Protocol

| Contract | Type | Address | Notes |
| -------- | ---- | ------- | ----- |
| `AMOY_ACL_HOST` | `fhevm_acl` | [`0xD99Cb9Fc3c42c87f2A4A12e8Fd60318d6bDdf985`](https://amoy.polygonscan.com/address/0xD99Cb9Fc3c42c87f2A4A12e8Fd60318d6bDdf985) | — |
| `AMOY_FHEVM_EXECUTOR` | `fhevm_executor` | [`0x89420269f61e4db00545cd99da0aEcA7fF0912f9`](https://amoy.polygonscan.com/address/0x89420269f61e4db00545cd99da0aEcA7fF0912f9) | — |
| `AMOY_HCU_LIMIT` | `fhevm_hcu_limit` | [`0x462f1920A9a7b5Aa74A36c3f49E38C34392B0546`](https://amoy.polygonscan.com/address/0x462f1920A9a7b5Aa74A36c3f49E38C34392B0546) | — |
| `AMOY_INPUT_VERIFIER` | `fhevm_verifier` | [`0x6e5A7D8b0c645467Cba7e62D6624917085118631`](https://amoy.polygonscan.com/address/0x6e5A7D8b0c645467Cba7e62D6624917085118631) | — |
| `AMOY_KMS_VERIFIER` | `fhevm_kms_verifier` | [`0xCD1D89E311bce4C8DEa9a0857a0c9A4E153D4041`](https://amoy.polygonscan.com/address/0xCD1D89E311bce4C8DEa9a0857a0c9A4E153D4041) | — |
| `AMOY_PROTOCOL_CONFIG` | `fhevm_protocol_config` | [`0x4CcF009Aba90D04f52b31fc7aDdE240578aFe10F`](https://amoy.polygonscan.com/address/0x4CcF009Aba90D04f52b31fc7aDdE240578aFe10F) | — |

## 0xRPC

https://0xrpc.io

Fast, Free, and private public RPC endpoints

#### Donations to

[0x76e6679eE4960B18941504c57a62F87EAaA559fd](https://etherscan.io/address/0x76e6679eE4960B18941504c57a62F87EAaA559fd) aka `0xrpcio.eth`

Accepts ETH, DAI, USDT, USDC, BNB from any EVM chains :)

#### Upptime

https://upptime.0xrpc.io

#### Updates

- Disabled polygon endpoint as the node seems unstable with volume of queries ( 25.02.09 )
- Added Unichain endpoint ( 25.02.15 )
- Disabled BNB Chain endpoint as the node seems unstable with volume of queries ( 25.02.21 )
- Added Hoodi Testnet endpoint ( 25.03.20 )
- Disabled Berachain endpoint as the node is unstable following tip ( 25.04.01 )
- Re-enabled BNB Chain mainnet, archive nodes are switched to pruned nodes to fulfill disk space requirement for long term operation ( 25.04.27 )
- Disabled BNB Chain mainnet as the node is draining all available RAMs, use alternative nodes please ( 25.06.03 )
- Due to hardware failures on server all nodes are down atm, use other nodes until it is recovered in a few days ( 25.06.30 )
- Due to excessive hardware usage Base node has been discontinued, thank you for using it! ( 25.09.27 )

#### About (TOS, Privacy Policy)

- We run nodes of multiple EVM networks (and with Bitcoin, Monero) as a public good.
- We now run full nodes for EVM chains by default, which is capable of deriving historic transactions receipts and contract events (like `eth_getTransactionReceipt` or `eth_getLogs`)
- Our endpoints are rate limited with less than 10 ~ 20 calls allowed per second so please use it wisely! (The limits are included with batch requests as well)
- We don't store any sent data nor any raw IPs. Refer [/privacy](/privacy) for more info.
- No tracking of any kind.
- Open issues on https://github.com/0xRPC/0xRPC.github.io/issues for any inquiries / bug reports on RPC.

#### Used by

- [Nethermind](https://github.com/NethermindEth/sedge/blob/6be63bd9761286fc197885f55743dc4e0ce08c37/configs/public_rpcs.go#L42)
- [Sigma Prime](https://github.com/sigp/siren/blob/ad9fc6eb09816eb7017b69a241c49c17da85026b/utilities/createWagmiConfig.ts#L19)
- [Swarm](https://github.com/ethersphere/storage-incentives/blob/8000a756a6a9c23d3a2da8dbde803438de23dcc7/hardhat.config.ts#L167)
- [Api3](https://github.com/api3dao/contracts/blob/282c344fe4cae2982b0cfcfe5d462621d0e5dfa2/CHANGELOG.md?plain=1#L116)
- [Frax](https://github.com/FraxFinance/fraxtal-node/blob/4681d2a7e1bef6dc9d368594fdfd88258e8fc5f9/.env.hoodi-testnet.SAMPLE#L4)
- [SubQuery Network](https://github.com/subquery/ethereum-subql-starter/blob/bd2ed434a02f73ebf25f815fde448c39f8f3d36b/Taiko/taiko-hoodi-starter/project.ts#L41)
- [Helios](https://github.com/helios-network/helios-core/blob/f7380da0afa41b657195ea633f39daa31f131afd/helios-chain/x/hyperion/types/params.go#L253)
- [HeimLabs](https://github.com/HeimLabs/coinbase-stakemyeth-backend/blob/06e55f417145e2d7b7afd98b58a0a7832c1acd61/config/index.ts#L13)
- [NilFoundation](https://github.com/NilFoundation/placeholder/blob/ba9ee053b856211556e57073eda71543da872dd6/load_block/load_block.py#L7)
- [Lanca](https://github.com/lanca-io/webapp/blob/a951bd3ddd42d5bd440e9275fed80a33261bbe5c/src/store/form/CreateFormStore.tsx#L45)
- [HebeBlock](https://github.com/HebePlatform/etc-classic-ui/blob/2ee3b246fc8a46ed2f2594884514908186024fd0/networkConfig.js#L243)
- [Gnosis Guild](https://github.com/gnosisguild/zodiac-modifier-roles/blob/a5ae54f7a9dabe4d075de86aacfc5ddc671b39f4/packages/evm/hardhat.config.ts#L120)

... [and more](https://github.com/search?q=0xrpc&type=code)

#### How to use

`$ cast block-number -r https://0xrpc.io/eth`

or 

`$ cast block-number -r wss://0xrpc.io/eth`

(All EVM endpoints support websockets)

#### Endpoints

- Monero Mainnet

https://xmr.0xrpc.io

- Ethereum Mainnet (Full, 128 state with all blocks)

https://0xrpc.io/eth

https://0xrpc.io/eth/v1 (Beacon)

- Ethereum Sepolia Testnet (Full, 128 state with all blocks)

https://0xrpc.io/sep

- Ethereum Hoodi Testnet (Full, 128 state with all blocks)

https://0xrpc.io/hoodi

- Gnosis Mainnet (Full, 128 state with all blocks)

https://0xrpc.io/gno

- Avalanche Mainnet (Full, 128 state)

https://0xrpc.io/avax

- Ethereum Classic Mainnet (Full, 128 state with all blocks)

https://0xrpc.io/etc

- ETC Mordor Testnet (Full, 128 state with all blocks)

https://0xrpc.io/mordor

- MintMe.com Mainnet (Full, 128 state with all blocks)

https://0xrpc.io/mint

- Optimism L2 Mainnet (Full, 128 state with all blocks)

https://0xrpc.io/op

- Unichain L2 Mainnet (Full, 128 state with all blocks)

https://0xrpc.io/uni

#### Listed on

- https://monero.fail
- https://chainlist.org

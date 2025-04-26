## 0xRPC

https://0xrpc.io

Fast, Free, and private public RPC endpoints

#### Upptime

https://upptime.0xrpc.io

#### Updates

- Disabled polygon endpoint as the node seems unstable with volume of queries ( 25.02.09 )
- Added Unichain endpoint ( 25.02.15 )
- Disabled BNB Chain endpoint as the node seems unstable with volume of queries ( 25.02.21 )
- Added Hoodi Testnet endpoint ( 25.03.20 )
- Disabled Berachain endpoint as the node is unstable following tip ( 25.04.01 )
- Re-enabled BNB Chain mainnet, archive nodes are switched to pruned nodes to fulfill disk space requirement for long term operation ( 25.04.27 )

#### About (TOS, Privacy Policy)

- We run nodes of multiple EVM networks (and with Bitcoin, Monero) as a public good.
- We now run pruned nodes for three networks (Ethereum, BNB Chain, Sepolia, Hoodi, Gnosis) based on Erigon3 nodes.
- All other non-archive full nodes are capable of deriving historic transactions receipts and contract events (like `eth_getTransactionReceipt` or `eth_getLogs`)
- Our endpoints are rate limited with less than 10 ~ 20 calls allowed per second so please use it wisely!
- We don't store any sent data nor any raw IPs. Refer [/privacy](/privacy) for more info.
- No tracking of any kind.
- Open issues on https://github.com/0xRPC/0xRPC.github.io/issues for any inquiries / bug reports on RPC.

#### How to use

`$ cast block-number -r https://0xrpc.io/eth`

or 

`$ cast block-number -r wss://0xrpc.io/eth`

(All EVM endpoints support websockets)

#### Endpoints

- Monero Mainnet

https://xmr.0xrpc.io

- Ethereum Mainnet (Full, 100_000 state with all blocks)

https://0xrpc.io/eth

https://0xrpc.io/eth/v1 (Beacon)

- Ethereum Sepolia Testnet (Pruned, 100_000 blocks only)

https://0xrpc.io/sep

- Ethereum Hoodi Testnet (Pruned, 100_000 blocks only)

https://0xrpc.io/hoodi

- BNB Chain Mainnet (Pruned, 100_000 blocks only)

https://0xrpc.io/bnb

- Gnosis Mainnet (Pruned, 100_000 blocks only)

https://0xrpc.io/gno

- Avalanche Mainnet (Pruned)

https://0xrpc.io/avax

- Ethereum Classic Mainnet (Full, 128 state with all blocks)

https://0xrpc.io/etc

- MintMe.com Mainnet (Full, 128 state with all blocks)

https://0xrpc.io/mint

- Optimism L2 Mainnet (Full, 128 state with all blocks)

https://0xrpc.io/op

- Base L2 Mainnet (Full, 128 state with all blocks)

https://0xrpc.io/base

- Unichain L2 Mainnet (Full, 128 state with all blocks)

https://0xrpc.io/uni

#### Listed on

- https://monero.fail
- https://chainlist.org

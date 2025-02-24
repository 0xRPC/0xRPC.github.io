## 0xRPC

https://0xrpc.io

Fast, Free, and private public RPC endpoints

#### Upptime

https://upptime.0xrpc.io

#### Updates

- Disabled polygon endpoint as the node seems unstable with volume of queries ( 25.02.09 )
- Added Unichain endpoint ( 25.02.15 )
- Disabled BNB Chain endpoint as the node seems unstable with volume of queries ( 25.02.21 )

#### About (TOS, Privacy Policy)

- We run nodes of multiple EVM networks (and with Bitcoin, Monero) as a public good.
- We now run archive nodes for three networks (Ethereum, Sepolia, Gnosis) based on Erigon3 archive nodes.
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

- Ethereum Mainnet (Archive)

https://0xrpc.io/eth

https://0xrpc.io/eth/v1 (Beacon)

- Ethereum Sepolia Testnet (Archive)

https://0xrpc.io/sep

- Gnosis Mainnet (Archive)

https://0xrpc.io/gno

- Avalanche Mainnet

https://0xrpc.io/avax

- Berachain Mainnet

https://0xrpc.io/bera

- Ethereum Classic Mainnet

https://0xrpc.io/etc

- Optimism L2 Mainnet

https://0xrpc.io/op

- Base L2 Mainnet

https://0xrpc.io/base

- Unichain L2 Mainnet

https://0xrpc.io/uni

#### Listed on

- https://monero.fail
- https://chainlist.org

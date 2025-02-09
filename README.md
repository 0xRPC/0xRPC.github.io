## 0xRPC

https://0xrpc.io

Fast, Free, and private public RPC endpoints

#### Upptime

https://upptime.0xrpc.io

#### Updates

- Disabled polygon endpoint as the node seems unstable with volume of queries ( 25.02.09 )

#### About (TOS, Privacy Policy)

- We run pruned nodes of multiple EVM networks (and with Bitcoin, Monero) as a public good.
- Using historical methods like `eth_getLogs` or `debug_traceCall` is discouraged as our nodes don't have historic data (Including block receipts, tx receipts, contract events, etc).
- Recommend use case for our RPC endpoints is to serve DApps and Wallets which requires latest state with `eth_call`, or `eth_getBalance`.
- Our endpoints are rate limited with less than 10 ~ 20 calls allowed per second so please use it wisely!
- We don't store any sent data nor any IPs or metadata.
- No tracking of any kind.
- Open issues on https://github.com/0xRPC/0xRPC.github.io/issues for any inquiries / bug reports on RPC.

#### How to use

`$ cast block-number -r https://0xrpc.io/eth`

#### Endpoints

- Monero Mainnet

https://xmr.0xrpc.io

- Ethereum Mainnet

https://0xrpc.io/eth

https://0xrpc.io/eth/v1 (Beacon)

- Ethereum Sepolia Testnet

https://0xrpc.io/sep

- BNB Chain Mainnet

https://0xrpc.io/bnb

- Gnosis Mainnet

https://0xrpc.io/gno

- Avalanche Mainnet

https://0xrpc.io/avax

- Optimism L2 Mainnet

https://0xrpc.io/op

- Base L2 Mainnet

https://0xrpc.io/base

#### Listed on

- https://monero.fail
- https://chainlist.org

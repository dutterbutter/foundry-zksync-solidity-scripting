## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.

## Documentation

https://foundry-book.zksync.io/

## Usage

### Build

```shell
$ forge build --zksync
```

### Test

```shell
$ forge test --zksync
```

### Format

```shell
$ forge fmt
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key> --zksync
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ cast --help
```

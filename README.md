## Foundry Fuzz and Invariant 

# Overview

In programming and software development, fuzzing or fuzz testing is an automated software testing technique that involves providing invalid, unexpected, or random data as inputs to a computer program. The program is then monitored for exceptions such as crashes, failing built-in code assertions, or potential memory leaks.

# Security researcher 

For the purpose of security, input that crosses a trust boundary is often the most useful.[1] For example, it is more important to fuzz code that handles the upload of a file by any user than it is to fuzz the code that parses a configuration file that is accessible only to a privileged user.

## Documentation

https://book.getfoundry.sh/

# Fuzz testing in Foundry 

involves automatically generating a wide range of inputs to test functions in smart contracts. 
This method helps in uncovering edge cases and ensuring that the contract behaves correctly under various scenarios.

# Invariant Testing in Foundry 

Invariant testing is about defining certain conditions or invariants that should always hold true for the state of the contract, 
regardless of the actions performed on it. These invariants are then tested to ensure they hold under different conditions and actions.

## Usage

openzeppelin-contracts

https://github.com/OpenZeppelin/openzeppelin-contracts/tree/01ef448981be9d20ca85f2faf6ebdf591ce409f3


### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```

## Foundry Fuzz and Invariant 

# Review

In programming and software development, fuzzing or fuzz testing is an automated software testing technique that involves providing invalid, unexpected, or random data as inputs to a computer program. The program is then monitored for exceptions such as crashes, failing built-in code assertions, or potential memory leaks.

# Security researcher 

For the purpose of security, input that crosses a trust boundary is often the most useful. For example, it is more important to fuzz code that handles the upload of a file by any user than it is to fuzz the code that parses a configuration file that is accessible only to a privileged user.

## Documentation

https://book.getfoundry.sh/

# Fuzz testing in Foundry 

involves automatically generating a wide range of inputs to test functions in smart contracts. 
This method helps in uncovering edge cases and ensuring that the contract behaves correctly under various scenarios.

# Invariant Testing in Foundry 

Invariant testing is about defining certain conditions or invariants that should always hold true for the state of the contract, 
regardless of the actions performed on it. These invariants are then tested to ensure they hold under different conditions and actions.

## Usage

***openzeppelin-contracts***

https://github.com/OpenZeppelin/openzeppelin-contracts/tree/01ef448981be9d20ca85f2faf6ebdf591ce409f3


***forge-std***

https://github.com/foundry-rs/forge-std/tree/36c303b7ffdd842d06b1ec2744c9b9b5fb3083f3


### 

### Format

```shell
$ forge fmt
```

### Contributing
Contributions are welcome! Please follow these steps:

1. Fork the project.
2. Create a new branch: git checkout -b feature-name
3. Make your changes and commit them: git commit -m 'Add some feature'
4. Push to the branch: git push origin feature-name
5. Submit a pull request.
Please make sure to update tests as appropriate.

### Contact 


***Master Foundry for Security Testing***

***Set up Foundry in your development environment. Start with basic testing and move on to more complex fuzz testing.***

```shell
git clone https://github.com/foundry-rs/foundry.git
cd foundry
cargo install --path 
```


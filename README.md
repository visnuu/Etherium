# HelloWorld Solidity Program

This Solidity program is a simple "Hello World" program that demonstrates the basic syntax and functionality of the Solidity programming language. The purpose of this program is to serve as a starting point for those who are new to Solidity and want to get a feel for how it works.

## Description

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a single function that returns the string "Hello World!". <br> This program serves as a simple and straightforward introduction to Solidity programming and can be used as a stepping stone for more complex projects in the future.

## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. Follow these steps:

1. Go to the [Remix website](https://remix.ethereum.org/).
2. Create a new file by clicking on the "+" icon in the left-hand sidebar.
3. Save the file with a `.sol` extension (e.g., `HelloWorld.sol`).
4. Copy and paste the following code into the file:

    ```solidity
    pragma solidity ^0.8.4;

    contract HelloWorld {
        function sayHello() public pure returns (string memory) {
            return "Hello World!";
        }
    }
    ```

5. Compile the code:
    - Click on the "Solidity Compiler" tab in the left-hand sidebar.
    - Ensure the "Compiler" option is set to "0.8.4" (or another compatible version).
    - Click on the "Compile HelloWorld.sol" button.

6. Deploy the contract:
    - Click on the "Deploy & Run Transactions" tab in the left-hand sidebar.
    - Select the "HelloWorld" contract from the dropdown menu.
    - Click on the "Deploy" button.

7. Interact with the contract:
    - Click on the deployed "HelloWorld" contract in the left-hand sidebar.
    - Click on the "sayHello" function.
    - Click on the "transact" button to execute the function and retrieve the "Hello World!" message.

## Authors

* **Metacrafter Chris** - [@metacraftersio](https://github.com/metacraftersio)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

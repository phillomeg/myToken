# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a Hardhat Ignition module that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat ignition deploy ./ignition/modules/Lock.js
```

This Solidity program is a simple "myToken" program that demonstrates the basic syntax and functionality of the Solidity programming language. The purpose of this program is to serve as a starting point for those who are new to Solidity and want to get a feel for how it works.

# how it works

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a single function that returns the string "myToken". This program serves as a simple and straightforward introduction to Solidity programming, and can be used as a stepping stone for more complex projects in the future.

# what it those 

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.


Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the following code into the file:



pragma solidity ^0.8.4;

contract HelloWorld {
    function sayHello() public pure returns (string memory) {
        return "Hello World!";
    }
}

Once the contract is deployed, you can interact with it by calling the sayHello function. Click on the "myToken" contract in the left-hand sidebar, and then click on the "sayHello" function. Finally, click on the "transact" button to execute the function and retrieve the "myToken" message.

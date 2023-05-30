# SOL Token

## Description

The SOL Token is a simple Solidity program that showcases the basic syntax and functionality of the Solidity programming language. This program demonstrates how to mint and burn tokens on a specified account based on the provided value. It serves as a beginner-friendly introduction to Solidity programming and can be used as a foundation for more complex projects in the future.

## Getting Started

### Executing the Program

To run this program, you can use Remix, an online Solidity IDE. Follow the steps below to get started:

1. Go to the Remix website at https://remix.ethereum.org/.

2. Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., myToken.sol).

3. Copy and paste the content of the myToken.sol file into the newly created file.

4. To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile myToken.sol" button.

5. Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "myToken" contract from the dropdown menu, and then click on the "Deploy" button.

6. After the contract is deployed, you can interact with it by calling the `mint` function, providing an address and the value to be minted. Click on the "totalSupply" button to see the updated total supply. 

7. To burn tokens from a specified address, provide the address and the amount of tokens you would like to burn. Note: If the amount of tokens to be burned is greater than the token supply or the balance of the specified address, the process won't conclude.

## Authors

Olalekan Solomon AWOYEMI

#### Video Explanation
[Link to video explanation](https://www.loom.com/share/5696ac4e2d764e32845b9f9664ef91a7)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

# Prime and Composite Numbers(Frontend+Solidity)

I have created a frontend where you can get the square of a number(if prime) or cube of a number(if composite) using a smart contract.

## Description

In the frontend, you will need to connect your wallet in hardhat network and have some test tokens ready.

There are two buttons to calculate the cube and square of the numbers and result is displayed on the screen.

getBalance: A public view function that returns the current balance of the contract.

Prime Square Calculation:
prime_square: A public payable function that takes a parameter n and calculates the square of n if it is a prime number. It iterates through numbers up to the square root of n and updates the balance if n is a prime number.

Composite Cube Calculation:
composite_cube: A public function that takes a parameter n and calculates the cube of n if it is a composite number. It iterates through numbers up to the square root of n and updates the balance if n is a composite number.

## Getting Started

### Executing code

After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type:
 ```
 npm i
 ```
  It is used to install the dependencies specified in the package.json file for the project.

Open two additional terminals in your Visual Studio Code (VS Code) editor.
   
2. In the second terminal type:
```
npx hardhat node
```
  npx is a package runner tool that comes with npm.
  hardhat is a development environment to compile, deploy, test, and debug your Ethereum smart contracts.
  node is a command provided by Hardhat to run a local Ethereum node. This command starts a local Ethereum blockchain on your machine.
   
3. In the third terminal, type:
 ```
 npx hardhat run --network localhost scripts/deploy.js
 ```
  hardhat run is used to run scripts or tasks defined in your Hardhat project.
  --network localhost specifies the network on which to run the script, in this case, the local Ethereum blockchain.
  
4. Back in the first terminal, type
 ```
 npm run dev
 ```
   to launch the front-end.
  This script is typically used to start a development server for the front-end of the application. The specifics of what it does depend on how it's configured in the package.json   file.
After this, the project will be running on your localhost. 
Typically at http://localhost:3000/

## Authors

Lalith Raj 

[@lalithrajrayappa@gmail.com]

## License

This project is licensed under the [MIT] License - see the LICENSE.md file for details

## Project Intro
My name is Jordi Piqueras and I have created this Smart Contract to help the people that wants to do an ICO (Initial Coin Offering)/Create a token with the ERC20 Standard to get cryptocurrencies from investors to create and improve their projects. 

**If you want to help me you can add me on LinkedIn and recommend me. Thanks you so much.**

## Understand the Smart Contract (SC).
The main functionality of this Smart Contract is to exchange Ethers (Ethereum) for ICO Tokens.
To do an ICO I recommend you to set an SC on the Ethereum Blockchain, you only have to give the SC address to your investors and when they send the Ethers to SC address automatically they receive your tokens.

## How to use the Smart Contract
1. Upload the Smart Contract to an Address with the "Quanity of tokens", "name_of_the_Token" and "symbol_of_the_token".
2. I recommend you to test the Smart Contract to understand it.
3. Show the address of the Smart Contract in your website and let the visitors exchange their Ethers for your Tokens automatically.

If you have doubts about how to use the SC you can find me on LinkedIn: https://www.linkedin.com/in/jordi-piqueras-50b439b9/.

More info about Ethereum and Smart Contracts: 
https://solidity.readthedocs.io/en/latest/ 
https://theethereum.wiki/w/index.php/ERC20_Token_Standard

## (Optional) Test the Smart Contract in a Test Environment
1. Copy the content of the file TokenERC20.sol and paste on this webeditor URL: (https://remix.ethereum.org/#optimize=false&version=soljson-v0.4.20+commit.3155dd80.js).

2. Configure the editor:

Mark the Option Autocompile and press "Start Compile" to upload the contract.

![alt text](https://image.prntscr.com/image/TP4aPTieR9ehhPTMIzEDfA.png)

* Each Smart Contract on Ethereum consume Gas then you need to define a number.

Chose the TokenERC20 contract

![alt text](https://image.prntscr.com/image/E928A52IT2KJFa7l1uKTZw.png)

3. Complete the "Create input" with you Token data:
The structure of the data is: quantity of tokens, "Name of the Token", "Symbol of the token"
Example with Bitcoin: 100, "Bitcoin", "BTC"

![alt text](https://image.prntscr.com/image/pRoJ0EcTRMua5GBs5Wecjw.png)

4. Run the Code, this will execute the constructor method "function TokenERC20".

5. Copy the address of the tokens and paste on the input "balanceOf" with quotes to see the balance of the address, press the button to see it.

![alt text](https://image.prntscr.com/image/RlDWd-ueQYa98tgXoK_5TQ.png)

6. Test the function transfer: Complete input Create and after that put an address on the input transfer and a value ("address", value):
Example: "0x14723a09acff6d2a60dcdf7aa4aff308fddc160c", 2
You can use another Test address: "0x14723a09acff6d2a60dcdf7aa4aff308fddc160c"
After do the transfer verify the token balance of this address.

![alt text](https://image.prntscr.com/image/8H19CEOJTZuX0J5r4UxSew.png)

You can test transfers modifying the input "account address" and the input "transfer".

![alt text](https://image.prntscr.com/image/SA7gthGYS3uv78F_0lYyQQ.png)
![alt text](https://image.prntscr.com/image/li4E2NJ9ReCfhuQFoXnQkw.png)

## Community
Special mention to Platzi Team to introduce me in the Blockchain tech.
https://platzi.com/cursos/

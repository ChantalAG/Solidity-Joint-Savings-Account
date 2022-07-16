# Solidity-Joint-Savings-Account
Unit 20 Solidity Homework Assignment 
![image](https://user-images.githubusercontent.com/99493522/179358348-b30bc789-5fcb-4fcf-b4c4-8fab2201f6c3.png)


## Background
In this assignment, a fintech startup company has recently hired you. This company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.
To automate the creation of joint savings accounts, a Solidity smart contract was created using Remix IDE that accepts two user addresses. These addresses will be able to control a joint savings account. The smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

### Components of the Project
1.	The completed Solidity [joint_savings.sol](https://github.com/ChantalAG/Solidity-Joint-Savings-Account/blob/main/joint_savings.sol) smart contract.
2.	A folder named [Execution_Results](https://github.com/ChantalAG/Solidity-Joint-Savings-Account/tree/main/Execution_Results) containing a pdf document of the images that confirm the deposit and withdrawal transactions, which test that the JointSavings functionality in the JavaScript VM worked as expected.

## Resources
[Remix IDE](https://remix-ide.readthedocs.io/en/latest/) documentation

## Instructions
The steps for this project are divided into the following sections:
1.	Create a Joint Savings Account Contract in Solidity
2.	Compile and Deploy Your Contract in the JavaScript VM
3.	Interact with Your Deployed Smart Contract

## Screenshots
![image](https://user-images.githubusercontent.com/99493522/179358808-67471271-dc86-4ab0-b12c-fc2c06881216.png)

### Interaction with Smart Contract

#### Step 1: Use the setAccounts function to define the authorized Ethereum address that will be able to withdraw funds from your contract.

![image](https://user-images.githubusercontent.com/99493522/179358864-910fbde8-5662-440b-aaab-5ffd26708f66.png)


#### Step 2: Test the deposit functionality of your smart contract by sending the following amounts of ether. After each transaction, use the contractBalance function to verify that the funds were added to your contract:

* Transaction 1: Send 1 ether as wei.


![image](https://user-images.githubusercontent.com/99493522/179358886-64781c29-d8f6-428e-8ad2-74183f744773.png)

* Transaction 2: Send 10 ether as wei.


![image](https://user-images.githubusercontent.com/99493522/179358898-c052828d-6f0d-46ac-ba10-e3817a43b523.png)

* Transaction 3: Send 5 ether.


![image](https://user-images.githubusercontent.com/99493522/179358919-f59a2841-c421-4e8c-b481-101a9f0160d4.png)

#### Step 3: Once you’ve successfully deposited funds into your contract, test the contract’s withdrawal functionality by withdrawing 5 ether into accountOne and 10 ether into accountTwo. After each transaction, use the contractBalance function to verify that the funds were withdrawn from your contract. Also, use the lastToWithdraw and lastWithdrawAmount functions to verify that the address and amount were correct.
![image](https://user-images.githubusercontent.com/99493522/179358955-f8e13a7a-f2ea-44c0-b4a8-c06ca0690cdb.png)

## Contributors
Chantal Garnett


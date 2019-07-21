# Udacity Blockchain Developer Nanodegree
Choose which project you want to view:

## [Project: Managing you Blockchain identity](https://github.com/linked0/myblockchain/tree/master/ud-blockchain-proj2)

### Build This Project
To complete this project, follow the steps below. Then submit the required information outlined in the Prepare for Submission section.

Project Steps
Step 1: Navigate to Electrum.org to download and install your bitcoin wallet.

Step 2: Walk through the wallet interface and find your wallet address.

Step 3: Navigate to our web application and use your wallet address to generate a message.

Step 4: Use your wallet to sign the message.

Step 5: Validate message signature with our web application.

Step 6: Using your text editor, document your wallet address, message, and validated message signature.

Step 7: Submit your project document

## [Project: Private Blockchain](https://github.com/linked0/myblockchain/tree/master/ud-blockchain-proj3)
Building Your Own Private Blockchain

In this course, you learned all about blockchain and transaction data models as well as the differences between public and private blockchains. In this project you will put this knowledge to practice by creating your own private blockchain. However, this current model has some flaws in saving, persisting, and validating data. Your challenge in this project is to refactor your private blockchain to securely handle this information.

## [Project: Build Blockchain Notary Service](https://github.com/linked0/myblockchain/tree/master/ud-blockchain-proj4)
Build a Private Blockchain Notary Service!

In this project, you will build a Star Registry Service that allows users to claim ownership of their favorite star in the night sky.

### What will you need to do?
#### Create a Blockchain dataset that allow you to store a Star (You should have this done in Projects 2 and 3)
* The application will persist the data (using LevelDB).
* The application will allow users to identify the Star data with the owner.

#### Create a Mempool component
* The mempool component will store temporal validation requests for 5 minutes (300 seconds).
* The mempool component will store temporal valid requests for 30 minutes (1800 seconds).
* The mempool component will manage the validation time window.

#### Create a REST API that allows users to interact with the application.
* The API will allow users to submit a validation request.
* The API will allow users to validate the request.
* The API will be able to encode and decode the star data.
* The API will allow be able to submit the Star data.
* The API will allow lookup of Stars by hash, wallet address, and height.

[Project 5](https://github.com/linked0/myblockchain/tree/master/ud-blockchain-proj5)

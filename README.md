# Angular9-Ethereum-Truffle
Using Angular 9 for Front-End. Truffle Box for compiling and migrating contracts and ganache-cli to run the the test network.

Install Truffe, Angular Cli and Ethereum Client. We will be using ganache-cli for Ethereum test network.

# Ethereum network 
Ganache-cli as a testnetwork

$ npm install -g ganache-cli

$ ganache-cli



# Angular 9 for Front-End
$ npm install -g @angular/cli

You might come across some node-gyp issues if it had never bothered you during compilation

# Truffle Box 
Use it for compiling and migrating Contracts

$ npm install -g truffle

If you don't want to use compiled and migrated contracts in this repo.

You can run the following command:

$ truffle unbox Quintor/angular-truffle-box

$ truffle compile && truffle migrate


$ npm start

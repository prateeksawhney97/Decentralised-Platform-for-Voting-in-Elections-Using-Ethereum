# Decentralised Platform for Voting in Elections Using Ethereum

## Problem Statement:

Electoral fraud, sometimes referred to as Fake Votes, is illegal interference with the process of an election, either by increasing the vote share of the favored candidate, depressing the vote share of the rival candidates, or both. The problem is to build a mechanism using which vote counterfeiting can be avoided and genuine votes are being considered.

#### Youtube Link - https://www.youtube.com/watch?v=UlVT_Aiz4kk&feature=youtu.be

## Tools Required:

- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Steps to run the project:

### Step 1. Clone the project

### Step 2. Install dependencies
```
$ cd election
$ npm install
```
### Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. 


### Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
Migration of the election smart contract is necessary each time Ganache is restarted.

### Step 5. Configure Metamask

- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

### Step 6. Run the Front End Application

`$ npm run dev`
Visit this URL in your browser: http://localhost:3000



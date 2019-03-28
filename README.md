# Decentralised Platform for Voting in Elections Using Ethereum

## Problem Statement:

Electoral fraud, sometimes referred to as Fake Votes, is illegal interference with the process of an election, either by increasing the vote share of the favored candidate, depressing the vote share of the rival candidates, or both. The problem is to build a mechanism using which vote counterfeiting can be avoided and genuine votes are being considered.

## Our Solution:

Our Solution is to build a Decentralised application on Blockchain using Ethereum, so that the voting system becomes transparent and unbiased. One of the key pillars of any healthy democratic system is the presence of independent and impartial elections in a nation. This is possible by Blockchain where we can keep the vote counts and other electoral data protected. The application would consist of a list of eligible candidates for election and we, as a voter, using our unique account having a unique private key, can cast a single vote to the candidate. This would require some ether, but the "Fake Votes" problem can be eliminated.

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



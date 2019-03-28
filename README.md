# Decentralised Platform for Voting in Elections Using Ethereum

## Problem Statement:

Electoral fraud, sometimes referred to as Fake Votes, is illegal interference with the process of an election, either by increasing the vote share of the favored candidate, depressing the vote share of the rival candidates, or both. The problem is to build a mechanism using which vote counterfeiting can be avoided and genuine votes are being considered.

## Our Solution:

Our Solution is to build a Decentralised application on Blockchain using Ethereum, so that the voting system becomes transparent and unbiased. One of the key pillars of any healthy democratic system is the presence of independent and impartial elections in a nation. This is possible by Blockchain where we can keep the vote counts and other electoral data protected. The application would consist of a list of eligible candidates for election and we, as a voter, using our unique account having a unique private key, can cast a single vote to the candidate. This would require some ether, but the "Fake Votes" problem can be eliminated.

#### Youtube Link - https://www.youtube.com/watch?v=UlVT_Aiz4kk&feature=youtu.be

#### Presentation Link - https://docs.google.com/presentation/d/1OBUWAH6HTC2MWPyb7WhUfk7ApNunuYISmPe7oKrqR7o/edit#slide=id.p

## Tools Required:

- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Steps to run the project:

### Step 1. Clone the project

### Step 2. Install dependencies
```
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

## Screenshots:

#### Initial Page showing the candidates for elections:

![Screenshot from 2019-03-28 20-32-02](https://user-images.githubusercontent.com/34116562/55181671-20ede180-51b2-11e9-9ce2-7592e1ad81de.png)

#### Selecting account from MetaMask and Ganache:

![Screenshot from 2019-03-28 20-32-24](https://user-images.githubusercontent.com/34116562/55181679-22b7a500-51b2-11e9-9ef5-612a41661832.png)
![Screenshot from 2019-03-28 20-32-47](https://user-images.githubusercontent.com/34116562/55181684-24816880-51b2-11e9-9f5b-37338e2d985a.png)

#### Importing account in MetaMask by Private key of any account from Ganache GUI.

![Screenshot from 2019-03-28 20-32-58](https://user-images.githubusercontent.com/34116562/55181689-264b2c00-51b2-11e9-848a-5fa56a1fd0d8.png)
![Screenshot from 2019-03-28 20-33-29](https://user-images.githubusercontent.com/34116562/55181695-28ad8600-51b2-11e9-87a5-4a415c5793dd.png)
![Screenshot from 2019-03-28 20-33-39](https://user-images.githubusercontent.com/34116562/55181698-2cd9a380-51b2-11e9-9d0a-3154a6f8b6e5.png)

#### Casting the vote from Imported Account:

![Screenshot from 2019-03-28 20-33-51](https://user-images.githubusercontent.com/34116562/55181705-2fd49400-51b2-11e9-9780-74c53eac3737.png)
![Screenshot from 2019-03-28 20-34-11](https://user-images.githubusercontent.com/34116562/55181711-3236ee00-51b2-11e9-8a67-daa3e2a3d9f3.png)
![Screenshot from 2019-03-28 20-34-41](https://user-images.githubusercontent.com/34116562/55181716-34994800-51b2-11e9-8823-426d0c23ab87.png)
![Screenshot from 2019-03-28 20-34-59](https://user-images.githubusercontent.com/34116562/55181722-36fba200-51b2-11e9-8a08-89faf5d6e4b2.png)
![Screenshot from 2019-03-28 20-35-30](https://user-images.githubusercontent.com/34116562/55181738-39f69280-51b2-11e9-9db7-129b9138e74e.png)
![Screenshot from 2019-03-28 20-35-51](https://user-images.githubusercontent.com/34116562/55181743-3cf18300-51b2-11e9-8923-79669e9eeb36.png)
![Screenshot from 2019-03-28 20-36-21](https://user-images.githubusercontent.com/34116562/55181753-411da080-51b2-11e9-84c7-f3028bdc4daa.png)
![Screenshot from 2019-03-28 20-36-51](https://user-images.githubusercontent.com/34116562/55181759-44189100-51b2-11e9-92c6-8fd5c71fcd9c.png)

# Flipkartgrid-4.0
Let's begin! Make sure you have git and npm installed. Clone the repo and cd into it, and install all required dependencies using npm.

```
git clone https://github.com/chandan25809/Flipkartgrid-4.0.git
cd Flipkartgrid-4.0
npm install
```

To deploy to a local blockchain (in this instance, hardhat's local chain), run the following commands:

```
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost
npx hardhat run scripts/deploy_arbitrum.js --network rinkarby
```

Then, to start the front-end website at [http://localhost:3000/](http://localhost:3000/), run:

```
cd src
npm start
```

And to run the tests on Warranties.sol, the main contract, run:

```
npx hardhat test
```

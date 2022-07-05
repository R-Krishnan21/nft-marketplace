## Full stack NFT marketplace built with Solidity,Hardhat, IPFS, & Next.js

To run this project locally, follow these steps.


cd polygon-ethereum-nextjs-marketplace

# install using NPM or Yarn
1. npm install

# or

yarn
```

2. Start the local Hardhat node

```sh
npx hardhat node
```

3. With the network running, deploy the contracts to the local network in a separate terminal window

```sh
npx hardhat run scripts/deploy.js --network localhost
```

4. Start the app

```
npm run dev
```

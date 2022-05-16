<img width="1436" alt="Screenshot 2022-05-16 at 9 13 24 PM" src="https://user-images.githubusercontent.com/54937640/168631948-1e932808-dd9c-49b0-a9c8-5c05817ab6f9.png">
<img width="1437" alt="Screenshot 2022-05-16 at 9 13 36 PM" src="https://user-images.githubusercontent.com/54937640/168631983-e9a2bf84-ee8a-4045-bfa7-8401402dd241.png">
## Full stack NFT marketplace built with Metamask , Hardhat , Solidity, IPFS, & Next.js 
#### Local setup

To run this project locally, follow these steps.

1. Clone the project locally, change into the directory, and install the dependencies:

cd polygon-ethereum-nextjs-marketplace

# install using NPM or Yarn
```
npm install
```
# or
```
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

If using Infura, update __.infuraid__ with your [Infura](https://infura.io/) project ID.

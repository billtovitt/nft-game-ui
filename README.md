# NFT Game UI

### 👋 Welcome

To get started with this project, clone this repo and follow these commands:

1. Run `npm install` at the root of your directory
2. Run `npm run start` to start the project
3. Start coding!

### 🙋 Note on contract redeploys

Smart contracts are **immutable**. That means changing a contract requires a full redeploy. This event will generate a brand new contract and it will reset all the variables. Basically, we'd lose all our NFT data if we wanted to update the contract's code.

If you _really_ want to change your contract, you need to do **3** things:

1. Deploy contract again on backend
2. Update contract address on frontend
3. Update abi file on frontend

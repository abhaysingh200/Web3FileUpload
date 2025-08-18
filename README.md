📤 Upload Contract

A simple Solidity smart contract to store URLs on-chain and manage access for other users. Built with Hardhat for easy development and testing.

⚡ Features

Add multiple URLs per user

Grant/revoke access to other users

Track ownership and access history

View URLs if access is allowed

Check list of users with access




1️⃣ Compile the Contract

Before deploying, make sure your contract is compiled:

npx hardhat compile


This generates the artifacts (ABI + bytecode) needed for deployment.

2️⃣ Deploy the Contract

Run your deploy script to deploy on the local Hardhat network:

npx hardhat run scripts/deploy.js --network localhost


After running this, you’ll see the deployed contract address in the terminal. Copy it carefully.

3️⃣ Update the Contract Address

In your frontend (React, Node, or whatever you’re using), replace the old contract address with the newly deployed contract address from step 2.

Example in a JS file:

export const contractAddress = "0xYourNewContractAddressHere";

4️⃣ Start the Local Node (Optional)

If you haven’t started a local Hardhat node yet, run:

npx hardhat node


Then redeploy using the same deploy command. This is useful if you want persistent accounts to interact with.

5️⃣ Run Your Frontend

Finally, start your frontend to interact with the deployed contract:

npm start

# DEX app

Create your own DEX for your ERC-20 token. Find the related contracts in the [dex-contracts repository](https://github.com/thirdweb-example/dex-contracts).

## Installation

After cloning this repository, install the dependencies using the following command:

```bash
# npm
npm install

# yarn
yarn install
```

## Adding details

Make sure you deploy the contracts specified in the dex-contracts repository and add the contract details in the `const/details.ts` file.

## Running the app

Use the following command to start the development server:

```bash
# npm
npm run dev

# yarn
yarn dev
```

## Conclusion

If you need any support, feel free to join our [Discord server](https://discord.gg/thirdweb) and ask us. If you have any feedback related to thirdweb, please leave it on our [feedback board](https://feedback.thirdweb.com).

# thirdweb build

```bash
gitpod /workspace/TW-Dex/dex-contracts (main) $ npx thirdweb build

    $$\     $$\       $$\                 $$\                         $$\       
    $$ |    $$ |      \__|                $$ |                        $$ |      
  $$$$$$\   $$$$$$$\  $$\  $$$$$$\   $$$$$$$ |$$\  $$\  $$\  $$$$$$\  $$$$$$$\  
  \_$$  _|  $$  __$$\ $$ |$$  __$$\ $$  __$$ |$$ | $$ | $$ |$$  __$$\ $$  __$$\ 
    $$ |    $$ |  $$ |$$ |$$ |  \__|$$ /  $$ |$$ | $$ | $$ |$$$$$$$$ |$$ |  $$ |
    $$ |$$\ $$ |  $$ |$$ |$$ |      $$ |  $$ |$$ | $$ | $$ |$$   ____|$$ |  $$ |
    \$$$$  |$$ |  $$ |$$ |$$ |      \$$$$$$$ |\$$$$$\$$$$  |\$$$$$$$\ $$$$$$$  |
     \____/ \__|  \__|\__|\__|       \_______| \_____\____/  \_______|\_______/ 

 💎 thirdweb-cli v0.10.23 💎

✔ Detected project type: hardhat
✔ Compilation successful


🔎 Detected extension on DEX
✔️ ERC20
✔️ ERC20Mintable
✔️ ERC20BatchMintable
✔️ ERC20Permit
✔️ ContractMetadata
✔️ Ownable

ℹ Suggested extensions
- ERC20Burnable - https://portal.thirdweb.com/interfaces/erc20burnable
- ERC20ClaimConditionsV1 - https://portal.thirdweb.com/interfaces/erc20claimconditionsv1
- ERC20ClaimConditionsV2 - https://portal.thirdweb.com/interfaces/erc20claimconditionsv2
- ERC20ClaimPhasesV1 - https://portal.thirdweb.com/interfaces/erc20claimphasesv1
- ERC20ClaimPhasesV2 - https://portal.thirdweb.com/interfaces/erc20claimphasesv2
- ERC20SignatureMintable - https://portal.thirdweb.com/interfaces/erc20signaturemintable
- Permissions - https://portal.thirdweb.com/interfaces/permissions

ℹ Once you're done writing your contracts, you can run the following command to deploy them:

     npx thirdweb@latest deploy
```
# thirdweb deploy

```bash
gitpod /workspace/TW-Dex/dex-contracts (main) $ npx thirdweb deploy

    $$\     $$\       $$\                 $$\                         $$\       
    $$ |    $$ |      \__|                $$ |                        $$ |      
  $$$$$$\   $$$$$$$\  $$\  $$$$$$\   $$$$$$$ |$$\  $$\  $$\  $$$$$$\  $$$$$$$\  
  \_$$  _|  $$  __$$\ $$ |$$  __$$\ $$  __$$ |$$ | $$ | $$ |$$  __$$\ $$  __$$\ 
    $$ |    $$ |  $$ |$$ |$$ |  \__|$$ /  $$ |$$ | $$ | $$ |$$$$$$$$ |$$ |  $$ |
    $$ |$$\ $$ |  $$ |$$ |$$ |      $$ |  $$ |$$ | $$ | $$ |$$   ____|$$ |  $$ |
    \$$$$  |$$ |  $$ |$$ |$$ |      \$$$$$$$ |\$$$$$\$$$$  |\$$$$$$$\ $$$$$$$  |
     \____/ \__|  \__|\__|\__|       \_______| \_____\____/  \_______|\_______/ 

 💎 thirdweb-cli v0.10.23 💎

✔ Detected project type: hardhat
✔ Compilation successful
✔ Processing contract: "DEX"
✔ Upload successful
✔ Open this link to deploy your contracts: https://thirdweb.com/contracts/deploy/QmbjZ7i42HK***********************
```

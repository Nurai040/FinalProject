# FinalProject

![image](https://user-images.githubusercontent.com/80448087/202789944-26bf6bbf-c0a3-47e7-9414-d92f65c5165b.png)


# Installation
For this project you need to have Remix IDE, json editor, filebase, Metamask, and Opensea testnet


# Usage
First open the Remix IDE create the new workplace, and within the new workplace copy and paste the Token.sol code. After compiling deploy using goerli testnet. Second, create a new workplace and add NFT.sol to it, after compiling deploy it using goerli testnet.
The next thing to do is to create a metadatas to mint the NFT. Go to filebase and upload there your image and json file with the link to that image:
![image](https://user-images.githubusercontent.com/80448087/202790425-8dd13b92-ff90-4adc-adea-c0b7a42d13bf.png)

After this go to remix and under the deployed contracts use the function safeMint to add your metadatas:
![image](https://user-images.githubusercontent.com/80448087/202790685-108306f7-e73b-4bad-8c00-3d089cdc9870.png)
Eventually, you can check that NFTs on your Opensea testnet account.

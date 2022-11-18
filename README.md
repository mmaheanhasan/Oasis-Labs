# OASIS-Labs DAO!
Collective effort towards building massively scaled interoperable network of real-time rendered 3D virtual worlds using generative AI.

![welcometooasislabs](https://user-images.githubusercontent.com/73466007/202773052-3bae235f-1015-4e97-9053-5de49772408d.PNG)

## Inspiration

In the last few months, I saw so many of my friends from the AI field created some interesting open-source stable diffusion models using Natural Language Processing, and those models worked like magic. Some are currently using stable diffusion to generate real-time rendered 3D worlds. Their models are evolving at a faster rate, and they’re praised by a lot of people on Twitter. But when they tried to raise money to keep their machines running, only a handful of people actually helped them via buy me a coffee weblink. So, I thought it cannot be just like that, why not make a DAO where thousands of people can adopt the decentralized community model, create a treasury, and fund those creative works using crypto-economic models. I did some research to see whether some people built this or not, and I wondered to see that not a single hackathon project within the last few EthGlobals did something like that. So, I researched, brainstormed, and took the approach to build OASIS Labs as my first ever web3 project where web3 artists, AI researchers, AI creators, developers, and marketers can be bound together by shared value and shared incentives to give life to these endless possibilities of generative AI.

## What it does

- **In my MVP** that I created within the last 5 days from the remaining deadline, I made just a basic infrastructure that doesn’t wholly portray my envision, but still:
    - On the landing page, I explained what OASIS Labs do and then let people connect their wallet if they wish to.
    - After Connecting your wallet, you will be directed to mint your ERC-1155 OASIS Labs membership NFT.
    - Only after minting the NFT, you will get the opportunity to see the membership page where you can see all the remaining members and how much governance token(OASIS Token) they hold. You will also see that token holders can vote on proposals on-chain.
    - I can also do token airdrops to members using a randomness function in a set limit.
    
    ![memberpage](https://user-images.githubusercontent.com/73466007/202773898-016df1bf-6ebd-4a47-81e2-74e641858671.PNG)


- **In Polygon mainnet:**
    - It will be different when I deploy OASIS Labs to the Polygon Mainnet. I will use Polygon ID for its unique functionality of ZK-based, fully private Sybil-resistant governance model. So, the governance system will be reputation-based, not wealth. Also, the process of becoming a DAO member won’t be just random.
    - OASIS Labs will use IPFS and Filecoin extensively for the DAO tooling. For example, It will integrate Bacalhau to process larger datasets while working with large NLP models.
    - The voting mechanism won’t wholly be on-chain. OASIS Labs will integrate IPFS and Chainlink Oracle for a performing off-chain mechanism.
    - OASIS Labs will integrate the NFT Index service of Truflation for its later workarounds with ERC-721 NFTs.
    - Integration of Render Network for distributed GPU rendering in Blockchain because it will be the key to generating high-quality real-time render in Blockchain.
    - After collaborating with experienced artists and developers and integrating all the other tools that I explained above to take OASIS into mainnet, OASIS labs will be a DAO with a treasury where OASIS citizens will be able to fund projects they wish and start collaborating with anyone with a shared incentive. OASIS Labs will be capable of leaping into the new frontier of the internet after going to the mainnet.

## How I built it

- Polygon Mumbai Testnet:
    - Membership NFT contract: 0xe7EE16b6Cd943A0348d682c9B2E734c1e3F18E7a
    - ERC-20 Token contract: 0x8dC72d22A5ca36f781d2BE0882b5280478cc9982
    - DAO Governance Contarct: 0xc9ED680594F2EdDDBCB007245C1eEFCBbD96708b
- Filecoin and IPFS: Used NFT.Storage to store asset Metadata with URL: ipfs://bafyreifjxlnzj4jlebw44xownhzaew36w3hzra74q2bsx4eccqurhbfpnm/metadata.json
- Chainlink VRF for verified randomness in token airdrop
- Quicknode: Ran QuickNode API on Polygon Mumbai testnet network
- Thirdweb: Used their SDK.
- Stable Diffusion: Generated all the graphics using generative AI.


## What's next for OASIS Labs

- Going to Polygon mainnet with at least a hundred talented developers, creators and researchers while integrating with all the tools mentioned above in the "What It Does" Polygon mainnet section.

![RARI Chain Logo](./public/chain_logo.png)

# Build with Rari Template

This template is designed for developers looking to build on the RARI Chain, leveraging the Foundry framework for smart contract development. It includes a frontend scaffolded with Next.js and a set of pre-configured packages for seamless integration with RARI Chain's features, including NFT creation, trading, and displaying using frames on Warpcast.

```bash
yarn install
```


**Smart Contracts**: Navigate to the `contracts` folder. This folder is set up with Foundry and includes common NFT contracts, scripts, and tests for rapid development on RARI Chain.

**Build Your Project**: After making your desired changes, build your project with:
    
    ```bash
    yarn build
    ```
**Deploy Frontend to RARI Chain**: Deploy your frontend to the RARI Chain by running:
    ```bash
    yarn run
    ```

   This command builds your Next.js app and deploys it to IPFS, making it accessible on the RARI Chain.

## Key Packages

- `@rarible/types`, `@thirdweb-dev/react`, `@thirdweb-dev/sdk`: For interacting with the Rarible protocol and integrating thirdweb's development tools.
- `@web3modal/wagmi`, `wagmi`: For web3 modal and hooks, essential for dApp interaction.
- `frames.js`: For creating frames on Warpcast to display your NFTs in an engaging way.


## Environment Variables

To run this project, you will need to add environment variables. Check the `.env.example` file for all the environment variables required and add it to `.env.local` file or set them up on your hosting provider.

## Join Our Community

For support, questions, or to contribute to the project, join our [Discord](https://discord.gg/thirdweb). We're excited to see what you build on RARI Chain!

-------

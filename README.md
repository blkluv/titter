## Titter - Web3 Social chat

🛠 Built with [Next.js](https://nextjs.org/), [Arweave](https://www.arweave.org/), [Bundlr](https://bundlr.network/), [Ceramic](https://ceramic.network/), GraphQL, & [Polygon](https://polygon.technology/)

![Titter](headerimage.jpg)

### How it works

This is a prototype of how you might build a web3-native social application. Features include:

- Permanent post storage (Arweave)
- User profiles (Ceramic [self.id](https://self.id/))
- Basic [GraphQL queries](https://gql-guide.vercel.app/)
- Filtering
- Fund and check balance of Bundlr
- [Pagination](https://gql-guide.vercel.app/#pagination) can also be implemented fairly easily with a few extra lines of code.

Caveats - Right now [there is an issue](https://github.com/Bundlr-Network/js-client/issues/35) with Bundlr + Arweave in that the gateway can miss Bundlr txs and think that it never hit Arweave (when it does). Hopefully this gets fixed soon.

## Deploying the app

To deploy this project, follow these steps:

1. Clone the project & change into the new directory

```sh
git clone git@github.com:dabit3/titter.git

cd titter
```

2. Install dependencies

```sh
yarn

# or

npm install
```

3. Run the app

```sh
npm run dev
```
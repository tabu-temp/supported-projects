# Supported-projects

Supported Projects for Tao-Systems Projects API

To add an Asset to Tabu Wallet follow the steps below:

1. First create a new branch with this format `Asset/*assetname*`.
2. Create a folder in the assets director with the name of the asset.
3. Create a index.ts file in that folder with the following format:

```json
{
  "type": "ERC20",
  "address": "0xc0a4df35568f116c370e6a6a6022ceb908eeddac",
  "name": "Umee",
  "symbol": "UMEE",
  "decimals": 6,
  "website": "https://umee.cc/",
  "explorer": "https://www.mintscan.io/umee",
  "shortDescription": "Simplest way to start your DeFi experience for staking, rates, and interoperable solutions across blockchains.",
  "description": "Umee is a layer one blockchain for cross chain communication and interoperability, built on the Cosmos SDK and powered by Tendermint Consensus along with a self sovereign validator network.",
  "link": "https://app.umee.cc/#/markets",
  "coinGeckoId": "umee",
  "logo": "https://assets.coingecko.com/coins/images/20635/small/1Ab_Umee_Brand_Icon_Full_Color.png?1645018295"
}
```

Type Options:

- ERC20
- COSMOS
- BEP20?
- ?

4. Fially create a Pull Request to merge your asset branch into the main branch.

Done :grinning:

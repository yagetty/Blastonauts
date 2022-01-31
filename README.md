# Welcome to BlastDAO Blastonauts!

![](https://github.com/yagetty/Blastonauts/logo-blob.png)

## Contract Info ℹ️

```json
{
  "CONTRACT_ADDRESS": "0x19815F154401A4eF49784eb3A605D64c14c8b126",
  "SCAN_LINK": "https://etherscan.io/address/0x19815f154401a4ef49784eb3a605d64c14c8b126",
  "NETWORK": {
    "NAME": "Ethereum",
    "SYMBOL": "Eth",
    "ID": 1
  },
  "NFT_NAME": "Blastonauts",
  "SYMBOL": "NAUTS",
  "MAX_SUPPLY": 2000,
  "WEI_COST": 75000000000000000,
  "DISPLAY_COST": 0.069,
  "GAS_LIMIT": 285000,
  "MARKETPLACE": "LooksRare",
  "MARKETPLACE_LINK": "https://looksrare.org/collections/0x19815F154401A4eF49784eb3A605D64c14c8b126",
  "SHOW_BACKGROUND": true
}
```

Make sure you copy the contract ABI from remix and paste it in the `public/config/abi.json` file.
(follow the youtube video if you struggle with this part).

Now you will need to create and change 2 images and a gif in the `public/config/images` folder, `bg.png`, `example.gif` and `logo.png`.

Next change the theme colors to your liking in the `public/config/theme.css` file.

```css
:root {
  --primary: #ebc908;
  --primary-text: #1a1a1a;
  --secondary: #ff1dec;
  --secondary-text: #ffffff;
  --accent: #ffffff;
  --accent-text: #000000;
}
```

Happy Minting!

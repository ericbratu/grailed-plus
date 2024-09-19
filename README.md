# Grailed Plus // Grailed+
Browser Extension for checking an item's price history on grailed.com.

## How It Works

Grailed+ monitors item listings on Grailed by accessing their publicly available metadata. The extension collects pricing data to generate the price history and predict future item listing drops. The metadata feature lets users download a file that contains all details about the listing.

## Current Features
- **Price History**: See how the price of an item has changed over time.
- **Average Price Drop**: Get the average percentage drop for each drop on the item you are currently viewing.
- **Next Expected Drop**: Predict when the next price drop may happen based on previous trends.
- **Seller Account Creation Date**: View when the seller’s account was created, giving you more context on their reputability.
- **Full Listing Meta-Data File**: Download a full metadata file of any listing.
- **And more...**


#### Feature Screenshots:
| Price History & Drop Average | Listing Meta-Data button (towards bottom of page) |
|---------------|---------------------------------------------------|
|![features-screenshot1](https://i.imgur.com/nUMCu0Q.png "Listing Price Data")| ![features-screenshot1](docs/screenshot-sidebar-lower.png "Listing JSON") <br> <br> <br> <br>  |

## Installation
#### Firefox
Stable Release Available on the [Firefox Addons Store](https://addons.mozilla.org/addon/grailed-plus/).
#### Google Chrome
Stable Release Available on the [Chrome Web Store](https://chrome.google.com/webstore/detail/grailed-plus/ipecfmmbppgpommpibaandmonmhohfnd). For Chromium see Other.
#### Other / Latest (pre)Release
It can take a bit to get latest releases approved on some webstores (looking at you Google), so the latest patches and releases can be installed manually. Download and extract the [latest release](https://github.com/RVRX/grailed-plus/releases/latest)'s `grailed_plus-X.X.X.zip`, and follow your browser's extension installation documentation from there.


## Steps to Contribute:

1. Fork the repo and clone it locally.
2. Make sure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.
3. Run `npm install` to install all dependencies.
4. Make your changes and run `npm run build` to build the extension.
5. Submit a pull request with a detailed description of the changes.


## FAQ

**Q: How accurate is the price drop prediction feature?**  
A: The price drop prediction feature is based on previous price drops for the same item, so while it is generally reliable, it may not always be correct.

**Q: How frequently is the price data updated?**  
A: Data is updated in real time as the extension scrapes the price change history on the given listing.

**Q: What permissions does the extension need and why?**  
A: Grailed+ needs permission to access Grailed's listing pages to scrape the price and metadata. It does not collect or store user information.



## License

This project is licensed under the [MIT](LICENSE) License
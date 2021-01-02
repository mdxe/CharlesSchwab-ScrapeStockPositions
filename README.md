# Get Your Stock Positions from Charles Schwab's

Get your current stock positions from Charles Schwab along with current price and your cost basis by scraping Charles Schwab's website using Selenium.  Heavily inspired from https://github.com/bakerqb/CharlesSchwab2.0.

## Installation

After cloning this repo, you may need to update the chromedriver to match your Chrome/Chromium version, go to https://chromedriver.chromium.org/downloads to download the correct version and replace the one in this repo.

## Usage

First create credentials.json and replace the dummy user and password with your information and then run the script.

```bash
cp credentials.json.example credentials.json
vim credentials.json
python3 getPositions.py
```


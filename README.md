# MintScrape
Scrape Mint Data


##Requirements

## Installation
Ensure you have Python 2 or 3 and pip (`easy_install pip`) and then:

```shell
pip install mintapi
brew cask install chromedriver # or sudo apt-get install chromium-chromedriver on Ubuntu/Debian
```

Note that chromedriver must be version 59+ if you want to use headless mode. If not installing via pip,
make sure to install the `install_requires` dependencies from setup.py yourself.

## Usage

### from the command line

From the command line, the most automated invocation will be:

    python mintapi/api.py --keyring --headless you@example.com
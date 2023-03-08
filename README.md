# CLI crypto tracker

Command line interface written in Node.js to check cryptocurrency prices

Register an API key at https://coinlayer.com

## Usage

```
npm install

npm link
```

## Commands

```
# Help & Commands
crypt -h

# Version
crypt -V

# API Key Commands
crypt key set
crypt key show
crypt key remove

# Crypto Check Commands
crypt check price

# Check Specific Coins (default: BTN,ETH,XRP)
crypt check --coin=BTC,ETH

# Choose Currency (Default: USD)
crypt check --cur=EUR
```

### Version

1.0.0

### License

MIT

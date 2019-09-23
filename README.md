# NordiEnergyWallet-CLI
**NordicEnergyWallet Command Line Interface**

[![asciicast](https://asciinema.org/a/204875.png)](https://asciinema.org/a/204875)

[![CircleCI](https://circleci.com/gh/powerchain/NordicEnergyWallet-CLI.svg?style=svg)](https://circleci.com/gh/powerchain/NordicEnergyWallet-CLI)

This wallet is based on NordicEnergyWallet library available on: https://www.npmjs.com/package/nordicenergywallet

## Installation
```
npm install -g nordicenergywallet-cli
```

## Usage
```
$ Nordic Energy Wallet help
```

### energy
Prints lifetime generation of electricity associated with this wallet.
```
$ nordic energy
0.0003506081621004566 kWh
```

### market
Prints current OTC market available to wallet
```
$ nordic energy token market
ID	nordic energy	Name
#0:	27		PV Plant Gibralta
#1:	32		WindPark Hessen-Süd
#2:	29		WindPark Maingau
```

### account
Prints all information associated to Ethereum Account
```
$ corrently account homestead:0x25FE8c5FceB9466b9D9BE4CFF37171f8D67573FA
Ethereum Address:		0x25FE8c5FceB9466b9D9BE4CFF37171f8D67573FA
Yearly Demand:			2425 kWh
Total Collected:		1963 NET Token
Converted:			1665 NET Token
Available:			298 NET Token
Valid from:			2018-10-6 14:53:18
Nominal Generation:		63 kWh/year
Confirmed Generation Equity:	200.72 kWh/year
Metered Generation:		2.5250572645230847 kWh
Metered Consumption:		1863 kWh
./. Imbalance:			-1860.4749427354768 kWh

```

### buy
Issues an OTC buy transaction.
```
$ nordicenergy token buy 1 1
```

## Contributing
- https://nordicenergy.co/capacitymarket
- https://gitter.im/net/Token

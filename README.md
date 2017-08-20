# Dapps Ideas

## Implement Twin Contracts Pattern

Given n blockchains with n >= 2, implement m >= n contracts (called twin contracts) in such a way that a transaction on one chain cannot take place without at least another mirror transaction on other chains.
This pattern will continue to be documented at [Twin Contracts Pattern](https://github.com/kuip/dlt-design-patterns#twin-contracts)

## Implement a Fiat Shadow Coin Blockchain

Given a fiat currency (like Euro), distribute a blockchain and offer exchange at the price offered by exchanges oracles for that currency. If you want to shadow Euro: you sell and buy this coin at the exact prices offered for Euro on Kraken and other exchanges.
Make sure that the implementation is at least [ERC20 compatible](https://github.com/kuip/dlt-design-patterns#contract-interoperativity). 

### Problems and Solutions

#### Fiat currencies prices are controlled by national banks

The blockchain needs a mechanism that stirs the shadow currency in much of the same fashion as a national bank: by selling or buying the coin in such a fashion that the price is kept in sync with the fiat currency. Keeping up with the market would not be hard if first a tick of one day is first resolved. If more computing power is available: before any transaction with external chains is performed: perform the price-fixing transactions. Ideally the commit of this group of transactions should take less time than a currency exchange market tick.



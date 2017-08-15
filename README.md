# Dapps Ideas

## Implement Twin Contracts Pattern

Given n blockchains with n >= 2, implement m >= n contracts (called twin contracts) in such a way that a transaction on one chain cannot take place without at least another mirror transaction on other chains.
This pattern will continue to be documented at [Twin Contracts Pattern](https://github.com/kuip/dlt-design-patterns#twin-contracts)

## Implement a Fiat Shadow Coin Blockchain

Given a fiat currency (like Euro), distribute a blockchain and offer exchange at the price offered by exchanges oracles for that currency. If you want to shadow Euro: you sell and buy this coin at the exact prices offered for Euro on Kraken and other exchanges.
Make sure that the implementation is at least [ERC20 compatible](https://github.com/kuip/dlt-design-patterns#contract-interoperativity). 


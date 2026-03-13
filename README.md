# btcdonate
**Webpage for Bitcoin donations**  

The actual website is here --> [http://cinefilmpalette.online/film/donate](http://cinefilmpalette.online/film/donate)  

The webpage calls api endpoints **/ticker** and **/q/getreceivedbyaddress** hosted on [https://blockchain.info](https://blockchain.info) for exchange rate retrieval and for detecting a change in my Bitcoin balance, respectively.  

My P2SH Bitcoin receiving address is hard coded into the webpage.  

## Features
   - The exchange rate is live and updates every 5 seconds.  
   - Typing a Bitcoin amount automatically calculates the dollar amount.  
   - Typing in a dollar amount automatically calculates the Bitcoin amount.

## New Features
   - Modular support (using BASH scripts to add, remove, and list - still a WIP) for other tokens, with ETH and XMR (additionally to BTC) as defaults.
   - Support for changing the price to other currencies via combo box (and updating flag).
  

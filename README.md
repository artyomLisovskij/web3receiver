# Proof of Concept - Web3 assets receiver
Receive assets to hot/cold-wallet(asset pool) without creating new addresses for each order using Web3

We will lookup for foreign address, i.e. <a href="https://ropsten.etherscan.io/address/0x687422eea2cb73b5d3e242ba5456b782919afc85">0x687422eEA2cB73B5d3e242bA5456b782919AFc85</a> on ropsten network.

FYI we don't own it, just want to prove that algoritm works.

# Abstract:

* You sign message with order number via web3
* We store your sign
* Now we know which address is yours(we match your address with order id)
* You pay any amount of ETH to address
* We lookup for your transfer from your address across tons of other
* You get much cheaper transfer(without accumulation and extra deposit fees). Owner of 0x687422eEA2cB73B5d3e242bA5456b782919AFc85 can use assets immediately.


PS: This algo works great with token transfers too.

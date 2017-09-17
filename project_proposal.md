# Project Proposal

### Introduction to Bitcoin

Bitcoin is an international cryptocurrency and digital payment system. It was initialized in 2009 and its value has grown exponentially over the years, with a price of over 3,000 USD per Bitcoin in 2017. It has been the most successful cryptocurrency to date in terms of market capitalization and public recognition.

It was designed around a secure protocol originally put forth under a pseudonym in [this paper](https://bitcoin.org/en/bitcoin-paper). The protocol revolves around the "blockchain", which is a datastructure that can thought of like a linked list. Each node in the list is a set of transactions, called a "block". As Bitcoin transactions occur, they are placed in a new, tentative block. The process known as "mining" is taking this tentative block and adding it officially to the blockchain. This process has been made intentionally computationally difficult, such that mining a block takes a non-negligible amount of work and time (and therefore money). This difficulty can be changed on the fly, such that as more people start mining Bitcoin, is becomes harder. In this way, the average time to mine a block has hovered around 10 minutes for most of Bitcoin's history. Therefore, mining difficulty is a good metric for measuring the populatrity of mining, which in turn indicates the value that Bitcoin has to miners. This can be used as a much less volatile metric than Bitcoin's value in USD or it's transaction volume.

We are trying to develop an algorithm to predict the future price of bitcoin.

Therefore, we will take the bitcoin historical data price dataset, the exchange distribution and ranking dataset, market captial and volume, block sizes and its difficulties of mining as factors that might have an influence on the price prediction of bitcoin. They are all important factors because they indicate the volatility of the transection market. 

While mentioning the group of people that uses bitcoin trading, the first thing popped up in your mind might be drug dealers or other political separators. Actually, there are many investors who are aiming at bitcoins due to its high potential of growth. Moreover, some major companies like Microsoft, overstock.com, start accepting bitcoins now. Therefore, our project of predicting bitcoin’s price can be valuable since bitcoin has become a more and more crucial role in the financial market. 


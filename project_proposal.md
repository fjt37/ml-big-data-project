# Project Proposal

### Introduction to Bitcoin

Bitcoin is an international cryptocurrency and digital payment system. It was initialized in 2009 and its value has grown exponentially over the years, with a price of over 3,000 USD per Bitcoin in 2017. It has been the most successful cryptocurrency to date in terms of market capitalization and public recognition.

It was designed around a secure protocol originally put forth under a pseudonym in [this paper](https://Bitcoin.org/en/bitcoin-paper). The protocol revolves around the "blockchain", which is a datastructure that can be thought of like a linked list. Each node in the list is a set of transactions, called a "block". As Bitcoin transactions occur, they are placed in a new, tentative block. The process known as "mining" is taking this tentative block and adding it officially to the blockchain. This process has been made intentionally computationally difficult, such that mining a block takes a non-negligible amount of work and time (and therefore money). This difficulty can be changed on the fly, such that as more people start mining Bitcoin, is becomes harder. In this way, the average time to mine a block has hovered around 10 minutes for most of Bitcoin's history. [This blog post](http://journalclub.deciphernow.com/main/2017/08/07/bitcoin.html) is a good introduction to how Bitcoin works if you are intersted in more technical details, or you can visit the [official site](https://bitcoin.org/en/how-it-works).

### Project Goals and Datasets
We are trying to develop an algorithm to predict the future price of Bitcoin.

We will take the Bitcoin price history, the Bitcoin exchanges and their rankings, market captialization, transaction volume, and mining difficulty as factors that might indicate the price of Bitcoin. Historical price data, as well as market capitalization, show the direct value of Bitcoin over time. Transaction volume shows the currency's popularity and usage, which in turn show commitment of resources by users to using Bitcoin. Mining difficulty is a good metric for measuring the populatrity of mining, which in turn indicates the value that Bitcoin has to miners. This can be used as a much less volatile metric than Bitcoin's value in USD or it's transaction volume. Many of these datasets can be previewed and downloaded [here](http://data.bitcoinity.org/markets/price/all/USD?c=e&t=l).

### Project Motivation

Bitcoin, largely because of it's potential for anonymity, has developed a reputation as a currency for shady dealings. In reality, there are many investors looking to Bitcoin for its high potential for growth. Moreover, some major companies like Microsoft and Overstock have started accepting Bitcoin as payment for purchases. Our project to predict Bitcoin’s price can be valuable since Bitcoin has come to have a more and more crucial role in the financial market.

On the technical side, this project will involve modeling large datasets, which fits well our current skills and the techniques that we anticipate being taught in the class. Personally, this project is also worthwhile because we will be able to learn how financial market works and how trading patterns behave, which could be beneficial if we would like to work in the financial industry in the future.

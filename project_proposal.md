# Project Proposal

### Introduction to Bitcoin

Bitcoin is an international cryptocurrency and digital payment system. It was initialized in 2009 and its value has grown exponentially over the years, with a price of over 3,000 USD per Bitcoin in 2017. It has been the most successful cryptocurrency to date in terms of market capitalization and public recognition.

It was designed around a secure protocol originally put forth under a pseudonym in [this paper](https://Bitcoin.org/en/Bitcoin-paper). The protocol revolves around the "blockchain", which is a datastructure that can thought of like a linked list. Each node in the list is a set of transactions, called a "block". As Bitcoin transactions occur, they are placed in a new, tentative block. The process known as "mining" is taking this tentative block and adding it officially to the blockchain. This process has been made intentionally computationally difficult, such that mining a block takes a non-negligible amount of work and time (and therefore money). This difficulty can be changed on the fly, such that as more people start mining Bitcoin, is becomes harder. In this way, the average time to mine a block has hovered around 10 minutes for most of Bitcoin's history. [This blog post](http://journalclub.deciphernow.com/main/2017/08/07/Bitcoin.html) is a good introduction to how Bitcoin works, if you are intersted in more technical details.

### Project Goals and Datasets
We are trying to develop an algorithm to predict the future price of Bitcoin.

We will take the Bitcoin historical price dataset, the exchange distribution and ranking dataset, market captialization, transaction volume, and mining difficulty as factors that might indicate the price of Bitcoin. Historical price data, as well as market capitalization, show the direct value of Bitcoin over time. Transaction volume shows the currency's popularity and usage, which in turn show commitment of resources by users to using Bitcoin. Mining difficulty is a good metric for measuring the populatrity of mining, which in turn indicates the value that Bitcoin has to miners. This can be used as a much less volatile metric than Bitcoin's value in USD or it's transaction volume. Many of these datasets can be previewed [here](http://data.bitcoinity.org/markets/price/all/USD?c=e&t=l)

### Project Motivation
While mentioning the group of people that use Bitcoin trading, the first thing to pop into your mind might be drug dealers or other political separators. In reality, there are many investors who are looking at Bitcoin due to its high potential for growth. Moreover, some major companies like Microsoft and overstock.com have started accepting Bitcoins now. Therefore, our project to predict Bitcoin’s price can be valuable since Bitcoin has come to have a more and more crucial role in the financial market. 

Technically, this project will involve large datasets and focus on data mining and prediction, which really fits the philosophy of the class. The techniques that will be taught later in this class will hopefully be helpful to this project as well. Personally, this project is also worthwhile because we will be able to learn how the financial market works and how trading patterns behave, which can be beneficial if we would like to work in the financial industry in the future.

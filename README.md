# Crypto-Token-Swap
Swapping of crypto tokens

In this project, we are building a trading Dapp which can be used for trading crypto currency like between HBTC and BAYC. It acts like a liquid aggregator which sources all prices across off-chain and on-chain and route the best price for the user. 

The Dapp uses 0x API swap endpoint that helps to fetch quotes across liquidity supply and uses smart order routing for the best prices across decentralized exchange networks. 

The diagram below shows an overview of the 0x Ecosystem, which includes applications who supply liquidity (Makers), applications who demand liquidity (Takers).

<img width="820" alt="image" src="https://github.com/nupur06p/Crypto-Token-Swap/assets/65718259/6d0aef08-8ed5-4e0f-9810-b68065b6431e">

Image courtsey: 0x Ecosystem


Liquidity – Users need to convert tokens to other types of tokens.
Atomicity – The exchange of tokens should be atomic based on a rate/amount agreed by both parties of the transaction.
Trust – It is hard for the parties involved in a transaction to trust each other completely.

By making the token swap atomic, we can ensure both parties will either receive the respective tokens or none of the tokens. A token swap is an agreement between two parties that exchange different token types (say token 𝐴 and token 𝐵). In a token swap, one party will pay a certain amount of token 𝐴 to the other party and receive the agreed amount of token 𝐵 in return.

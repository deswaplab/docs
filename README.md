# Overview

Deswap is a collection of tools to help you wrap your digital assets into a new NFT which can provide extra liquidity for your assets.

What's the most important thing for a digital asset? I would say liquidity, if one token lost liquidity, its value would become 0. How do people solve liquidity problem in web3 world? For ERC20 tokens, there is uniswap and its AMM model. For ERC721/ERC1155 tokens, there are a lot of NFT marketplaces like opensea and blur. Is that enough for liquidity? I would say no, a lot of meme coins have lost their value, no one would trade on uniswap, a lot of NFTs no people would buy. Deswap is the solution to these problems.

### Barter

Barter means use one thing to exchange another thing without using currency. Imagine this scene, user 1 owns some NFTs in collection A, user 2 owns some NFTs in collection B. Both of the 2 collections don't have enough liquidity, what should they do, lower the price? not a good idea. Using our Barter NFT, user1 wraps his NFT into a Barter NFT and specify that he want to receive a NFT from collection B. User1 can then sell this newly minted Barter NFT at any price, even for 0. User2 can buy this Barter NFT, then call the exercise method to transfer his NFT to user1 and user1 will receive user2's NFT.&#x20;

<figure><img src=".gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

The diagram show how user1 and user2 exchange their NFTs.

### Lottery

If you don't want to use the Barter to swap 2 NFTs, you can try our Lottery NFT. Like buying lottery in real world, you wrap your NFT or ERC20 tokens into a Lottery NFT, specify the amount and redistribute it. For example, your original NFT's floor price is 0.1 ETH, no one want to buy it, using the Lottery NFT, you can specify the amount to 100 and lower the price to 0.001,  it's 100 times price reduction, a big attraction for NFT traders.

<figure><img src=".gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

The diagram show how User 1 wraps his NFT A into Lottery A and sell on NFT markets to other people, after the draw, one lucky winner will get the NFT A.

### RedEnvelope

If your token's value totally becomes 0, you don't have any faith that it would become valuable anymore, you can give it to friends  for free. Our RedEnvelope NFT is here to help. You can wrap your ERC20/ERC1155 tokens into a RedEnvelope NFT, list it on NFT marketplaces, if you don't care about the price, just set 0, send the link to your friends, after buying, they have the right to open the RedEnvelope and receive random amount of underlying tokens.

<figure><img src=".gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

The diagram shows how User1 wraps some ERC1155 tokens into a RedEnvelope NFT, and other people buy the RedEnvelope NFT, open to get random ERC1155 NFT A. It's the same process for ERC20 tokens. Don't be afraid to give tokens to others, without liquidity your token's value would be 0, but the more people owns the token, the higher value the token would become, think of the man how buy pizza with BTC.

### Roulette

Roulette is like gamblefi, but again, we are not casino, our goal is to provide liquidity for tokens. For example, user1 minted a Roulette NFT, he can share the link to other people and place bet to win the total bets.

<figure><img src=".gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

The diagram shows how User1 betted his NFT A into a Roulette A, any other users can place bet in the collection of NFT A, after bets, User1 can open the roulette and choose a winner to take all bets. The bet currency is specified at mint time.

&#x20;

### Conclusion

These 4 products share the same idea, That is:

1. Wrap ERC20/ERC721/ERC1155 into an NFT
2. Trade that NFT
3. Take actions on that NFT

We didn't invent new protocol, we just reused the popular ERC-20, ERC-721/ERC-1155 standard.  We didn't invent new NFT marketplaces, we just reus the existed NFT marketplaces. The only new thing is the Wrap process, if one token lack of liquidity, why not try wrap it, maybe we can get more liquidity!

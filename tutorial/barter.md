# Barter

Barter is used to exchange 2 goods without using currency. Deswap Barter NFT supported asset pairs include:

ERC20-ERC20

ERC721-ERC721

ERC721-ERC1155

ERC1155-ERC721

ERC1155-ERC1155

Can be categorized in FT-FT, NFT-NFT



In this tutorial I will show you how to use Barter to swap 2 ERC721 NFTs.



### Setup

My test address1  `0x7e727520B29773e7F23a8665649197aAf064CeF1` owns some NFTs in&#x20;

{% embed url="https://testnets.opensea.io/collection/test-nft-1060?tab=items" %}

I want to use one of my `0x3377484d1920dc414dcc4eb8d6a8777e38ad968f:1` token to exchange for any token in

{% embed url="https://testnets.opensea.io/collection/test-nft2-19/overview" %}

### Mint Barter NFT

Head to: [https://deswap.one/app/barter](https://deswap.one/app/barter)

<figure><img src="../.gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

The Selected Asset Kind field I chose `NFT-NFT` means I want to exchange 2 NFTs.

In the You Pay field, I inputed `0x3377484d1920dc414dcc4eb8d6a8777e38ad968f` this is the NFT contract I want to exchange. The ID field is 1 because I want to give out the #1 ID to others.

In the You Will Get field, I set `0x8FbD64A97474bF78A8E816c57B261057E8E745b1` this is the NFT contract I want to receive token.

The Maturity Date means the due date to make the deal valid, default is 3 days later, just leave it default value.

All set, then click the mint button, this consist of 2 steps, one to approve to transfer the test NFT, one to mint the Barter NFT.

<figure><img src="../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

If every thing goes well, you shold see a successful message at the bottom of the form. Chick to see the details.

<figure><img src="../.gitbook/assets/image (46).png" alt=""><figcaption></figcaption></figure>

The detail page looks like this. This NFT means anyone owns it can use a token in `0x8fbd64a97474bf78a8e816c57b261057e8e745b1` to exchange my `0x3377484d1920dc414dcc4eb8d6a8777e38ad968f:1`

I need to go to a NFT marketplace to sell this token, so the new owner can exchange with me. The default NFT marketplace is opensea, just click the image, will redirect you to the opensea website.

### List on NFT Marketplace

List an NFT is simple, just set a fixed price, if the buyer want to pay the price, you can make the deal.

<figure><img src="../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

Now we have a listed NFT

<figure><img src="../.gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>

### Buy  This NFT

I will change to another address to demostrate other people buying this NFT. Switch account in opensea is also easy, just click metamask and choose another address.

<figure><img src="../.gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>

I'm now in a new address, so I can see the `Buy Now` button. Just click it to buy.

### Go back to deswap

Now my address: 0xd22 owns this Barter NFT, means I have the right to use any ID in `0x8fbd64a97474bf78a8e816c57b261057e8e745b1`  to exchange with 0x7e72

Head to: [https://deswap.one/app/user/tokens](https://deswap.one/app/user/tokens)

<figure><img src="../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

This token is my newly bought Barter NFT, click to go to the detail page.

<figure><img src="../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

Click the Exercise button to start the exchange.

<figure><img src="../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

A simple popup modal is shown up, the address is fixed, you just need to input the asset ID you want to exchange. If you forgot which ID you have, you can click the \`Token\` link above the address field.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

The etherscan token page shows address `0xd22` only owns id 5, so input 5 and click the exercise button.



After that, we can see `0x7e72` and `0xd22` have successfully exchanged their NFTs.

`0xd22` got `0x3377484d1920dc414dcc4eb8d6a8777e38ad968f:1`

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

`0x7e72` got `0x8fbd64a97474bf78a8e816c57b261057e8e745b1:5`

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>


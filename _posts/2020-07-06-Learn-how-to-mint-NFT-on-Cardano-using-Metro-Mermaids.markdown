---
layout: post
title:  Learn how to mint an NFT on Cardano blockchain using Metro Mermaids
description: Learn how to mint your own NFTs on Cardano blockchain
date:   2019-01-29 18:05:55 +0300
image:  '/images/posts/how-to-mint-nft-on-cardano/mint-nfts-on-cardano-blockchain.png'
tags:   [minting]
---
The process of minting NFTs on Cardano blockchain is most likely going to change dramatically in the near future after the official release of smart contracts with [Alonzo Goguen](https://roadmap.cardano.org/en/goguen/), but that could still be at least a few months away. 

In the meantime there are still going to be folks like me who want to start minting NFTs right away to be a part of history and be early adopters. This how-to article is for you! 

Now, you might be wondering how is it even possible to mint NFTs on Cardano when smart contracts aren't yet available. The short answer is developers have figured out a way to hack together methods to make it work and some of the earliest NFT projects like [Spacebudz](https://spacebudz.io) were hugely successful selling out supply in a matter of days.

A more technical explanation of how minting NFTs is possible right now can be seen straight from [Cardano's website.](https://cardano-ledger.readthedocs.io/en/latest/explanations/faq.html#cardano-native-tokens-vs-erc) 

Today I'll share one of the easiest and quickest ways to mint your own NFT in a matter of minutes using a simple tool built by [Metro Mermaids.](https://www.metromermaids.com) 

### Important Disclaimer
I can't be held responsible or liable for your use of the information contained in or linked from these web pages. Please try at your own risk. 

# Let's get started!
Find an image that you're completely fine with messing up on and uploading to a place where everyone has access to see without restrictions. Once images are uploaded to IPFS there's no turning back and they can't be deleted ever!

I'd also suggest being VERY careful what type of image you're uploading to ensure you don't break any copyright infringements.  

### Go to Pinata:
[https://pinata.cloud/](https://pinata.cloud/)  

[![](/images/posts/how-to-mint-nft-on-cardano/pinata_1_5.png)](https://pinata.cloud/)  

We're going to use Pinata to upload an image to [IPFS](https://docs.ipfs.io/concepts/what-is-ipfs/) which is ultimately the image source used in the minting process. An entirely separate article would need to be written about some of the pros and cons of using IPFS. For now let's focus on minting an NFT.

Pinata has worked out well for me so far and I'm currently using their free tier. That being said, it's also totally fine to try alternative methods to upload images to IPFS if you prefer.  

### Upload your image to IPFS

After creating an account and logging in you should see an Upload button at the top center of the page. Click on the Upload button and choose the File option.  

![](/images/posts/how-to-mint-nft-on-cardano/pinata_2.png) 

![](/images/posts/how-to-mint-nft-on-cardano/pinata_4.png)  

A popup window should appear that looks like this:  

![](/images/posts/how-to-mint-nft-on-cardano/pinata_8.png)  

Upload your image and leave empty the field to input a custom name for a pin. Also leave unchecked the "Preserve file name" option. Click on the "Upload" button. I just used the image created for this tutorial.

![](/images/posts/how-to-mint-nft-on-cardano/pinata_5.png)  

If you wait a few seconds you should now see the image link posted in your account. 

![](/images/posts/how-to-mint-nft-on-cardano/pinata_6.png)    

Now, let's switch gears.

### Step 2: Go to Metro Maids Minting Tool
Go to the following URL:
[https://www.metromermaids.com/mint-a-token/](https://www.metromermaids.com/mint-a-token/)  

You should see a page like this.  
<br/>
![](/images/posts/how-to-mint-nft-on-cardano/metro-maid-minting-tool.png)   
We're basically going to be going thru each section one at a time. 

Sections include:
- NFT Short Name or Ticker
- NFT Display Name
- How many to mint
- NFT Receive Address
- Policy options
- IPFS Qid/CID
- Metadata

### NFT Short Name or Ticker
The short name I'm using is MyFirstNFT01, but feel free to use something else. Keep in mind the name can't have any spaces or special characters.  
![](/images/posts/how-to-mint-nft-on-cardano/metro-maid_2.png)  

### NFT Display Name
This is the longer name that will be included in the minted NFT. There is a lot more flexibility in terms of names you could include, but it's probably best to keep it somewhat consistent with the NFT Short Name. 

![](/images/posts/how-to-mint-nft-on-cardano/metro-maid_3.png)  

### How many to mint
Very important to ALWAYS leave this as 1 if you truly want to create an NFT. Otherwise you'll end up creating a fungible token instead, which isn't unique.

![](/images/posts/how-to-mint-nft-on-cardano/metro-maid_4.png)  

### NFT Receive Address
This is probably one of trickiest parts if you're entirely new to Cardano and using accepted ADA wallets. 

![](/images/posts/how-to-mint-nft-on-cardano/metro-maid_6.png)  


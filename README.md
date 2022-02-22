# pinksale-snipper
An automatic bot that will get you automatically in a pinksale ICO launch

 To use this bot you will have first to create a config file. This file will contain the data of your wallet, as well as the gas and gwei you chose to use for the transaction.
The private key of the wallet will be stored in the config file encrypted, also, the encryption will require a password and a 2FA Google Authenticator code to get access to the data. Therefore, your private key will be safe even if someone else gets access to your config file. With this type of security you will be safer than most of the wallets provider at this moment.

  Regarding the gas and gwei you should use, I suggest that you enter 1000000(1M) or even 1500000(1.5M) gas, as the nodes that will validate the transaction will take only what they need. For gwei Pancakeswap recommends these values: 5 for a slow transaction( almost 90% of every transactions on the Binance Smart Chain will use 5 gwei); 6 for a medium speed transaction and 7 for a fast transaction.
  
  As soon as you have created the config file you will be able to use the snipper.
  
  This version of the snipper will take a fee of 5% of each transaction, considering all the projects out there on the BSC 5% is quite a rather small fee to be sure you get into an hyped launch, also, this fee will allow us to further develop this product. The fee will be taken only for a successful contribution. Note, that in projects with a small hardcap( ~50bnb) and a hyped community there might be a chance that you won't get in, as many will use bots as well. 
  
  For BSC mainnet we use our own node, this node is located in Europe on a high end spec server with a 10 Gb connection to the Internet, this will help the bot to perform a fast transaction even when the BSC network gets very busy. 

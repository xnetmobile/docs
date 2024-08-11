## XNET Solana Migration - Phase One

Welcome to our XNET Token Bridge Guide! In this document, we'll walk you through the detailed steps for migrating your XNET tokens across different networks, ensuring a smooth transition from Polygon or Ethereum to Solana. Please follow each step carefully and refer to the provided resources to make this process as seamless as possible. LFG!

For the purposes of this document, when we refer to the original Polygon XNET we will refer to it as `(P)XNET`, for ETH wrapped XNET we will use `(EW)XNET`, for Wormhole(Portal Bridge) wrapped XNET will use `(W)XNET`, and for the final migrated token on Solana we will refer to it as just (`XNET`).

The process flow for migrating tokens goes as follows:

`(P)XNET` -> `(W)XNET` -> `XNET`

`(EW)XNET` -> `(W)XNET` -> `XNET`

Notes and Important Considerations:


!!! tip 
    * You must use a desktop browser for this process.
    * You must use a browser that does not have any other wallet installed/enabled except MetaMask and Phantom wallets.
    * You may have to disable Phantom wallet extension to connect Metamask to the first part of the bridge then re-enable it when connecting Solana wallet with phantom
    * You will need about $5 USD equivalent of MATIC and $5 USD equivalent of SOL to complete this bridge.


!!! note 
    This process is tested to work. Be very sure you follow this process exactly.

If you do not follow these bridge instructions, you’re on your own. We can not, unfortunately, support every combination of app, wallet, chain, etc. Please watch this video and follow along while reading the instructions: XNET Token Bridge How-to


## Bridging `$(P)XNET` from Polygon to Solana Using Wormhole

!!! note
    This documentation assumes you use MetaMask or another Polygon/ERC20 wallet and are bridging XNET tokens to Phantom wallet.

## Step-by-Step Instructions

### Step 1: Install Phantom Wallet
1. Download and install the Phantom Wallet extension to your web browser from the official website.

2. If you have never created a Solana wallet before, follow the instructions from the official Phantom wallet guide to create a new Solana wallet.

### Step 2: Add some SOL to Your Wallet
1. Ensure you have some Solana (SOL) in your new wallet before continuing.

2. Recommended methods for acquiring SOL:
 --- Coinbase
 --- KuCoin

3. You'll need around $5 USD equivalent to SOL to complete the bridge in most cases. 

### Step 3: Access Wormhole Bridge Advanced Transfer Tool
1. Visit Portal Bridge Advanced Tools using your browser or Phantom’s in wallet’s web3 browser. (You must use the Advance Wormhole bridge to complete the migration)

2. Select either Polygon as “Source” -> and Solana as “Target” or Ethereum as “Source  -> and Solana as “Target”, Depending on which chain you currently on XNET tokens on and want to bridge from

3. Now click "*Connect Wallet*," choose Metamask, and confirm. (You may have to disable Phantom wallet extension to connect Metamask to the this part of the bridge then re-enable it when connecting Solana wallet part of the bridge, This happen when Phantom wallet try to take priority over metamask as to which wallet to connect first)


    <a href="/migration/page_3_img_2.png" data-fancybox="gallery">
      <img src="/migration/page_3_img_2.png" alt="Relevant Image" width="500px">
    </a>

### Step 4: Select Correct Token
1. Under "Select a Token," paste the following based on which XNET token chain you are migrating from.

    For Polygon use `$(P)XNET` contract address: `0xbc5eb84c052fd012bb902c258c9fd241b17c0005`

    For Ethereum use `$(EW)XNET` contract address: `0x5393cEeD9a265Bda7952780E5b9413150e666a24`

    <a href="/migration/page_3_img_3.jpeg" data-fancybox="gallery">
    <img src="/migration/page_3_img_3.jpeg" alt="Relevant Image" width="500px">
    </a>

2. The token may appear as “XNET” or “Unknown” Choose the amount (or max) that you want to bridge and click "Next."


    <a href="/migration/page_3_img_4.png" data-fancybox="gallery">
      <img src="/migration/page_3_img_4.png" alt="Relevant Image" width="500px">
    </a>



### Step 5: Connect Your Solana Wallet
1. Click "Connect" and choose Phantom from the dropdown list.

    <a href="/migration/page_4_img_2.jpeg" data-fancybox="gallery">
    <img src="/migration/page_4_img_2.jpeg" alt="Relevant Image" width="500px">
    </a>


    <a href="/migration/page_4_img_3.jpeg" data-fancybox="gallery">
    <img src="/migration/page_4_img_3.jpeg" alt="Relevant Image" width="500px">
    </a>

2. You will then likely need to “create associated token account”, this will prompt you through a series of confirmations from the phantom wallet.


    <a href="/migration/page_4_img_4.jpeg" data-fancybox="gallery">
    <img src="/migration/page_4_img_4.jpeg" alt="Relevant Image" width="500px">
    </a>

    <a href="/migration/page_5_img_2.png" data-fancybox="gallery">
    <img src="/migration/page_5_img_2.png" alt="Relevant Image" width="500px">
    </a>

3. Once the created associated token account is created select “next”.

4. Next confirm the token amount you want to move by selecting “Approve”, A Metamask popup will generate a popup for you to approve the amount to be transferred via you wallet and the token bridge contract. Confirm and approve the transaction then hit next in the popup window.


    <a href="/migration/page_5_img_4.jpeg" data-fancybox="gallery">
      <img src="/migration/page_5_img_4.jpeg" alt="Relevant Image" width="500px">
    </a>


### Step 6: Send Tokens

1. Click "Transfer" and confirm the transactions after verifying the amounts.

    <a href="/migration/page_6_img_2.png" data-fancybox="gallery">
    <img src="/migration/page_6_img_2.png" alt="Relevant Image" width="500px">
    </a>

2. Next you will “confirm” that the tokens are moving from the Source chain to the Target chain in the correct order. A new Metamask transaction confirmation popup will show on your confirmation the transaction and the migration transfer will begin. 

!!! note
    This process can take up to 30 minutes during times of high congestion, but typically only takes 2-3 minutes.

  <a href="/migration/page_7_img_2.png" data-fancybox="gallery">
    <img src="/migration/page_7_img_2.png" alt="Relevant Image" width="500px">
  </a>

  <a href="/migration/page_7_img_3.jpeg" data-fancybox="gallery">
    <img src="/migration/page_7_img_3.jpeg" alt="Relevant Image" width="500px">
  </a>

  <a href="/migration/page_7_img_4.png" data-fancybox="gallery">
    <img src="/migration/page_7_img_4.png" alt="Relevant Image" width="500px">
  </a>


### Step 7: Redeem Tokens

1. Click the "Redeem" option to finalize the transfer. You will see 4-5 confirmations from the Solana wallet to complete the transfer.

    <a href="/migration/page_7_img_5.png" data-fancybox="gallery">
      <img src="/migration/page_7_img_5.png" alt="Relevant Image" width="500px">
    </a>


    <a href="/migration/page_8_img_2.png" data-fancybox="gallery">
      <img src="/migration/page_8_img_2.png" alt="Relevant Image" width="500px">
    </a>


### Step 8: Bridge Complete!

1. Congratulations, you have successfully bridged  `$(P)XNET` from Polygon to Solana `$(W)XNET` using Wormhole Bridge! You should see this XNET token in your wallet now.


    <a href="/migration/page_8_img_3.jpeg" data-fancybox="gallery">
      <img src="/migration/page_8_img_3.jpeg" alt="Relevant Image" width="500px">
    </a>

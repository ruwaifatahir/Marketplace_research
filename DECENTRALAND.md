<!-- Headings -->

# Decentraland Research Document

<br>

## **Team** :

<br>

| _Name :_                |        _Email :_         | _Role :_ |
| :---------------------- | :----------------------: | -------: |
| _Ruwaifa Tahir_         | *ruwaifatahir@gmail.com* | Researcher |


---

<br>

## **_Introduction_** :

The Marketplace is the go-to place to trade and manage all your Decentraland on-chain assets.
<br>
<br>
![image](https://user-images.githubusercontent.com/66880814/175871595-bcbcc10a-dea2-4f8c-9a25-5faa37888fac.png)


### The Marketplace allows you to:

- **Sell** parcels and Estates of LAND, wearables, and unique names. Set your own price in MANA and an expiration date for the offer.

- **Buy** parcels and Estates, wearables, and unique names that are for sale.

- **Transfer** your Decentraland assets to another user.

- **Explore** the world through a map to see who owns what, existing wearables
  or claimed avatar names.

- If item isn't listed, you can place a **bid** on it.

- You can **change** the price of a sale that you already put on offer without having to **cancel** and **re-create** the sale

- The Marketplace app is backed by a smart contract that provides a trustless and transparent exchange for buying and selling LAND. The Marketplace is completely open source, and you can view the contract code in our [GitHub](https://github.com/decentraland/marketplace-contracts) Repo.

- Marketplace is designed the Marketplace to facilitate atomic swaps.

  <br>

## _Research Parameters_:

<br>

| Parameters :                        | Details :                                                                                                                                               |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Supported Blockchains :**         | _Polygon, Ethereum_                                                                                                                                     |
| **Payment Methods :**               | _Polygon MANA, Ethereum Mana_                                                                                                                           |
| **Buyer Fee :**                     | _0%_                                                                                                                                                    |
| **Seller Fee :**                    | _2.5%_                                                                                                                                                  |
| **Royalties :**                     | _Yes_                                                                                                                                                   |
| **Listing Type/ Selling Methods :** | Direct Sale                                                                                                                                             |
| **Categories :**                    | _land, wearables, emotes, Names_                                                                                                                        |
| **Recommended Wallets :**           | _Metamask, Formatic, WalletConnect, Ledger_                                                                                                             |
| **File Format :**                   | _gITF, .gltf or .glb_ |
| **Max File Size :**                 | _15 MB_                                                  |
| **Media Storage :**                 | _BitTorrent and Kademlia DHT networks_                                                                                                                  |
| **Decentralization :**              | _Yes_                                                                                                                                                   |
| **Ownership :**                     | _Non custodial_                                                                                                                                         |
| **Licensing :**                     | _No its all for use inside Decentraland_                                                                                                                                           |
| **Governance :**                    | _Yes_                                                                                                                                                   |
| **Staking :**                       | _No_                                                                                                                                                    |
| **KYC :**                           | _No_                                                                                                                                                    |
| **Community Engagement :**          | _Good_                                                                                                                                                  |

---

<br>



<br>

---

<br>

## _Description for Parameters_ :

<br>


- **_Seller Fee :_**

  - Commission fees on Decentraland Marketplace:
    - The commission fee on this platform is 2.5%.
    - It is comparatively less than the fees on most marketplaces.
    - When a wearable creator made a sale in the primary market, they received the listing price minus a commission of 2.5%, which went to the Decentraland DAO.
    - However, when the sale occurred in the secondary market, the owner of the item (not necessarily the original creator!) received the sale price minus the 2.5% commission, which still went to the DAO.
  - **Listing Fee :**
    - There is also listing fee feature in contract which can be set by owner
  - **Publication fees :**

    - There is a required fee for publishing items. This fee was voted in place by the Decentraland DAO This fee exists to deter users from publishing an excessive number of wearables in an attempt to “spam” the wearables market.

    - The fee is a flat rate of $500 value (paid in MANA) per item (not NFT!) in your collection.

    - Previously it was 500 MANA, with MANA’s value increase, it was lowered to equal $500 in a recent DAO vote.

  <br>

- **_Royalties :_**

  - With the implementation of Royalties in the Decentraland marketplace, only primary market commissions are destined to the DAO, while those in the secondary market now go straight to the creative hands behind the wearables.<br>

  - Creators of new and existing collections on Polygon will be able to set a beneficiary address per item in the collection management tool, be it themselves or a third party.
  - If a wearable is sold multiple times, it is now up to the creator to decide who benefits from all those sales!
  - 

- **_Categories :_**

  - Land:

    - LAND within Decentraland is represented by non-fungible LAND tokens (meaning that each is unique and cannot be replicated) that track ownership on the Ethereum blockchain.
      Owning LAND within Decentraland is akin to owning any other unique, crypto asset like [CryptoKitties](https://www.cryptokitties.co/) or [CryptoPunks](https://www.larvalabs.com/cryptopunks), however you will be able to use your LAND within Decentraland to build three dimensional spaces and applications.
      LAND is built on our [ERC721](https://ethereum.org/en/developers/docs/standards/tokens/erc-721/) standard, making it a digital asset that can be traded with other users, like other digital assets.
      
      <br>
  ![image](https://user-images.githubusercontent.com/66880814/175872340-5e0416a9-33c0-4095-b5d9-399645c8c774.png)


    <br>

  - Names :

    - Decentraland Names are tradable ERC721s, integrated fully with the Ethereum Name System.
    - These unique human-readable names allow users to trade tokens between memorable addresses, e.g. ‘jane.dcl.eth’.

      <br>
      
      ![image](https://user-images.githubusercontent.com/66880814/175871797-ef621936-538c-4aca-9b78-0e84e67942c4.png)


      <br>

  - Wearables :

    - Wearables are the various items of clothing, accessories, and body features that can be used to customize the appearance of a Decentraland avatar.
    - There is a selection of default wearables that are freely available to all avatars, but Decentraland also supports the creation and use of custom wearables that are represented by non-fungible tokens (or NFTs).
    - This allows a finite amount of different wearables to be created, or minted, on the blockchain, similar to the LAND.
      -By default, Decentraland Wearables are minted on the Polygon/Matic sidechain so users can mint, buy, sell, or transfer items without having to pay gas fees.
      
      <br>
      <br>

  - Emotes:

    - Decentraland has introduced a set of programmable moves to add a little flair to proceedings.
    - Each emote represents an entirely ownable and tradable demonstration of self-expression, all controlled via the emote UI.
    - To use one of the pre-programmed emotes, open up the console by clicking ‘B,’ then hit the number associated with it.

    <br>

- **_File Format :_**

  - All 3D models in Decentraland must be in glTF format. glTF (GL Transmission Format) is an open project by Khronos providing a common, extensible format for 3D assets that is both efficient and highly interoperable with modern web technologies.
  - glTF models can have either a .gltf or a .glb extension. glTF files are human-readable, you can open one in a text editor and read it like a JSON file.
  - This is useful, for example, to verify that animations are properly attached and to check for their names. glb files are binary, so they’re not readable but they are considerably smaller in size, which is good for the scene’s performance.

  <br>

- **_Max File Size :_**

  - Decentraland allows its users to upload 15 MB files per parcel in size, including 3D models and audio tracks.
  - But the size of the file, like node.js packages that won’t be uploaded on the platform, isn’t counted in the total size of the uploaded files.

  - 200 files per parcel Total count of the files uploaded. Includes 3D models and audio. Doesn’t include files that aren’t uploaded, such as node.js packages.

    <br>

- **_Media Storage :_**

  - Decentraland uses a decentralized storage system to distribute the content needed to
    render the world.

  - For each parcel that needs to be rendered, a reference to a file with
    the description of the parcel’s content is retrieved from the smart contract.

  - The current
    solution uses the battle-tested BitTorrent and Kademlia DHT networks by storing a
    magnet link for each parcel.
  - However, the Inter-Planetary File System (IPFS)11 provides
    a compelling alternative as its technology matures.

  - This decentralized distribution system allows Decentraland to work without the need
    of any centralized server infrastructure.
  - This allows the world to exist as long as it has
    users distributing content, shifting the cost of running the system to the same actors
    that benefit from it.
  - It also provides Decentraland with strong censorship-resistance,
    eliminating the power of a central authority to change the rules or prevent users from
    participating.
  - However, hosting these files and the bandwidth required to serve this content has
    significant costs.

  - Currently, users of the Decentraland P2P network are seeding the
    content without compensation and out of goodwill. However, in the future, this
    infrastructure cost can be covered by the use of protocols like Filecoin12.
  - Until this
    technology becomes available, automated micropayments can be used to pay for
    quality of service.
  - The proceeds of Decentraland’s continuous sale of MANA can cover
    these costs over the long run<br>

- **_Decentralization :_**

  - The Marketplace is a fully decentralized application built using Ethereum smart contracts, giving you us completely trustless exchange for LAND.

  - Most importantly, they have removed any counterparty risk by designing the Marketplace to facilitate atomic swaps — transactions that are only finalized if both parties fulfil their obligation before a timer expires. All of the code for the Marketplace is open source, transparent, and continually updated.

- **_Ownership :_**

  - Decentraland is the first fully decentralized virtual world. It was always part of the original vision to hand over control to the people who create and play in this virtual space. In short – you, the users.
  - Through the DAO, we are in control of the policies created to determine how the world behaves: for example, what kinds of wearable items are allowed (or disallowed) after the launch of the DAO, moderation of content, LAND policy and auctions, among others.
  - Further, the founding team claims the private key that controlled Decentraland’s smart contract has been destroyed.

    <br>

- **_Governance :_**

  - To circumvent the very high gas fees associated with full on-chain governance, Decentraland’s DAO uses a combination of free, off-chain voting for the community and a multi-sig wallet controlled by a “DAO Committee” to enact those off-chain decisions on the Ethereum blockchain.
  - This allows everyone who holds MANA, NAMES or LAND to participate in the DAO without having to pay any fees everytime they want to vote or open a proposal.

  - The use of a multi-sig wallet controlled by a committee of trusted persons guarantees the security of the DAO along with guaranteeing that passed proposals result in an on-chain action.
  - A second multisig owned by the SAB provides a second layer of protection on top of the DAO Committee.

  - The main interface for the Decentraland DAO is located at [governance.decentraland.org](https://governance.decentraland.org/). This is where users log-in, create proposals, and vote.

  <br>


---

<br>

## _Contracts Description_ :

<br>

[**_Decentraland Marketplace Contracts_**](https://github.com/decentraland/marketplace-contracts)

<br>

<br>

- **_Buying Process :_**

  - Checks if nftAdress is contract or EOA and if nftAddress have correct ERC721 implementation.
  - Calculate commision which can be updated by marketplace owner
  - Transfers commision to marketplace owner, and remaining to seller.
  - Tranfers NFT from seller to buyer
  - Delete the item data from contract

<br>

```java
  function executeOrder(
    address nftAddress,
    uint256 assetId,
    uint256 price
  )
   public
   whenNotPaused
  {
    _executeOrder(
      nftAddress,
      assetId,
      price,
      ""
    );
  }
```

<br>

- **_Order Booking :_**

  - Creates a new order
  - Generates a orderId to keep track of item listings
  - It also have **listing** fee which can beturned ON/OFF by **owner**.
  - It does not transfer NFT from sender instead it checks if sender have already apporved the contract

<br>

```java
 function createOrder(
    address nftAddress,
    uint256 assetId,
    uint256 priceInWei,
    uint256 expiresAt
  )
    public
    whenNotPaused
  {
    _createOrder(
      nftAddress,
      assetId,
      priceInWei,
      expiresAt
    );
  }
```

<br>

- **_Funds Distribution :_**

  - Calculate commision which can be updated by marketplace owner

  -

<br>

```java
if (ownerCutPerMillion > 0) {
  // Calculate sale share
  saleShareAmount = price.mul(ownerCutPerMillion).div(1000000);

  // Transfer share amount for marketplace Owner
  require(acceptedToken.transferFrom(
    sender,
    owner(),
    saleShareAmount
  ), "Transfering the cut to the Marketplace owner failed");
}
```

---

<br>

<br>

---


<br>

## _Sources :_

- [Decentraland Names](https://opensea.io/collection/dcl-names)
- [Selling Methods](https://danky.art/blog/decentraland-wearables#:~:text=To%20sell%20wearables%20on%20the,items%20we%20want%20to%20sell.)
- [Max file size and format0](https://nonfungibletalk.com/guides/nft-files-what-size-and-format-should-you-use/)
- [Max file size and format1](https://docs.decentraland.org/builder/scene-limitations/#:~:text=File%20size%3A%2015%20MB%20per,t%20uploaded%2C%20such%20as%20node.)
- [White Paper](https://decentraland.org/whitepaper.pdf)
- [Decentralization](https://decentraland.org/blog/announcements/introducing-the-decentraland-marketplace-for-mobile/)

<br>




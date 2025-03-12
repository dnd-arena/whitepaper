# DND Arena Whitepaper

## 1. Introduction
DND Arena is a blockchain-based gaming ecosystem that merges the thrill of arena battles with the strategic depth of Dungeons and Dragons (DND) rules and mechanics. Players can own unique in-game assets, participate in battles based on character stats, and engage with a constantly evolving platform governed by its community. In addition to gameplay, a dedicated item shop website is planned as a "Coming Soon" feature, where players will be able to purchase exclusive NFT-based gear and items.

## 2. Vision and Mission
### Vision
To create a decentralized and engaging platform where players can own, trade, and compete with unique assets in a fair and community-driven environment.

### Mission
To revolutionize gaming by integrating blockchain technology, enabling players to turn their gaming skills and assets into tangible rewards while fostering a sustainable and community-centric economy.

## 3. Core Features
### 3.1 Core Functionality
#### Character Creation
- Each user is granted one free character generation upon registration.
- Additional character generations will cost **30,000 $DND** per character.

#### Arenas and Battle Mechanics
- Players will engage in battles where outcomes are determined by character stats and, in future versions, item stats and skills.
- Dice-roll mechanics influence combat outcomes, creating opportunities for strategy and unpredictability.

### 3.2 NFT-Based Items
- Every item in DND Arena, including weapons, armor, and accessories, is represented as an NFT.
- Exclusive daily random drops feature ~10 items with superior stats, enhancing user engagement and providing competitive advantages.

### 3.3 Daily Random Drops
- At random times each day, ~10 exclusive items will drop into the shop.
- These items have enhanced stats compared to regular shop offerings.

### 3.4 Decentralized Governance
- DND Arena operates on a community-driven governance model, where **$DND token holders** vote on major decisions and ecosystem developments.
- Proposals can include updates to game mechanics, new features, or changes to tokenomics.

## 4. Tokenomics
### 4.1 $DND Token
#### Total Supply: **1,000,000,000 $DND**
#### Allocation:
- **50%**: Public Sale – Tokens available for general purchase by the public.
- **5%**: Lock with virtual lockers.
- **5%**: Arena activity.
- **1%**: 
  - 0.5% from withdrawal fee collecting to provide stacking incentives.
  - 0.5% marketing & development.
- **30k $DND** from new character generation: marketing & development.

## 5. Game Mechanics
### 5.1 Arenas and Battle Mechanics
- Players compete in battles where character stats determine outcomes.
- Future versions will incorporate item stats and skills into battle calculations.
- Dice-roll mechanics influence combat outcomes, adding a layer of unpredictability and strategy.

### 5.2 Customization and Strategy
- Players can customize their loadout with unique NFT-based gear.
- Character stats and strategic planning play a critical role in achieving victory.

## 6. Marketplace and Economy
### 6.1 NFT Marketplace
- A dedicated marketplace enables players to buy, sell, and trade NFTs.
- A portion of every transaction is funneled back into the ecosystem for rewards and development.

### 6.2 Auction System
- A "Coming Soon" feature, auctions will allow players to bid on rare and exclusive NFTs.
- This will add another layer of excitement and strategy to the economy.

## 7. Wallet Integration
- Players can connect their existing crypto wallets (e.g., **MetaMask**) to manage their $DND balance and NFTs.
- Wallet integration ensures secure transactions and easy onboarding.

## 8. Profile and Community Engagement
### 8.1 Profile Page
- **Arena History**: Track matches and performance over time.
- **Statistics**: View detailed metrics such as win rate, highest damage, and ranking.
- **DND Balance**: Display current holdings and transaction history.

### 8.2 Community Features
- **Leaderboards**: Showcase top-performing players globally and regionally.
- **Events**: Regular tournaments and challenges to keep the community engaged.

## 9. Roadmap
### Phase 1: Launch (Months 0-3)
- Release the **$DND Arena Bot V1** (character creation/recreation, battle, withdrawals).
- Release the **landing page, shop, and wallet integration**.
- Launch initial **NFT marketplace**.
- Begin **daily random drops** and feature them on the landing page.

### Phase 2: Growth (Months 3-6)
- Introduce a **governance system** for $DND holders.
- Expand **arena types** and gameplay features.
- Begin development of **auction functionality**.

### Phase 3: Expansion (Months 6-12)
- Launch **auction system**.
- Establish **staking and earning** opportunities for $DND holders.
- Host the **first global tournament** with significant prizes.

### Phase 4: Sustainability (Year 2 and Beyond)
- Enhance gameplay with **new arenas and mechanics**.
- Foster **partnerships** with other blockchain projects.
- Continuously refine and expand the ecosystem based on **community feedback**.

## 10. Contracts
### Base Chain
#### **DNDArena**: `0xd6655e23012FB336387D16b089B3aAd0988e3080`
This contract manages the creation and acceptance of arenas and determines the winner. It ensures a unified and publicly accessible state and interface, promoting trust and transparency in arena token flow.

#### **CharacterGenerationManager**: `0x4E24D0a7f1457eAEfAD308100649A4dD179642e4`
This contract handles requests to generate new characters, making the character generation token flow publicly accessible and verifiable. Upon payment for character generation, the contract emits an event, which our server processes to initiate the generation process.

### GitHub Contracts: [DNDArena Contracts](https://github.com/dnd-arena/contracts)

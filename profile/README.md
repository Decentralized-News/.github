# decentNews: A Decentralized News Platform 📰🚨

## Introduction

decentNews is a cutting-edge decentralized news platform created at ETHMunich Hackathon. It empowers anyone to publish articles, which will then be reviewed by peers. Upon receiving enough validation, the articles will be published on the website. Both authors and reviewers can earn rewards for accurate content and reviews, or face penalties for malicious actions. This process establishes a truly independent news platform, allowing for transparent, community-driven journalism that operates free from centralized control or bias.

## How It Works

### 1. **Publishing an Article**
   - **Staking Ether**: To participate, users must stake Ether as a commitment against malicious activities. (Deactivated in the MVP, however included in the Smart Contract)
   - **Submitting Articles**: Anyone can write and submit an article for review.

### 2. **Peer Review Process**
   - **Random Assignment**: Articles are assigned to random reviewers through a true random process using Chainlink.
   - **Review and Validation**: Peer reviewers evaluate the article for accuracy and quality.
   - **Threshold Validation**: If the article receives enough validations, it gets published.

### 3. **Reward and Punishment Mechanism** 
   - **Rewards**: Authors and reviewers receive rewards for accurate articles or reviews. 
   - **Punishments**: Malicious actions lead to penalties, including the loss of staked Ether.

### 4. **Decentralized Storage**
   - **Hash Storage**: Article hashes are stored on a smart contract, guaranteeing integrity.
   - **Database Storage**: The actual article content is stored in a separate database, maintaining decentralization.

## Technologies Used

- **Solidity**: For creating smart contracts and managing staking.
- **Chainlink**: For true randomness in the review assignment process.
- **React + Vite **: For a user intuitive interface.
- **Node.js + MongoDB**: For storage of article content.

## Conclusion

decentNews represents a bold step towards a more transparent, decentralized, and democratic news publishing system. By harnessing the power of blockchain and innovative technologies, it opens up a new avenue for unbiased and community-driven journalism.

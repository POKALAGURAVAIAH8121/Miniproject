## Title of the Project

Decentralized peer to peer Ride sharing System using Block Chain

## About
<!--Detailed Description about the project-->
Most current ride-sharing apps, including well-known ones such as Uber and Lyft, operate on centralized platforms where a central agency has access to all the user, ride, and payment information. The utilization of a central system has several disadvantages such as exorbitant fees, low transparency, compromised data privacy, and probable system crashes. As a response to such limitations, the present project offers an approach to a decentralized ride-sharing system built by using blockchain technology. It avoids middlemen in the form of direct "peer-to-peer (P2P) interactions" among drivers and passengers, promoting trust and fairness. It relies on a "private blockchain" that implements the "Proof of Authority (PoA)" consensus algorithm, which promises secure and efficient transaction verification with low computational overhead. The system facilitates login-free ride booking, “decentralized identity verification, and an escrow-based payment system with an integrated tamper-proof reputation system to guarantee reliability. By merging the immutability and transparency of blockchain with optimized P2P networking, the system ensures data integrity, fairness, and cost-effectiveness. In addition, it supports user autonomy through transparent and verifiable ride agreements, minimizing fraud and manipulation. “Decentralized in nature”, this solution provides a solid foundation for a scalable, secure, and community-driven ride-sharing ecosystem that can evolve with future innovations in mobility.

## Features
<!--List the features of the project as shown below-->
Decentralized Peer-to-Peer Ride Sharing

Private Blockchain Network

Proof of Authority (PoA) Consensus


Smart Contract–Based Ride Agreements

Escrow-Protected Payments

On-Chain Reputation System

High Transparency and Security

User Data Privacy

Low Transaction Costs
## Requirements
<!--List the requirements of the project as shown below-->
- Use a private, permissioned blockchain with Proof-of-Authority (PoA) validators to record and validate all ride-related transactions. 

- Support login-free ride booking by issuing cryptographic identities (public/private keys) to riders and drivers on first use.

- Implement an escrow-based payment smart contract that locks fare funds at request time and releases them only after on-chain ride completion.

- Model each trip as a multi-transaction state machine (ESCROW_PENDING → RIDE_ACCEPTED_IN_PROGRESS → ESCROW_RELEASED_COMPLETED) so every state change is an immutable chained transaction.

- Maintain a tamper-proof, auditable reputation system where final ride ratings (included in the completion transaction) update an off-chain, verifiable reputation ledger derived from on-chain events.

- Use SHA-256 hashing for block integrity, cryptographic signatures for action authenticity, and end-to-end encrypted P2P messaging between matched driver and rider.

- Combine on-chain immutability with off-chain storage for high-performance lookups and scalability, and expose APIs/endpoints for ride creation, acceptance, completion, mining, and reputation queries.

## System Architecture
<!--Embed the system architecture diagram as shown below-->

<img width="1043" height="651" alt="image" src="https://github.com/user-attachments/assets/9929af6b-fa0b-4c2f-942d-3f5557ba2208" />


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 

<img width="621" height="458" alt="image" src="https://github.com/user-attachments/assets/cc2559ab-4832-4a58-bd35-88494cab350c" />


#### Output2 

<img width="641" height="575" alt="image" src="https://github.com/user-attachments/assets/8ec046b1-7ea1-4821-9275-a9f82e1dd605" />

#### Output3

<img width="628" height="575" alt="image" src="https://github.com/user-attachments/assets/45f6c869-a03d-41de-86d2-084c4537880d" />


Detection Accuracy: 96.7%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
<!--Give the results and impact as shown below-->
The system ensures secure and transparent ride transactions using blockchain technology.
Proof of Authority consensus enables fast validation with minimal operational costs.
Peer-to-peer ride matching removes intermediaries, fostering direct driver–rider trust.
Private blockchain integration ensures data privacy and system reliability.
Overall, it delivers a scalable, efficient, and trustworthy solution for digital ride-sharing.


The system significantly enhances ride-sharing by increasing transparency, trust, and privacy while reducing costs through a decentralized, middleman-free model.


## Articles published / References
Klimis S. Ntalianis, Nikos E. Mastorakis, “Quality of Experience Oriented Eco-Friendly Taxi-Ride Sharing Recommendation Framework,” IEEE Access, Volume: 12, October 2024. DOI: 10.1109/ACCESS.2024.3485221.
Yafei Li, Huiling Li, “Utility-Aware Dynamic Ridesharing in Spatial Crowdsourcing,” IEEE Transactions on Mobile Computing, Volume: 23, Issue: 2, February 2024. DOI: 10.1109/TMC.2022.3232215





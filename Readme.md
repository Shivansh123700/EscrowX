# EscrowX - Blockchain Escrow Service

## About EscrowX

EscrowX is a decentralized escrow service built on the blockchain. It provides a secure and transparent way for two parties (sender and receiver) to complete transactions. With the help of smart contracts, EscrowX ensures that funds are held securely until predefined conditions are met, protecting both parties from fraud and disputes.

## Contract Details

- **Contract Address**: `0x83e07df615efe89101081Db9337e5b765c9b6b53`
- **Network**: Mantle Sepolia Testnet

## Features

- **Set Participants**: Allows the sender and receiver to be set before the deposit is made.
- **Deposit Funds**: The sender deposits the agreed amount of funds to the contract.
- **Release Funds**: The receiver can release the funds once they fulfill the terms.
- **Refund Funds**: If the conditions are not met, the sender can refund the funds.
- **Reset**: Resets the contract for new participants after funds are released or refunded.

## Deployment

- **Contract Address**: [View on Explorer](https://sepolia.mantlescan.xyz/address/0x83e07df615efe89101081db9337e5b765c9b6b53)
- **Coin Used**: MNT (Mantle Sepolia Testnet)

## How It Works

1. **Set Participants**: The sender and receiver's Ethereum addresses are set using the `setParticipants` function.
2. **Deposit**: The sender deposits an agreed amount of Ether to the contract using the `deposit` function.
3. **Release/Refund**: Based on the agreement, the receiver can release the funds, or the sender can request a refund if the conditions are not met.
4. **Reset**: After the transaction has been completed (released or refunded), the contract can be reset for new participants.

## ScreenShots
<img width="1437" alt="Screenshot 2024-12-14 at 4 08 39 PM" src="https://github.com/user-attachments/assets/0cb448e8-ff94-432e-bfdf-248f47105146" />
<img width="1440" alt="Screenshot 2024-12-14 at 4 08 55 PM" src="https://github.com/user-attachments/assets/21cac719-4f23-4f52-adf9-941d808b3353" />
<img width="1440" alt="Screenshot 2024-12-14 at 4 09 10 PM" src="https://github.com/user-attachments/assets/3cb9aa5e-1f97-478d-ad20-cbb986083d1c" />
<img width="1440" alt="Screenshot 2024-12-14 at 4 05 51 PM" src="https://github.com/user-attachments/assets/0fa8dfc4-6fa3-436b-ad6f-3f11f6ef2b9b" />
<img width="1439" alt="Screenshot 2024-12-14 at 4 06 03 PM" src="https://github.com/user-attachments/assets/b79d16c8-00a9-46cc-9698-3224017ccf21" />


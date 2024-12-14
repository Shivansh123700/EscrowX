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
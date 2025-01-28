# Secure Auctions Using Multi-Party Computation

This project implements a secure computation protocol called **B-share** for conducting sealed-bid auctions. The protocol ensures that bids are exchanged securely, preserving the privacy of all participants while determining the winner fairly.

## Key Features
- **Protocol Implemented**: B-share
- **Communication**: Utilized Boost ASIO for secure socket-based communication between multiple bidders.
- **Privacy**: Maintains bid confidentiality, revealing only the winning bid and bidder.

## Components
- Random share generation and distribution among bidders.
- Secure inter-bidder communication using TCP sockets.
- Efficient determination of the winning bid while preserving privacy.

## Authors
- Abhishek Khandelwal
- Pallav Goyal


# ICP Token Wallet

## Overview
This project is a basic token wallet built on the Internet Computer Protocol (ICP) using Rust. It supports basic functionalities such as sending and receiving tokens and viewing the balance.

## Project Structure

icp_token_wallet/
│
├── src/
│ ├── lib.rs
│ ├── types.rs
│ ├── wallet.rs
│ ├── tests.rs
│
├── dfx.json
├── Cargo.toml
├── README.md
├── .gitignore
└── .vscode/

markdown

## Setup Instructions

1. **Install DFX and Rust:**
   Follow the official [ICP documentation](https://internetcomputer.org/docs) to install DFX and Rust.

2. **Start the Local ICP Network:**

   ```bash
   dfx start --background
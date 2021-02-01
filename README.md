# Secret Network Contracts - SCRT

## First build the pacakge:
* Node version required: 14.7
```
cargo wasm
npm install
```

## Deploy the contract
```
node deploy.js
```

## How to install rust and run cargo
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env

# Add rustup target wasm32 for both stable and nightly
rustup default stable
rustup target list --installed
rustup target add wasm32-unknown-unknown

rustup install nightly
rustup target add wasm32-unknown-unknown --toolchain nightly

sudo apt install build-essential libssl-dev pkg-config

cargo install cargo-generate --locked cargo
```

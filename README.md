# Solana Hello World Program

A simple Solana smart contract that prints "Hello, Solana!" to the program logs.

## Usage

1. Install Solana CLI
2. Build with `cargo build-bpf`
3. Deploy with `solana program deploy ./target/deploy/solana_hello_world.so`

## Screenshots

![CLI Version](screenshots/cli-version.png)
![Successful Deployment](screenshots/deployment.png)

## Examples

```rust
msg!("Hello, Solana!");

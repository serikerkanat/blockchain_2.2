# Solana Hello World Program

A simple Solana smart contract that prints "Hello, Solana!" to the program logs.

## Usage

1. Install Solana CLI
2. Build with `cargo build-bpf`
3. Deploy with `solana program deploy ./target/deploy/solana_hello_world.so`
4. 
## Deployment Details
- **Solana CLI Version**: 2.1.19
- **Wallet Address**: 7MZmsJmRXqvFoA1ZGc8QgUUerFmDqkqQF4tVZtPkJBge
- **Program ID**: C2MVEt4CPxpiGYpkYKiWx2cSFPfVXDjD3RHXMcTj1263
- **Transaction**: [5ezGThRafYRjg9BhmUaHGuCv29S5h66bgWo4kLuB5FrFfY4cXMJtAmU9E8zexTn2MpXXZ9Rrnt86XRZtJcxE4DLe](https://explorer.solana.com/tx/5ezGThRafYRjg9BhmUaHGuCv29S5h66bgWo4kLuB5FrFfY4cXMJtAmU9E8zexTn2MpXXZ9Rrnt86XRZtJcxE4DLe?cluster=devnet)


![CLI Version](screenshots/cli-version.png)
![Successful Deployment](screenshots/deployment.png)

## Examples

```rust
msg!("Hello, Solana!");
```
## Screenshots
![Снимок экрана 2025-04-14 140908](https://github.com/user-attachments/assets/9437f902-6655-4e57-863c-d67fe8c906e0)
![Снимок экрана 2025-04-14 140951](https://github.com/user-attachments/assets/638aa5aa-5216-4e27-9ceb-40ae220a3342)
![Снимок экрана 2025-04-14 141348](https://github.com/user-attachments/assets/86baab76-3299-45aa-947e-b954ad3469d3)
![Снимок экрана 2025-04-14 210457](https://github.com/user-attachments/assets/9ce380ce-0e92-4957-a86e-7baeb7e9d9d2)
![Снимок экрана 2025-04-14 211805](https://github.com/user-attachments/assets/2630af02-8276-4c4e-8f83-6bbcfb6f628a)
![Снимок экрана 2025-04-14 212600](https://github.com/user-attachments/assets/e6cd332e-7201-4fa2-b53a-6296d8725509)
![Снимок экрана 2025-04-14 213141](https://github.com/user-attachments/assets/1cfd8ea2-8f7e-462d-b5d8-014cbfda16fe)

## How to Build & Deploy
```bash
cargo build-sbf
solana program deploy ./target/deploy/solana_hello_world.so

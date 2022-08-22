# paulx solana escrow contract & clients

Reference implementation for the guide https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/

The contract is in [program](program) and the tests are in [scripts/src](scripts/src)

# Simple Instruction (try out now)
```bash
# start local solana chain
# in `/home/vscode` dir
solana-test-validator -r

# new terminal below
# in program dir
# build solana program (may take a few minutes.)
cargo build-bpf

# follow the README instruction in `scripts`
```

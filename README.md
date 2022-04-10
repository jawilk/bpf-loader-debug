# bpf-loader-debug

fork of https://github.com/solana-labs/solana/tree/master/programs/bpf_loader  
- switched to rbpf with remote debug support in Cargo.toml
- added a thread local in lib.rs process_instruction() to check if should debug the current program

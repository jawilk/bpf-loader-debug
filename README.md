# bpf-loader-debug

fork of https://github.com/solana-labs/solana/tree/master/programs/bpf_loader  
- switched to rbpf fork with remote debug support in Cargo.toml
- added a thread local in lib.rs execute() to check if current program should be debugged

# hello-rust

## Install Rust
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
## Hello World
In a folder of choice...
```
cargo new hello-rust
cd hello-rust
cargo run
```

## Tools
```
cargo build     # build a project
cargo run       # run a project
cargo test      # test a project
cargo doc       # build documention

cargo publish   # publish a library to crates.io

cargo --version # display installed version
```

## Release
```
cargo build --release

./target/release/hello-rust
```

## Visual Studio Code
Install Extensions...
- rust-analyzer
- [others to be investigated]

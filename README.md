# vprytz-sockets

Online server implementation of [IndaPlus22/vprytz-chess-gui](https://github.com/IndaPlus22/vprytz-chess-gui).

## How to run

Make sure you have [Rust installed](https://www.rust-lang.org/tools/install).

Clone this project. Then use `cargo` to compile and run it.

```bash
cargo run
```

The server should listen on all interfaces, port `6000`. You can change this in `src/main.rs`. Use the chess GUI to connect to the server, and play chess (online)!

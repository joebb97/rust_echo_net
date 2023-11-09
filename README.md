# Echo Server/Client in Rust

Supports tcp and udp

## Run Server

```
$ cargo run -- -s [--proto tcp|udp] [--port port] [-a addr]
```

## Run Client
```
$ cargo run -- -c [-proto tcp|udp] [--port port] [-a addr]
```

## Expected Behavior

Whatever the client sends, the server sends back.
The server prints what it got from the client. The client prints what got sent back.

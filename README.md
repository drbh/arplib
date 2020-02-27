# arplib

### Build
```bash
cargo build --example basic --release
```

### Basic Usage
```
# you need sudo to access the network stack
sudo ./target/release/examples/basic
```

### Response
```rust
[
    (
        "192.168.1.1",
        "mac::address:here",
    ),
    (
        "192.168.1.5",
        "mac::address:here",
    ),
    (
        "192.168.1.4",
        "mac::address:here",
    ),
    (
        "192.168.1.3",
        "mac::address:here",
    ),
    (
        "192.168.1.7",
        "mac::address:here",
    ),
]
```
# Configuration Environment

follow [this](https://rust-osdev.github.io/uefi-rs/HEAD/tutorial/app.html)

but Cargo.toml like this

```toml
...
[dependencies]
log = "0.4.21"
uefi = { version = "0.28.0", features = ["panic_handler", "logger"] }
```


# Futures Borrow

Future-aware cell that can move borrows into futures and closures.

A future-aware borrow allows a value to be borrowed such that the borrow can be
moved into closures passed to `Future` combinators.

## Usage

To use `futures-borrow`, first add this to your `Cargo.toml`:

```toml
[dependencies]
futures-borrow = { git = "https://github.com/carllerche/futures-borrow" } # Soon on crates.io
```

Next, add this to your crate:

```rust
extern crate futures_borrow;

fn main() {
    // ...
}
```

## License

`futures-borrow` is primarily distributed under the terms of both the MIT license
and the Apache License (Version 2.0), with portions covered by various BSD-like
licenses.

See LICENSE-APACHE, and LICENSE-MIT for details.


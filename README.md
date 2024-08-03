# bxCAN peripheral driver

[![crates.io](https://img.shields.io/crates/v/bxcan-ng.svg)](https://crates.io/crates/bxcan-ng)
[![docs.rs](https://docs.rs/bxcan-ng/badge.svg)](https://docs.rs/bxcan-ng/)
![CI](https://github.com/guineawheek/bxcan-ng/workflows/CI/badge.svg)

This crate implements a driver for the bxCAN peripheral found in many low- to
middle-end STM32 and STM32-like microcontrollers.

Please refer to the [changelog](CHANGELOG.md) to see what changed in the last
releases.

## Usage

Add an entry to your `Cargo.toml`:

```toml
[dependencies]
bxcan-ng = "0.8.0"
```

Check the [API Documentation](https://docs.rs/bxcan-ng/) for how to use the
crate's functionality.

## Rust version support

This crate supports at least the 3 latest stable Rust releases. Bumping the
minimum supported Rust version (MSRV) is not considered a breaking change as
long as these 3 versions are still supported.

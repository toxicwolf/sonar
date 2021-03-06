# Sonar

[![Azure DevOps builds](https://img.shields.io/azure-devops/build/sonar-rs/5c991520-a1fe-4dc3-8bbd-dcc44d24d1b7/1.svg?style=flat-square)](https://dev.azure.com/sonar-rs/sonar/_build/latest?definitionId=1)
[![crates.io](https://img.shields.io/crates/v/sonar.svg?style=flat-square)](https://crates.io/crates/sonar)
[![License](https://img.shields.io/crates/l/sonar.svg?style=flat-square)](https://crates.io/crates/sonar)

3D game engine written in Rust

**DISCLAIMER: This library is a very early work in progress and not ready for general use!**

[Documentation](https://docs.rs/sonar)

## Design Goals

- Minimal boilerplate required
- Sane defaults
- Highly scaleable for non-trivial use cases
- Allow for 'dropping down' to lower abstraction levels
- Cross-platform support (Linux/Windows)
- Vulkan support

Non-goals:
- Support for multiple graphics backends

## Usage

Add this to your `Cargo.toml`:

```toml
[dependencies]
sonar = "*"
```

and this to your crate root:

```rust
extern crate sonar;
```

## License

Licensed under either of

 * Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT License ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any
additional terms or conditions.

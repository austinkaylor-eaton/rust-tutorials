# rust-tutorials

A collection of tutorials and exercises followed online to learn the [Rust programming language](https://www.rust-lang.org/).

## About

This repository tracks personal progress through various Rust learning resources available online. Each tutorial or exercise is kept here for reference and to reinforce concepts covered along the way.

## Prerequisites

To run any of the code in this repository you will need:

- [Rust](https://www.rust-lang.org/tools/install) (stable toolchain recommended)
- [Cargo](https://doc.rust-lang.org/cargo/) (bundled with Rust)

### Installing Rust

The easiest way to install Rust is via `rustup`:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Verify the installation:

```bash
rustc --version
cargo --version
```

## Getting Started

Clone the repository:

```bash
git clone https://github.com/austinkaylor-eaton/rust-tutorials.git
cd rust-tutorials
```

Navigate into any tutorial subdirectory and use Cargo to build and run it:

```bash
cargo run
```

To run the tests for a project:

```bash
cargo test
```

## Resources

Some useful resources for learning Rust:

- [The Rust Programming Language (the "Book")](https://doc.rust-lang.org/book/)
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
- [Rustlings](https://github.com/rust-lang/rustlings)
- [Exercism – Rust track](https://exercism.org/tracks/rust)

## License

This repository is intended for personal learning and reference. Feel free to use anything here as a starting point for your own Rust journey.

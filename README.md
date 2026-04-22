# Hello World in Rust

This project is a simple Hello World application written in Rust. The program demonstrates a basic Rust project structure, builds with Cargo, and prints `Hello, world!` to the terminal when run.

## Instructions for Build and Use

Steps to build and/or run the software:

1. Install the Rust toolchain and Cargo, or enter the provided Nix development shell with `nix develop`.
2. Open a terminal in the project folder.
3. Run `cargo build` to compile the project.
4. Run `cargo run` to build and execute the program.

Instructions for using the software:

1. From the project root, run `cargo run`.
2. Wait for Cargo to compile the program if needed.
3. View the output `Hello, world!` in the terminal.

## Development Environment

To recreate the development environment, you need the following software and/or libraries with the specified versions:

* Rust compiler `rustc 1.95.0`
* Cargo `1.95.0`
* A code editor or IDE such as Visual Studio Code, RustRover, or another editor with Rust support
* Optional: Nix with flakes enabled to use the provided [flake.nix](flake.nix)

## Useful Websites to Learn More

I found these websites useful in developing this software:

* [The Rust Programming Language](https://doc.rust-lang.org/book/)
* [Cargo Book](https://doc.rust-lang.org/cargo/)
* [Rust by Example](https://doc.rust-lang.org/rust-by-example/)

## Future Work

The following items I plan to fix, improve, and/or add to this project in the future:

* [ ] Accept user input and print a personalized greeting
* [ ] Add automated tests for future program behavior
* [ ] Expand the application from a basic greeting into a small interactive command-line program

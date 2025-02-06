# Moon OS

Moon OS is a toy operating system written in Rust following the tutorial found [here](https://os.phil-opp.com). This project is an educational tool to explore OS development concepts using the Rust programming language.

## Getting Started

### Prerequisites
- Install QEMU. You can do this using your package manager. For example:
    - On Ubuntu:
        ```sh
        sudo apt-get install qemu
        ```
    - On macOS:
        ```sh
        brew install qemu
        ```
    - On Windows:
        Download the installer from the [official QEMU website](https://www.qemu.org/download/) and follow the installation instructions.

- Install Rust with the nightly toolchain. You can do this using `rustup`:
    ```sh
    rustup install nightly
    rustup default nightly
    ```

### Building

To build the project, run:
```sh
cargo build
```

### Running

To run the project, use:
```sh
cargo run
```

### Testing

To run the project tests, use:
```sh
cargo test
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
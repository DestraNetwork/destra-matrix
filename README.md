
# Destra Matrix
A fork of Foundry, customized as a toolkit for the Destra L2 Chain.

## DestraCLI

DestraCLI is a command-line tool for performing Destra L2 RPC calls. You can make smart contract calls, send transactions, or retrieve any type of chain data - all from your command-line!

### Prerequisites
- [Rust](https://www.rust-lang.org/tools/install) installed on your system. You can install Rust via Rustup by following the instructions at [rustup.rs](https://rustup.rs/).

### Setting Up Rust & Cargo
1. Install Rust and Cargo via Rustup by running the following command in your terminal:

    ```bash
    curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
    ```

2. Follow the prompts to complete the installation process.

## Building the Project
1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/DestraNetwork/destra-matrix.git
    ```

2. Navigate to the DestraCLI directory:

    ```bash
    cd destra-matrix/crates/destracli
    ```

3. Build the project using Cargo:

    ```bash
    cargo build --release
    ```

    This command will compile the destracli in release mode, optimizing it for performance.

## Installing the Executable
1. Once the build process is complete, navigate to the target directory:

    ```bash
    cd ../../target/release
    ```

2. Move the executable file to the `bin` directory in your home folder:

    ```bash
    sudo mv destracli /usr/local/bin
    ```

This command moves the destracli to the `bin` directory in your home folder, making it accessible from anywhere in the terminal.

## Running the Executable
After moving the executable to the `bin` directory, you can run it from anywhere in the terminal by simply typing its name:

```bash
destracli --version

# My First Rust Compression Project

## Overview

This is my first attempt at a Rust project, and it's a program that demonstrates file compression using the flate2 crate. The goal is to compress a source file and write the compressed data to a target file.

## Usage

1. Make sure you have Rust and Cargo installed on your system.

2. Clone the repository:
```bash
   git clone https://github.com/your-username/rust-compression-project.git

3. Navigate to the project directory

4. Build the project:
```bash
   cargo build

5. Run the project:
```bash
   cargo run source_file.txt target_file.gz

Replace source_file.txt with the path to the file you want to compress and target_file.gz with the desired name for the compressed file.


## Project Structure

src/main.rs: The main Rust source file containing the compression logic.

Cargo.toml: The project configuration file for Cargo.

## Dependencies

flate2: A Rust crate for working with compressed files.


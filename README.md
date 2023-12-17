# Project Title

This is a simple, multi-threaded port scanner written in Rust. It scans the open ports of a given IP address and prints them to the console.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Rust installed on your machine. You can download it from the official [Rust website](https://www.rust-lang.org/tools/install).

### Installing

Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/project.git
```

Navigate to the project directory:

```bash
cd project
```

Build the project:

```bash
cargo build
```

## Usage

Run the program with the following command:

```bash
cargo run -- -t <NUMBER_OF_THREADS> <IP_ADDRESS>
```

Replace `<IP_ADDRESS>` with the IP address you want to scan and `<NUMBER_OF_THREADS>` with the number of threads you want to use for scanning.

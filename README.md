[![build status](https://api.travis-ci.org/nuxeh/url-bot-rs.png?branch=master)](https://travis-ci.org/nuxeh/url-bot-rs)

# url-bot-rs

URL title fetching bot for IRC in Rust

## Build

### Get rust

[https://www.rust-lang.org/en-US/install.html](https://www.rust-lang.org/en-US/install.html)

### Build

    cd url-bot-rs
    cargo build

### Run tests

    cargo test

## Configuration

Configuration is done by editing `config.toml`.

This may include:
- Address of the IRC server to connect to
- Connection credentials
- The nick to use when joining the server
- Channels to join on the server

## Run

    cargo run

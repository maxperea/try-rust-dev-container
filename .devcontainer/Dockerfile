# Use an official Rust image as a parent image
FROM mcr.microsoft.com/devcontainers/rust:0-1-bullseye

# Add rust-analyzer download and setup
RUN curl -L https://github.com/rust-lang/rust-analyzer/releases/download/2023-08-07/rust-analyzer-aarch64-unknown-linux-gnu.gz -o /usr/bin/rust-analyzer.gz
RUN gzip -d /usr/bin/rust-analyzer.gz
RUN chmod +x /usr/bin/rust-analyzer

# Learning Vulkano

This is a small personal project for learning [Vulkano](https://github.com/vulkano-rs/vulkano), a Rust wrapper around the Vulkan graphics API.

The current example:

- Loads the Vulkan library and creates a Vulkan instance
- Selects a physical device and graphics queue
- Creates source and destination buffers
- Copies data between the buffers with a Vulkan command buffer
- Verifies that the copied contents are equal

This repository is a learning playground, so the code will evolve as I explore more of Vulkan and Vulkano.

## Requirements

- Rust and Cargo
- A Vulkan-capable GPU or driver
- Vulkan runtime/loader installed for your operating system

## Running

Clone the repository and run the example:

```bash
cargo run
```

A successful run prints:

```text
Success! The contents of the source and destination buffers are equal.
```

## Useful commands

```bash
cargo check
cargo test
cargo fmt
```

## License

This project is primarily for personal learning and experimentation.

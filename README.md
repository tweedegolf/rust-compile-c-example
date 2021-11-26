# Rust+C basic example

Code taken from the [rust cookbook](https://rust-lang-nursery.github.io/rust-cookbook/development_tools/build_tools.html). Run with

```
cargo run
```

## Troubleshooting

This package compiles C and therefore needs a C compiler to be available. On \*nix `gcc` is usually available. If set, the environment variable `CC` is used to find the C compiler to use. 

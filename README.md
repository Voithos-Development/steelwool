# `steelwool 🧶🔗`

lightweight library for interacting with LLMs

## TODO

- [ ] Add the following optional features to `Cargo.toml`:

  ```toml
  [features]
  ollama = ["ollama-rs"]

  [dependencies.ollama-rs]
  optional = true
  version = "0.2.6"
  ```

## Testing

To test the basic ollama integration, run in root:

```
cargo test --features ollama -- --nocapture
```

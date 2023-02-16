The dapp contract cross contract calls the protocol contract. The dapp contract references protocol via `path`.

To test the cross contract build, run the following:

```
cd dapp-example/contracts

RUST_LOG=debug cargo contract build --manifest-path ./Cargo.toml --verbose --keep-debug-symbols --generate all
```

# Anoma ledger prototype

Handy commands:

```shell
# Build
make

# Build and link the executables
make install

# Run Anoma daemon (this will also initialize and run Tendermint node)
make run

# Reset the state (resets Tendermint too), ...
cargo run --bin anomad -- reset
# ...or shorter when executables are installed:
anoma reset

# Submit a transaction to the Tendermint node, ...
cargo run --bin anomac -- transfer -c 1
# ...or shorter when executables are installed:
anoma transfer -c 1
```
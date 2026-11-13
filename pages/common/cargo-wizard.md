# cargo wizard

> Cargo subcommand for applying predefined profile templates to `Cargo.toml` for faster builds or runtime performance.
> More information: <https://github.com/kobzol/cargo-wizard>.

- Run the interactive wizard in the current Cargo project:

`cargo wizard`

- Apply a predefined template (`fast-compile`, `fast-runtime`, or `min-size`) to a specific profile:

`cargo wizard apply {{fast-compile|fast-runtime|min-size}} {{dev|release}}`

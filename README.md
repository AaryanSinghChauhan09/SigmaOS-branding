# SigmaOS Branding

A Rust library for holding and editing branding metadata: distribution name, version, tagline, copyright, support URL, and text logo lines. `Branding` can return these values and assemble a human-readable about summary.

The crate owns branding data only. It does not render graphics, install fonts or wallpapers, or integrate with a desktop shell.

## Build

The manifest references the sibling [`SigmaOS-kernel`](../SigmaOS-kernel) crate. From the SigmaOS checkout:

```sh
cargo check --manifest-path SigmaOS-branding/Cargo.toml --lib
```

## License

GPL-3.0-or-later. See [`Cargo.toml`](Cargo.toml).

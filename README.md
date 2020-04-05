# asdf-rust

[![Build Status](https://travis-ci.org/code-lever/asdf-rust.svg?branch=master)](https://travis-ci.org/code-lever/asdf-rust)

Rust plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```
asdf plugin-add rust https://github.com/code-lever/asdf-rust.git
```

After you have installed rust, do NOT follow the directions it outputs to update your PATH
 -- asdf's shim will handle that for you!

## Use

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of Rust.

### Default `cargo` crates

asdf-rust can automatically install a default set of packages with `cargo` right after installing a Rust version.
To enable this feature, provide a \$HOME/.default-cargo-crates file that lists one package per line, for example:

```
// cli-tools
ripgrep

// install from source
--git https://github.com/sharkdp/bat
```

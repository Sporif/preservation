# Preservation

Nix tooling to enable declarative management of non-volatile system state.

Inspired and heavily influenced by [impermanence](https://github.com/nix-community/impermanence) but not
meant to be a drop-in replacement.

## Work in Progress

🚧 still under construction 🚧

Check out [the test](tests/basic.nix) 👀

## Why?

This aims to provide a declarative state management solution for NixOS systems without resorting to
interpreters to do the heavy lifting. This should enable impermanence-like state management on
an "interpreter-less" system.

Related:
- https://github.com/NixOS/nixpkgs/issues/265640
- https://github.com/nix-community/projects/blob/main/proposals/nixpkgs-security-phase2.md#boot-chain-security

## License

This project is released under the terms of the MIT License. See [LICENSE](./LICENSE).

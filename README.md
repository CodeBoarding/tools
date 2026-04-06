# CodeBoarding Tools

This repository stores pre-built tool binaries used by [CodeBoarding](https://github.com/CodeBoarding/CodeBoarding) for static code analysis.

## Included Tools

| Tool | Description |
|------|-------------|
| [tokei](https://github.com/XAMPPRocky/tokei) | Fast line-of-code counter supporting many languages |
| [gopls](https://pkg.go.dev/golang.org/x/tools/gopls) | Go language server, used for Go static analysis via LSP |

## How Releases Work

Binaries are built and published automatically via the [`build-tools.yml`](https://github.com/CodeBoarding/CodeBoarding/blob/main/.github/workflows/build-tools.yml) workflow in the main CodeBoarding repository. Each release includes binaries for Linux, macOS, and Windows, along with SHA-256 checksums.

## Release Artifacts

Each release contains:

- `tokei-linux`, `tokei-macos`, `tokei-windows.exe`
- `gopls-linux`, `gopls-macos`, `gopls-windows.exe`
- `checksums.sha256`

## License

This repository is licensed under the [Apache License 2.0](LICENSE).
The distributed tool binaries are subject to their own respective licenses.

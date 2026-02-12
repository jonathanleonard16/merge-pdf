## About

A simple CLI tool based on [lopdf](https://github.com/J-F-Liu/lopdf) for mergin PDF files.

## Usage

1. build the release version
```
cargo build --release
```
2. move binary to /bin
```
cp target/release/merge-pdf ~/bin/merge-pdf
```
3. run from any working directory
```
merge-pdf --name <target-path> <pdf-paths>
```

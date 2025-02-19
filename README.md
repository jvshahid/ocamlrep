# ocamlrep: Interop OCaml and Rust code [![facebook](https://circleci.com/gh/facebook/ocamlrep.svg?style=svg)](https://app.circleci.com/pipelines/github/facebook/ocamlrep)

The goal of this project is to make OCaml and Rust code interoperable. While in its early stage of development, this library is actively used by the [HHVM](https://github.com/facebook/hhvm) project, mostly in the Hack type checker, to enable OCaml code to rely on Rust.

## Requirements
This project is stand-alone and requires or works with:

  - OCaml 4.14.0;
  - A rust nightly toolchain.

## Building ocamlrep
Assume an opam installation on a `4.x` or `5.0`switch. From the repository root,
```bash
    cargo build
```

## Contributing
See the [CONTRIBUTING](CONTRIBUTING.md) file for how to help out.

## License
ocamlrep has an MIT license. See the LICENSE file included in this distribution.

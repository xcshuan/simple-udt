# simple-udt

The following must be installed and available to use Capsule.

+ cargo and rust - Capsule uses cargo to generate Rust contracts and run tests. https://www.rust-lang.org/tools/install.
+ docker - Capsule uses docker container to reproducible build contracts. It's also used by cross. https://docs.docker.com/get-docker/
+ cross. Capsule uses cross to build rust contracts. Install with
    ```
    $ cargo install cross --git https://github.com/cross-rs/cross
    ```
Note: All commands must be accessible in the PATH in order for them to be used by Capsule.

Note: The current user must have permission to manage Docker instances. How to manage Docker as a non-root user.

## Install capsule

Install the latest version [capsule](https://github.com/nervosnetwork/capsule/)

```
cargo install ckb-capsule
```

## Contracts test

Build contracts:

``` sh
capsule build
```

Run tests:

``` sh
capsule test
```

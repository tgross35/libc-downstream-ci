# Downstream CI Template for Rust's `libc`

Sample template for CI that tests Rust's `libc`. This does the following:

* Launch CI once per day
* Check out both this repo and rust-lang/libc
* Apply all patches in the `patches` directory to `libc`
* Start `libc` tests

Please consider submitting any patches upstream once CI has been figured out,
to make things easy for future.

See <https://github.com/rust-lang/libc/issues/5209> for more details.

## Licensing

This is derived from libc's CI so available under the same licenses (MIT
or Apache-2.0).

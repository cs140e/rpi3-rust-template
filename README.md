# Raspberry Pi 3 Rust Starter Template

How to use this:

  1. Install the `aarch64-none-elf` toolchain.

     * On Linux, download from [linaro]. Rename binaries to `aarch64-none-elf`.
     * On Mac: `brew tap SergioBenitez/osxct && brew install aarch64-none-elf`

  2. Install Nightly Rust

     Assuming you have `rustup` installed, this is as easy as `rustup default nightly`.

  3. Install Xargo

     `cargo install xargo`

You can now call:

  * `make`: creates build/kernel.{a,elf,hex}

[linaro]: https://releases.linaro.org/components/toolchain/binaries/7.2-2017.11/aarch64-elf/

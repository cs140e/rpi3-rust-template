# Raspberry Pi 3 Rust Starter Template

How to use this:

  1. Install the `aarch64-none-elf` toolchain.

     * On Linux, download the [linaro toolchain]. Add `bin/` to your `$PATH`.
     * On Mac: `brew tap SergioBenitez/osxct && brew install aarch64-none-elf`.

  2. Install Rust nightly.

     Assuming you have `rustup` installed, this is as easy as `rustup default nightly`.

  3. Install Xargo.

     ```sh
     rustup component add rust-src
     cargo install xargo
     ```

You can now call:

  * `make`: creates `build/template.{a,elf,hex.bin}`

[linaro toolchain]: https://web.stanford.edu/class/cs140e/files/aarch64-none-elf-linux-x64.tar.gz

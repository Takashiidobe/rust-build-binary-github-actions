# Test Binary

Using Github Actions to Build a binary for as many platforms as possible.

Here are the platforms that this builds for.

## Tier 1

| Target                    | OS           | Uses Cross? | Compiles? |
| ------------------------- | ------------ | ----------- | --------- |
| aarch64-unknown-linux-gnu | ubuntu-20.04 | ✅          | ✅        |
| i686-pc-windows-gnu       | windows-2019 | ❌          | ✅        |
| i686-unknown-linux-gnu    | ubuntu-20.04 | ✅          | ✅        |
| i686-pc-windows-msvc      | windows-2019 | ❌          | ✅        |
| x86_64-apple-darwin       | macos-10.15  | ❌          | ✅        |
| x86_64-pc-windows-gnu     | windows-2019 | ❌          | ✅        |
| x86_64-pc-windows-msvc    | windows-2019 | ❌          | ✅        |
| x86_64-unknown-linux-gnu  | ubuntu-20.04 | ❌          | ✅        |

## Tier 2 with Host Tools

| Target                          | OS           | Uses Cross? | Compiles? |
| ------------------------------- | ------------ | ----------- | --------- |
| aarch64-apple-darwin            | macos-11.0   | ❌          | ✅        |
| aarch64-pc-windows-msvc         | windows-2019 | ❌          | ✅        |
| aarch64-unknown-linux-musl      | ubuntu-20.04 | ✅          | ✅        |
| arm-unknown-linux-gnueabi       | ubuntu-20.04 | ✅          | ✅        |
| arm-unknown-linux-gnueabihf     | ubuntu-20.04 | ✅          | ✅        |
| armv7-unknown-linux-gnueabihf   | ubuntu-20.04 | ✅          | ✅        |
| mips-unknown-linux-gnu          | ubuntu-20.04 | ✅          | ✅        |
| mips64-unknown-linux-gnuabi64   | ubuntu-20.04 | ✅          | ✅        |
| mips64el-unknown-linux-gnuabi64 | ubuntu-20.04 | ✅          | ✅        |
| mipsel-unknown-linux-gnuabi     | ubuntu-20.04 | ✅          | ✅        |
| powerpc-unknown-linux-gnu       | ubuntu-20.04 | ✅          | ✅        |
| powerpc64-unknown-linux-gnu     | ubuntu-20.04 | ✅          | ✅        |
| powerpc64le-unknown-linux-gnu   | ubuntu-20.04 | ✅          | ✅        |
| riscv64gc-unknown-linux-gnu     | ubuntu-20.04 | ✅          | ✅        |
| s390x-unknown-linux-gnu         | ubuntu-20.04 | ✅          | ✅        |
| x86_64-unknown-freebsd          | ubuntu-20.04 | ✅          | ✅        |
| x86_64-unknown-illumos          | ubuntu-20.04 | ✅          | ❌        |
| arm-unknown-linux-musleabihf    | ubuntu-20.04 | ✅          | ✅        |
| i686-unknown-linux-musl         | ubuntu-20.04 | ✅          | ✅        |
| x86_64-unknown-linux-musl       | ubuntu-20.04 | ✅          | ✅        |
| x86_64-unknown-netbsd           | ubuntu-20.04 | ✅          | ✅        |

## Tier 2

| Target                              | OS           | Uses Cross? | Compiles? |
| ----------------------------------- | ------------ | ----------- | --------- |
| aarch64-apple-ios                   | macos-11.0   | ❌          | ✅        |
| aarch64-apple-ios-sim               | macos-11.0   | ❌          | ✅        |
| aarch64-fuchsia                     | ubuntu-20.04 | ✅          | ❓        |
| aarch64-linux-android               | ubuntu-20.04 | ✅          | ❓        |
| aarch64-unknown-none-softfloat      | ubuntu-20.04 | ✅          | ❓        |
| aarch64-unknown-none                | ubuntu-20.04 | ✅          | ❓        |
| arm-linux-androideabi               | ubuntu-20.04 | ✅          | ❓        |
| arm-unknown-linux-musleabi          | ubuntu-20.04 | ✅          | ✅        |
| arm-unknown-linux-musleabihf        | ubuntu-20.04 | ✅          | ✅        |
| armebv7r-none-eabi                  | ubuntu-20.04 | ✅          | ❓        |
| armebv7r-none-eabihf                | ubuntu-20.04 | ✅          | ❓        |
| armv5te-unknown-linux-gnueabi       | ubuntu-20.04 | ✅          | ❓        |
| armv5te-unknown-linux-musleabi      | ubuntu-20.04 | ✅          | ❓        |
| armv7-linux-androideabi             | ubuntu-20.04 | ✅          | ❓        |
| armv7-unknown-linux-gnueabi         | ubuntu-20.04 | ✅          | ❓        |
| armv7-unknown-linux-musleabi        | ubuntu-20.04 | ✅          | ❓        |
| armv7-unknown-linux-musleabihf      | ubuntu-20.04 | ✅          | ❓        |
| armv7a-none-eabi                    | ubuntu-20.04 | ✅          | ❓        |
| armv7r-none-eabi                    | ubuntu-20.04 | ✅          | ❓        |
| armv7r-none-eabihf                  | ubuntu-20.04 | ✅          | ❓        |
| armv5te-unknown-linux-gnueabi       | ubuntu-20.04 | ✅          | ❓        |
| armv5te-unknown-linux-musleabi      | ubuntu-20.04 | ✅          | ❓        |
| armv7-linux-androideabi             | ubuntu-20.04 | ✅          | ❓        |
| armv7-unknown-linux-gnueabi         | ubuntu-20.04 | ✅          | ❓        |
| armv7-unknown-linux-musleabi        | ubuntu-20.04 | ✅          | ❓        |
| armv7-unknown-linux-musleabihf      | ubuntu-20.04 | ✅          | ✅        |
| armv7a-none-eabi                    | ubuntu-20.04 | ✅          | ❓        |
| armv7a-none-eabihf                  | ubuntu-20.04 | ✅          | ❓        |
| asmjs-unknown-emscripten            | ubuntu-20.04 | ✅          | ❓        |
| i586-pc-windows-msvc                | windows-2019 | ❌          | ❓        |
| i586-unknown-linux-gnu              | ubuntu-20.04 | ✅          | ❓        |
| i586-unknown-linux-musl             | ubuntu-20.04 | ✅          | ❓        |
| i686-linux-android                  | ubuntu-20.04 | ✅          | ❓        |
| i686-unknown-freebsd                | ubuntu-20.04 | ✅          | ❓        |
| i686-unknown-linux-musl             | ubuntu-20.04 | ✅          | ❓        |
| mips-unknown-linux-musl             | ubuntu-20.04 | ✅          | ❓        |
| mips64-unknown-linux-muslabi64      | ubuntu-20.04 | ✅          | ❓        |
| mips64el-unknown-linux-muslabi64    | ubuntu-20.04 | ✅          | ❓        |
| nvptx64-nvidia-cuda                 | ubuntu-20.04 | ✅          | ❓        |
| riscv32i-unknown-none-elf           | ubuntu-20.04 | ✅          | ❓        |
| riscv32imac-unknown-none-elf        | ubuntu-20.04 | ✅          | ❓        |
| riscv32imc-unknown-none-elf         | ubuntu-20.04 | ✅          | ❓        |
| riscv64gc-unknown-none-elf          | ubuntu-20.04 | ✅          | ❓        |
| riscv64imac-unknown-none-elf        | ubuntu-20.04 | ✅          | ❓        |
| sparc64-unknown-linux-gnu           | ubuntu-20.04 | ✅          | ❓        |
| sparcv9-sun-solaris                 | ubuntu-20.04 | ✅          | ❓        |
| thumbv6m-none-eabi                  | ubuntu-20.04 | ✅          | ❓        |
| thumbv7em-none-eabi                 | ubuntu-20.04 | ✅          | ❓        |
| thumbv7em-none-eabihf               | ubuntu-20.04 | ✅          | ❓        |
| thumbv7m-none-eabi                  | ubuntu-20.04 | ✅          | ❓        |
| thumbv7neon-linux-androideabi       | ubuntu-20.04 | ✅          | ❓        |
| thumbv7neon-unknown-linux-gnueabihf | ubuntu-20.04 | ✅          | ❓        |
| thumbv8m.base-none-eabi             | ubuntu-20.04 | ✅          | ❓        |
| thumbv8m.main-none-eabi             | ubuntu-20.04 | ✅          | ❓        |
| thumbv8m.main-none-eabihf           | ubuntu-20.04 | ✅          | ❓        |
| wasm32-unknown-emscripten           | ubuntu-20.04 | ✅          | ❓        |
| wasm32-unknown-unknown              | ubuntu-20.04 | ✅          | ❓        |
| wasm32-wasi                         | ubuntu-20.04 | ✅          | ❓        |
| x86_64-apple-ios                    | macos-10.15  | ❌          | ❓        |
| x86_64-fortanix-unknown-sgx         | ubuntu-20.04 | ✅          | ❓        |
| x86_64-fuchsia                      | ubuntu-20.04 | ✅          | ❓        |
| x86_64-linux-android                | ubuntu-20.04 | ✅          | ❓        |
| x86_64-pc-solaris                   | ubuntu-20.04 | ✅          | ❓        |
| x86_64-unknown-linux-gnux32         | ubuntu-20.04 | ✅          | ❓        |
| x86_64-unknown-redox                | ubuntu-20.04 | ✅          | ❓        |

## Tier 3

| Target                   | OS           | Uses Cross? | Compiles? |
| ------------------------ | ------------ | ----------- | --------- |
| aarch64-apple-ios-macabi | macos-10.15  | ❌          | ❓        |
| aarch64-apple-tvos       | macos-10.15  | ❌          | ❓        |
| aarch64-unknown-freebsd  | ubuntu-20.04 | ✅          | ❓        |
| aarch64-unknown-hermit   | ubuntu-20.04 | ✅          | ❓        |
| aarch64-unknown-uefi     | ubuntu-20.04 | ✅          | ❓        |

## License

Licensed under either of Apache License, Version 2.0 or MIT license at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.

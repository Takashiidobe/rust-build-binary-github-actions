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

| Target                         | OS           | Uses Cross? | Compiles? |
| ------------------------------ | ------------ | ----------- | --------- |
| aarch64-apple-ios              | macos-11.0   | ❌          | ❓        |
| aarch64-apple-ios-sim          | macos-11.0   | ❌          | ❓        |
| aarch64-fuchsia                | ubuntu-20.04 | ✅          | ❓        |
| aarch64-linux-android          | ubuntu-20.04 | ✅          | ❓        |
| aarch64-unknown-none-softfloat | ubuntu-20.04 | ✅          | ❓        |
| aarch64-unknown-none           | ubuntu-20.04 | ✅          | ❓        |
| arm-linux-androideabi          | ubuntu-20.04 | ✅          | ❓        |
| arm-unknown-linux-musleabi     | ubuntu-20.04 | ✅          | ❓        |
| arm-unknown-linux-musleabihf   | ubuntu-20.04 | ✅          | ❓        |
| armebv7r-none-eabi             | ubuntu-20.04 | ✅          | ❓        |
| armebv7r-none-eabihf           | ubuntu-20.04 | ✅          | ❓        |
| armv5te-unknown-linux-gnueabi  | ubuntu-20.04 | ✅          | ❓        |
| armv5te-unknown-linux-musleabi | ubuntu-20.04 | ✅          | ❓        |
| armv7-linux-androideabi        | ubuntu-20.04 | ✅          | ❓        |
| armv7-unknown-linux-gnueabi    | ubuntu-20.04 | ✅          | ❓        |
| armv7-unknown-linux-musleabi   | ubuntu-20.04 | ✅          | ❓        |
| armv7-unknown-linux-musleabihf | ubuntu-20.04 | ✅          | ❓        |
| armv7a-none-eabi               | ubuntu-20.04 | ✅          | ❓        |
| armv7r-none-eabi               | ubuntu-20.04 | ✅          | ❓        |
| armv7r-none-eabihf             | ubuntu-20.04 | ✅          | ❓        |
|                                |              |             |           |
| x86_64-fortanix-unknown-sgx    | ubuntu-20.04 | ✅          | ❓        |
| x86_64-fuchsia                 | ubuntu-20.04 | ✅          | ❓        |
| x86_64-linux-android           | ubuntu-20.04 | ✅          | ❓        |
| x86_64-pc-solaris              | ubuntu-20.04 | ✅          | ❓        |
| x86_64-unknown-linux-gnux32    | ubuntu-20.04 | ✅          | ❓        |
| x86_64-unknown-redox           | ubuntu-20.04 | ✅          | ❓        |

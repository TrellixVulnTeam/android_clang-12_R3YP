# Android Clang 12 + Binutils 2.38

Android (7714059, based on r416183c1) clang version 12.0.8 taken from [Prebuilt Android Clang for Linux x86](https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86) and [TC-Build](https://github.com/ClangBuiltLinux/tc-build.git) for GNU Binutils.

## How to use

```shell
$ export PATH=$(pwd)/bin
$ export LD_LIBRARY_PATH=$(pwd)/lib64:$LD_LIBRARY_PATH
```

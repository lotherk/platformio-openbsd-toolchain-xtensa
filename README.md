# platformio-openbsd-toolchain-xtensa

This is a fake platformio package to make it work on OpenBSD. It is inspired by [https://github.com/trombik/platformio-freebsd-toolchain-xtensa/](https://github.com/trombik/platformio-freebsd-toolchain-xtensa/).

## Required packages
```
$ pkg_add arduino-esp8266
```

## Installation

Go to `~/.platformio/packages` and clone this repository. It is important to name the cloned directory `toolchain-xtensa`.
```
$ cd ~/.platformio/packages
$ git clone https://github.com/lotherk/platformio-openbsd-toolchain-xtensa toolchain-xtensa
$ cd toolchain-xtensa
$ ./init.sh
```

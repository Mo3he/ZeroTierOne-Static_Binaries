# ZeroTier-One static binaries
This project provides help building static binaries for zerotier from source [Zerotier-One](https://github.com/zerotier/ZeroTierOne) .

# Building
Open the platform you want to build for.

To build latest version run:
```sh
make
```
To build specific version, set variable:
```sh
make ZT_VERSION=1.14.2
```
Or to build for a different platform:
```sh
make PLATFORM=linux/aarch64
```

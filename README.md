# libalac

Shared library builds of the Apple Lossless Audio Codec (ALAC).
For GNU and BSD-based platforms like macOS (`libalac.dylib`) and Linux.


## Requirements Installation

### macOS

Using [Homebrew](https://brew.sh):

```bash
brew install automake autoconf libtool pkg-config
```

### Linux (Debian)

```bash
apt-get install autoconf automake libtool
```


## Usage

### Setup

```bash
autoreconf -fiv
./configure
```

### Build

```bash
make
```

### Build & Install

```bash
make install
```
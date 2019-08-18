# libalac

Shared & Static library (framework) builds of the Apple Lossless Audio Codec (ALAC).
For GNU and BSD platforms like macOS, Linux and more.


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
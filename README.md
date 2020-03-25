qemu-system-riscv64.deb
========
QEMU 4.2 Binary targetting riscv64-softmmu, packaged for Debian 10, *Buster*.
Made for [Operating Systems] class of Seoul National University.

### How to install
```bash
# Download package first
wget https://git.io/JvSnF -O qemu-system-riscv64_4.2.0-1_amd64.deb

# Install
sudo apt-get install ./qemu-system-riscv64_4.2.0-1_amd64.deb
```

&nbsp;

### How to package it by yourself
```bash
sudo apt-get install \
  build-essential devscripts debhelper bison flex \
  libglib2.0-dev libpixman-1-dev

./build
```

###### Reference
- https://salsa.debian.org/qemu-team/qemu

[Operating Systems]: http://csl.snu.ac.kr/courses/4190.307/2020-1/

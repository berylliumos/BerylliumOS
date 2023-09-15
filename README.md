<p align="center">
  <a href="https://berylliumos.com">
    <img alt="BerylliumOS" src="https://github.com/berylliumos/BerylliumOS/blob/main/assets/beryllium.png" width="546">
  </a>
</p>

<p align="center">
  <h1>Beryllium Operating System</h1>
</p>

<p align="center">
  Lightweight, portable, and highly optimized UNIX-like operating system.
</p>

<p align="center">
  <a href="https://github.com/berylliumos/BerylliumOS/blob/main/LICENSE">
    <img alt="GitHub" src="https://img.shields.io/github/license/berylliumos/BerylliumOS">
  </a>
  <img alt="GitHub issues" src="https://img.shields.io/github/issues/berylliumos/BerylliumOS">
  <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/berylliumos/BerylliumOS">
</p>

<hr>

## Table of contents

- [Introduction](#introduction)
- [Quick start](#quick-start)
- [Contributing](#contributing)
- [Documentation](#documentation)
- [Disk images](#disk-images)
- [License](#license)

## Introduction

**BerylliumOS is a fast, lightweight UNIX-like general-purpose operating system optimized for various architectures and modern hardware.** Starting from scratch, the operating system uses various algorithms and data structures for high performance, as well as being designed around new hardware features from the newest PC architectures. The core of the system is the Beryllium kernel.

## Quick start

When building BerylliumOS, you run the shell script in the root directory of the repository "build.sh". The build output is placed in a "build" directory, and the output of the build process are binaries for the kernel and modules, a disk image tool (diskutil), an ISO image for a small system, and an ISO image for installation.

Simply run the script in a terminal:

```bash
chmod +x build.sh
./build.sh
```

To build BerylliumOS, you need the following dependencies:

* A C and C++ compiler
* CMake
* C/C++ linker and make program (usually comes with the compiler)
* NASM assembler

## Contributing

Contributions are welcome, such as adding features and fixing bugs. Please read the [contributing guide](CONTRIBUTING.md) for more information and guidelines for contributions.

## Documentation

We are currently working on a website with comprehensive docmentation. Until then, the repository contains some mmarkdown documentation files inside various directories.

## Disk images

The **diskutil** program allows you to produce ISO images, as well as hard drive images. It also supports virtual machine images and configuration. The ISO bootable images can be written to a storage device such as a USB flash drive, and executed on a computer. The documentation for diskutil is inside the "diskutil" directory.

Official ISO bootable images can be downloaded from the [BerylliumOS website](https://berylliumos.com).

## License

Copyright (c) 2023 Beryllium Systems. All rights reserved.

Licensed under the [MIT](LICENSE) license.

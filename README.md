# ftplib++ Windows Modifications
This repository contains modifications to `ftplib++` to make it work on Windows.

## Modifications
- Adjusted socket handling for Windows.
- Added Winsock2 headers and library dependencies.

## Usage
- Include `ftplib.h` and `ftplib.cpp` in your project.
- Link against OpenSSL libraries (`libcrypto.lib` and `libssl.lib`).

## License
This code is licensed under the LGPL-2.1. See the LICENSE file for details.

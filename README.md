# ftplib++ Windows Modifications
This is a modified version of [ftplib++](https://github.com/mkulke/ftplibpp) for Windows compatibility.

## Modifications
- Adjusted socket handling for Windows.
- Added Winsock2 headers and library dependencies.

## Usage
- Include `ftplib.h` and `ftplib.cpp` in your project.
- Link against OpenSSL libraries (`libcrypto.lib` and `libssl.lib`).

## License
This code is licensed under the LGPL-2.1. See the LICENSE file for details.

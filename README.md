# Echo Wallet

[![Continuous Integration](https://github.com/mimblewimble/echo-wallet/actions/workflows/ci.yaml/badge.svg)](https://github.com/mimblewimble/echo-wallet/actions/workflows/ci.yaml)
[![Coverage Status](https://img.shields.io/codecov/c/github/mimblewimble/echo-wallet/master.svg)](https://codecov.io/gh/mimblewimble/echo-wallet)
[![Chat](https://img.shields.io/gitter/room/grin_community/Lobby.svg)](https://gitter.im/grin_community/Lobby)
[![Support](https://img.shields.io/badge/support-on%20gitter-brightgreen.svg)](https://gitter.im/grin_community/support)
[![](https://img.shields.io/badge/dynamic/json.svg?label=docs&uri=https%3A%2F%2Fcrates.io%2Fapi%2Fv1%2Fcrates%2Fecho-wallet%2Fversions&query=%24.versions%5B0%5D.num&colorB=4F74A6)](https://docs.rs/releases/search?query=echo_wallet)
[![Release Version](https://img.shields.io/github/release/mimblewimble/echo-wallet.svg)](https://github.com/mimblewimble/echo-wallet/releases)
[![License](https://img.shields.io/github/license/mimblewimble/echo-wallet.svg)](https://github.com/mimblewimble/echo-wallet/blob/master/LICENSE)

## Overview

Echo Wallet serves as the official reference implementation for the [Echo blockchain](https://github.com/echo-project/echo-node). This comprehensive wallet solution comprises two primary components designed to meet the needs of both developers and end users.

## Components

### 1. Echo Wallet APIs
The core wallet APIs provide essential functionality for Echo community wallet developers. These APIs can be:
- **Directly integrated** into other projects as a library
- **Accessed remotely** through a JSON-RPC interface

### 2. Command-Line Reference Wallet
A fully functional command-line wallet that serves as:
- A **baseline implementation** for the Echo ecosystem
- A **demonstration platform** showcasing proper API integration patterns
- A **production-ready tool** for users who prefer command-line interfaces

## Getting Started

### Installation
For the best experience, download the latest stable release from our [Releases page](https://github.com/echo-project/echo-wallet/releases). We provide pre-built distributions for:
- **Linux** (various distributions)
- **macOS** (Intel and Apple Silicon)
- **Windows** (x64)

### Documentation
Comprehensive user documentation is available on the [Echo Wiki](https://github.com/echo-project/docs/wiki/Wallet-User-Guide), covering:
- Installation procedures
- Configuration options
- Transaction management
- Security best practices
- Troubleshooting guides

## Development

This project welcomes contributions from the Echo community. The codebase is structured to provide clear separation between the core wallet functionality and the command-line interface, making it easy for developers to understand and extend.

## License

This project is licensed under the **Apache License v2.0** - see the [LICENSE](https://github.com/echo-project/echo-wallet/blob/main/LICENSE) file for details.

## Community

- **Chat**: Join our [Gitter community](https://gitter.im/echo-community/Lobby)
- **Support**: Get help on our [support channel](https://gitter.im/echo-community/support)
- **Documentation**: Browse our [API documentation](https://docs.rs/releases/search?query=echo_wallet)

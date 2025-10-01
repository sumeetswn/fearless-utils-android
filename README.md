# fearless-utils-android

Android utility library for cryptographic operations, blockchain interactions, and more.

## Installation

Add JitPack repository to your project's `build.gradle`:

```gradle
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

Add the dependency to your module's `build.gradle`:

```gradle
dependencies {
    implementation 'com.github.sumeetswn:fearless-utils-android:1.8.0'
}
```

## Features

- **Cryptographic Operations**: BouncyCastle and EdDSA support
- **BIP39 Mnemonic**: Secure mnemonic phrase generation and handling
- **Web3 Integration**: Ethereum and blockchain utilities
- **WebSocket Client**: Real-time communication support
- **SVG Rendering**: Android SVG support
- **Data Compression**: LZ4 compression utilities
- **Coroutines Support**: Built with Kotlin coroutines for async operations

## Dependencies

This library includes the following key dependencies:

- Kotlin 1.8.20
- BouncyCastle 1.65
- EdDSA 0.3.0
- Web3j Crypto 4.8.0
- BIP39 (NovaCrypto)
- Kotlinx Coroutines 1.6.4
- Kotlinx Serialization 1.5.0
- Gson 2.10.1
- WebSocket Client 2.14

## Requirements

- Android SDK
- Kotlin 1.8.20 or higher

## License

See LICENSE file for details.

## Version

Current version: **1.8.0**

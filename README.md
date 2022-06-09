The Binance Chain JavaScript SDK allows browsers and Node.js clients to interact
with Binance Chain. It includes the following core components.

- **crypto** - core cryptographic functions.
- **amino** -
  [amino](https://github.com/binance-chain/docs-site/blob/master/docs/encoding.md)
  (protobuf-like) encoding and decoding of transactions.
- **client** - implementations of Binance Chain transaction types, such as for
  transfers and trading.
- **accounts** - management of "accounts" and wallets, including seed and
  encrypted mnemonic generation.
- **rpc** - Node RPC client.
- **transaction** - Transaction Class, build and sign.

You can find more detailed documentation and examples in our
[Documentation](https://github.com/binance-chain/javascript-sdk/blob/master/docs/README.md)
pages.

## Installation

```bash
$ npm i @binance-chain/javascript-sdk
# Or:
$ yarn add @binance-chain/javascript-sdk
```

### Prerequisites

- **Windows users:** Please install
  [windows-build-tools](https://www.npmjs.com/package/windows-build-tools)
  first.

- **Mac users:** Make sure XCode Command Line Tools are installed:
  `xcode-select --install`.

## Testing

All new code changes should be covered with unit tests. You can run the tests
with the following command:

```bash
$ yarn test
```

## Contributing

Contributions to the Binance Chain JavaScript SDK are welcome. Please ensure
that you have tested the changes with a local client and have added unit test
coverage for your code.

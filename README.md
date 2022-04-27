# femplate • [![tests](https://github.com/abrandec/femplate/actions/workflows/tests.yml/badge.svg)](https://github.com/abrandec/femplate/actions/workflows/tests.yml) [![lints](https://github.com/abrandec/femplate/actions/workflows/lints.yml/badge.svg)](https://github.com/abrandec/femplate/actions/workflows/lints.yml) ![GitHub](https://img.shields.io/github/license/abrandec/femplate)  ![GitHub package.json version](https://img.shields.io/github/package-json/v/abrandec/femplate)

## Getting Started
```sh
forge install
```

## Blueprint

```ml
lib
├─ ds-test — https://github.com/dapphub/ds-test
├─ forge-std — https://github.com/brockelmore/forge-std
├─ solmate — https://github.com/Rari-Capital/solmate
├─ clones-with-immutable-args — https://github.com/wighawag/clones-with-immutable-args
src
├─ tests
│  └─ Greeter.t — "Greeter Tests"
└─ Greeter — "A Minimal Greeter Contract"
```

## Development

**Setup**
```bash
make
# OR #
make setup
```

**Building**
```bash
make build
```

**Testing**
```bash
make test
```

## License

[AGPL-3.0-only](https://github.com/abigger87/femplate/blob/master/LICENSE)

## Acknowledgements

- [femplate](https://github.com/abigger87/femplate)

## Disclaimer

_These smart contracts are being provided as is. No guarantee, representation or warranty is being made, express or implied, as to the safety or correctness of the user interface or the smart contracts. They have not been audited and as such there can be no assurance they will work as intended, and users may experience delays, failures, errors, omissions, loss of transmitted information or loss of funds. The creators are not liable for any of the foregoing. Users should proceed with caution and use at their own risk._

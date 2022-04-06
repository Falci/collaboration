# TBD Collaboration Repository

This repository is the welcoming point to TBD's open source efforts. It outlines 
the tbDEX Protocol, Decentralized Web Platform, and the components which comprise them. 

This repository is not a source forge, but a sync point for TBD projects. It's
used for documentation, issues, and discussions that span our software.

## Systems

The tbDEX Protocol is the center of our work. It allows users to transact
with financial institutions - without a central authority. Users can 
exchange fiat and crypto with providers who plug into the system. 

The Decentralized Web Platform is the architecture which makes this possible. It provides
the complex transport and identity systems necessary for parties to transact with one
another.

Together, these two systems open up a world of possibility for currency and information
exchange. And they return ownership of data where we believe it belongs:
with the user.

[INSERT IMAGE of COMPONENTS in the system here]
@csuwildcat - https://github.com/TBD54566975/collaboration/issues/27

### tbDEX

The `tbDEX` Protocol was first described in a [whitepaper](https://tbdex.io/whitepaper.pdf)
in November 2021. From its abstract:

```
tbDEX is a protocol for discovering liquidity and exchanging assets (such as bitcoin, fiat money, or real world goods) when the existence of social trust is an intractable element of managing transaction risk. The tbDEX protocol facilitates decentralized networks of exchange between assets by providing a framework for establishing social trust, utilizing decentralized identity (DID) and verifiable credentials (VCs) to establish the provenance of identity in the real world. The protocol has no opinion on anonymity as a feature or consequence of transactions. Instead, it allows willing counterparties to negotiate and establish the minimum information acceptable for the exchange. Moreover, it provides the infrastructure necessary to create a ubiquity of on-ramps and off-ramps directly between the fiat and crypto financial systems without the need for centralized intermediaries and trust brokers. This makes crypto assets and decentralized financial services more accessible to everyone.
```

The source for the `tbDEX` whitepaper is [here](https://github.com/TBD54566975/tbdex-whitepaper).

The [`tbdex-protocol` repository](https://github.com/TBD54566975/tbdex-protocol) is where
this work is housed. It describes the message formats/schemas used to transact. And it also
contains a preliminary mock implementation a PFI (Primary Financial Institution) may 
implement when it plugs into the system.

Looking forward, the work done here may be split into separate repositories. For now it's 
faster to couple the message formats, libraries, and mock implementation together until
the APIs harden.

## Contribution

The [contribution guide](./CONTRIBUTING.md) welcomes contributors with resources to get involved.

## Projects

| Project                                                  | Description                                                                    |
| -------------------------------------------------------- | ------------------------------------------------------------------------------ |
| [`ssi-sdk`](https://github.com/TBD54566975/ssi-sdk)     | The ssi-sdk provides a set of standards-based primitives for building decentralized identity applications. |
| [`developer-site`](https://github.com/TBD54566975/developer-site)     | Temporary developer site containing orienting resources to those looking to contribute to or work for TBD. |
| [`dwn-sdk-js`](https://github.com/TBD54566975/dwn-sdk-js)     | Reference implementation of Decentralized Web Nodes as per the [specification](https://identity.foundation/decentralized-web-node/spec/). |
| [`tbd-project-template`](https://github.com/TBD54566975/tbd-project-template)     | A template repository to create new projects with Governance, Licensing, and Code of Conduct |
| [`tbdex-protocol`](https://github.com/TBD54566975/tbdex-protocol)     | `tbDEX` message formats, libraries, and a mock PFI implementation showing how these may be used |
| [`ssi-service`](https://github.com/TBD54566975/ssi-service)     | Self-Sovereign Identity service |

## Project Resources

| Resource                                   | Description                                                                    |
| ------------------------------------------ | ------------------------------------------------------------------------------ |
| [CODEOWNERS](./CODEOWNERS)                 | Outlines the project lead(s)                                                   |
| [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) | Expected behavior for project contributors, promoting a welcoming environment |
| [CONTRIBUTING.md](./CONTRIBUTING.md)       | Developer guide to build, test, run, access CI, chat, discuss, file issues     |
| [GOVERNANCE.md](./GOVERNANCE.md)           | Project governance                                                             |
| [LICENSE](./LICENSE)                       | Apache License, Version 2.0                                                    |

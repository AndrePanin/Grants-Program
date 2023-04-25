# Gear's AssemblyScript library for Substrate-based blockchains

- **Team Name:** Gear Technologies
- **Payment Address:** TBD
- **[Level](https://github.com/w3f/Grants-Program/tree/master#level_slider-levels):** 2 ???
![img](https://github.com/gear-tech/gear/raw/master/images/title-grey.png)

## Project Overview :page_facing_up:

AssemblyScript is a programming language that allows developers to write smart contracts for blockchain networks using a syntax that is similar to TypeScript. The Gear's AssemblyScript library is a tool that enables developers to write smart contracts in AssemblyScript that can be executed on blockchain networks powered by Gear Protocol as well as other Substrate-based networks.

### Overview

The Gear's AssemblyScript library provides several functional capabilities for implementing smart contracts, including:

1. Type-Safe Contract Development: AssemblyScript library provides strong typing and compile-time checks for the contracts. It ensures that the contracts' functions and variables are of the correct type and can help catch errors early in the development process.

2. Interaction with Gear Networks: AssemblyScript library allows smart contracts to interact with the networks powered by Gear Protocol by providing a set of pre-built functions similar to Gear's Rust [`gstd`](https://github.com/gear-tech/gear/tree/master/gstd) library, allowing developers to access and use Gear's native functions and data structures.

3. Cross-Chain Compatibility: AssemblyScript library can be used to write smart contracts that can run on multiple Substrate-based blockchain networks, including the [Vara Network](https://vara-network.io/). This cross-chain compatibility allows for greater flexibility in the deployment and execution of smart contracts.

4. Low-Level Access: AssemblyScript library provides low-level access to the blockchain, allowing developers to directly interact with the blockchain's data structures and perform complex operations.

5. Efficient Execution: AssemblyScript library is designed to be efficient and can be compiled to WebAssembly, which is a low-level bytecode that is optimized for performance. This efficiency allows smart contracts written in AssemblyScript to execute quickly and with low gas fees.

### Project Details

1. We will produce a set of AssemblyScript functions using lower level abstractions for general interation with any Substrate-based network:
    1. General AssemblyScript library for interacting with any Substrate-based network. It will be a library that provides all the necessary and sufficient functions and methods for developing smart-contracts in accordance to of Gear Protocol's Actor model and other protocol's features.
    2. A separate AssemblyScript library implementing Parity SCALE codec. Such a libary can be used by any other one exposing their custom API surface for working with Substrate based network bypassing the library described in p 1.1. The codec can be used for any other communications not necessary related to blockchain. There is an implementation by [LimeChain](https://github.com/LimeChain/as-scale-codec/tree/master)).

### Ecosystem Fit

Overall, the AssemblyScript library is a powerful tool that enables developers to write smart contracts for blockchain networks powered by Gear Protocol as well as other Substrate-based networks. With its type-safe development, interaction with Gear Node's runtime, cross-chain compatibility, low-level access, and efficient execution, it provides a robust framework for building decentralized applications on these networks.

## Team :busts_in_silhouette:

### Team members

- Dmitry Osipov ([osipov-mit](https://github.com/osipov-mit))

### Contact

- **Contact Name:** Dmitry Osipov
- **Contact Email:** dm.osipov@gear-tech.io
- **Website:** https://www.gear-tech.io

### Legal Structure

- **Registered Address:** TBD _Address of your registered legal entity, if available. Please keep it in a single line. (e.g. High Street 1, London LK1 234, UK)_
- **Registered Legal Entity:** DevCo

### Team's experience

The Gear team consists of engineers with vast experience in implementing open source projects, as well as experience in implementing complex and high-load systems.

### Team Code Repos

- https://github.com/gear-tech
- https://github.com/gear-dapps
- https://github.com/osipov-mit

## Development Roadmap :nut_and_bolt:

### Overview

- **Total Estimated Duration:** 1 month
- **Full-Time Equivalent (FTE):** 1 FTE
- **Total Costs:** 10,000 USD

### Milestone 1 — Basic functionality

- **Estimated duration:** 1 month
- **FTE:**  1
- **Costs:** 10,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.) |
| 1. | Library: assemblyscript-scale-codec | We will deliver an Assemblyscript library that will implement SCALE codec to encode and decode data. |
| 2. | Library: gstd | We will deliver an Assemblyscript library that will enable functionality to write smart-contracts on Gear |

## Future Plans

Anyone can use the proposed solution to implement decentralized applciations running in Substrate blockchains.

Furhter plans to implement a dApp examples on AssemblyScript that utilize considering Gear specifics - Actor model for message communications etc.

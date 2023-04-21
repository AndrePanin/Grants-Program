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
  2. A separate AssemblyScript library implementing Parity SCALE codec. Apparently there is no any at the moment (actually there is an implementation by [LimeChain](https://github.com/LimeChain/as-scale-codec/tree/master)). Such a libary can be used by any other one exposing their custom API surface for working with Substrate based network bypassing the library described in p 1.1. The codec can be used for any other communications not necessary related to blockchain.

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

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/osipov-mit

### Team LinkedIn Profiles (if available)

- TBD

## Development Roadmap :nut_and_bolt: - TBD

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/Support%20Docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.

> :exclamation: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview

- **Total Estimated Duration:** _Duration of the whole project_ - 2 months ???
- **Full-Time Equivalent (FTE):**  _Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)_ - 1 FTE ???
- **Total Costs:** _Requested amount in USD for the whole project (e.g. 12,000 USD). Note that the acceptance criteria and additional benefits vary depending on the [level](../README.md#level_slider-levels) of funding requested. This and the costs for each milestone need to be provided in USD; if the grant is paid out in Bitcoin, the amount will be calculated according to the exchange rate at the time of payment._ - ???

### Milestone 1 Example — Basic functionality

- **Estimated duration:** 1 month
- **FTE:**  1,5
- **Costs:** 8,000 USD

> :exclamation: **The default deliverables 0a-0d below are mandatory for all milestones**, and deliverable 0e at least for the last one. 

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.) |
| 1. | Library: assemblyscript-scale-codec | We will deliver an Assemblyscript library that will implement SCALE codec to encode and decode data. |
| 2. | Library: gstd | We will deliver an Assemblyscript library that will enable functionality to write smart-contracts on Gear |


### Milestone 2 Example — Additional features

- **Estimated Duration:** 1 month
- **FTE:**  1,5
- **Costs:** 8,000 USD

...

## Future Plans

Anyone can use the proposed solution to implement decentralized applciations running in Substrate blockchains.

Furhter plans to implement a dApp examples on AssemblyScript that utilize considering Gear specifics - Actor model for message communications etc.

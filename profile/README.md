# Drosera Network

![Drosera Banner](DroseraHeader.jpeg)

**Creating a EVM native and decentralized agent layer**

At Drosera, we are building a decentralized agent layer for the EVM that enables developers to create **Traps**—smart contracts that monitor on-chain data and trigger automated on-chain responses. 

By leveraging the **Drosera Protocol** and a network of **Operators**, we aim to provide a scalable, trustless framework for:

* DeFi security

* General automation 

* Cost efficient Dapps.

## Why Drosera?

* Ethereum-Native – Built for seamless integration with the EVM and EigenLayer’s restaking.

* Trustless & Decentralized – No single point of control; Operators and Traps work together to enforce security.

* Developer-Friendly – Simple APIs, Foundry templates, and open-source tooling for easy adoption.

* Community-Driven – Build, share, and innovate alongside a passionate developer community.

## Key Components of Drosera

* Traps
* Operators


**Traps**

Traps are smart contracts that listen for on-chain events and respond automatically. 
Each Trap consists of:

* Trigger – Defines what condition or data point to monitor.

* Action – Specifies what on-chain response to execute.

* Condition – Optional logic to refine execution.

Example Traps:

Detect treasury drains and execute emergency responses.

Monitor low collateralization ratios and send liquidation alerts.

Watch for unusual trading activity on DEXs.


**Operators**

Operators run Drosera nodes, executing Trap logic in a decentralized manner. Operators earn rewards for securing and maintaining the network.
    
    
# Key Repositories

Explore our open-source projects to start building with Drosera:

| Repo | Details |
|--------|------------|
| **drosera-network/examples**<br>[GitHub Link](https://github.com/drosera-network/examples) | A collection of example Drosera Traps in Solidity, showcasing how to detect incidents (e.g., balance drops, liquidity issues) and integrate with the Drosera Protocol. Perfect for developers learning Trap creation!<br>![GitHub stars](https://img.shields.io/github/stars/drosera-network/examples?style=social) |
| **drosera-network/trap-foundry-template**<br>[GitHub Link](https://github.com/drosera-network/trap-foundry-template) | A Foundry template to kickstart your Drosera Trap development. Run `forge init -t drosera-network/trap-foundry-template` to set up a new project.<br>![GitHub stars](https://img.shields.io/github/stars/drosera-network/trap-foundry-template?style=social) |
| **drosera-network/releases**<br>[GitHub Link](https://github.com/drosera-network/releases) | Official releases for the Drosera CLI and Nodes (e.g., v1.19.0). Download and run Operator nodes to execute Traps and earn rewards.<br>![GitHub release](https://img.shields.io/github/v/release/drosera-network/releases) |
| **drosera-network/erc7579-trap-integration-poc**<br>[GitHub Link](https://github.com/drosera-network/erc-7579-trap-wallet-integration-pocp) | Our PoC for integrating smart contract accounts with traps to enable autonomous wallets. |


## Developer Resources

Get started with Drosera’s developer-friendly tools and documentation:

- **[Developer Docs](https://dev.drosera.io)**  
  Comprehensive guides on running Drosera Operator nodes, creating Traps, and integrating with the Drosera Protocol.

- **[Getting Started](https://dev.drosera.io/trappers/getting-started)**  
  Learn how to set up a Drosera project using our Foundry template or run an Operator node with Docker.

- **[Trap Anatomy](https://dev.drosera.io/trappers/creating-a-trap)**  
  Trap creation guide and description of the Trap lifecycle, including how to define triggers, actions, and conditions.

- **[Trap Examples](https://github.com/drosera-network/examples)**  
  Reference implementations for monitoring treasury drains, collateralization ratios, and unusual trading activity.

## Use Cases
Drosera empowers developers to build powerful automation and security applications:

* Treasury Management – Detect unauthorized transfers and trigger failsafes.

* Lending Protocols – Monitor collateralization ratios and automate liquidation alerts.

* Decentralized Exchanges – Detect unusual trading activity or price manipulation.

* Time-Series Analysis – Identify historical patterns like vesting schedules or risk indicators.


## Drosera Dapps

Check out our Dapps that leverage the Drosera Protocol for automation and cost effeciency:

- **♟️ [Chess](https://chess.drosera.io)**  
- **[Notaassino](https://notacasino.drosera.io/roulette)**
- More coming soon

## Community & Contribution

Join the Drosera community to build the future of decentralized automation:

[Discord](https://discord.gg/drosera)

Connect with developers, Operators, and the Drosera team for support and collaboration

We have four path at Drosera:

* The Writers path - They write Threads, Articles, Contents and Research for Drosera

* The Artist path - They create lovely, stunning and crazy arts for Drosera

* The Trappers path - They create **Traps** that serves a use case and run nodes

* The keepers path - They educate users about Drosera

[Follow us on X](https://x.com/DroseraNetwork)

Stay updated on news, releases, and testnet events.
 
[Drosera Trappersphere](https://x.com/i/communities/1914716154712461738)

Our very own X community

[Website](https://drosera.io)

Learn more about our mission and roadmap.

**Want to contribute?**

Create and share new Trap examples in our [examples repo](https://github.com/drosera-network/examples). The Drosera team reviews and provides feedback to build a robust library for the community.

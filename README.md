# SOFIE Framework

The SOFIE Framework is an example implementation of the SOFIE Federation Architecture developed by the [SOFIE Project](https://www.sofie-iot.eu). The Framework consists of 6 components and federation adapters:

* [Interledger](https://github.com/SOFIE-project/Interledger) supports secure federation by enabling atomic transactions spanning two or more ledgers, and multiple examples demonstrate how the component can be utilised for different types of application. Different ledger types including Ethereum and Hyperledger Fabric are already supported and new ones can be easily added.

* [Identity, Authentication and Authorisation](https://github.com/SOFIE-project/identity-authentication-authorization) can be used to secure any HTTP-based resource: the component acts as an HTTP forward proxy and supports multiple access tokens including including Decentralized Identifiers (DIDs) and Verifiable Credentials (VCs), and JWT tokens.

* [Privacy and Data Sovereignty](https://github.com/SOFIE-project/Privacy-and-Data-Sovereignty) extends OAuth 2.0 to support additional authorisation grants including DIDs and VCs and blockchain-based tokens. It also implements privacy preserving surveys using differential privacy.

* [Semantic Representation](https://github.com/SOFIE-project/Semantic-Representation) enables interoperability between different IoT devices, services, and data by describing what functions they provide and what interfaces and formats they utilise. It supports defining and validating data models using JSON schemas and W3C WoT Thin Descriptions.

* [Marketplace](https://github.com/SOFIE-project/Marketplace) allows participants to trade resources by placing bids and offers in a secure, auditable, and decentralised way. It supports different pricing models and covers the whole trade process from offer creation to payment and verification of receipt of the traded item.

* [Provisioning and Discovery](https://github.com/SOFIE-project/Discovery-and-Provisioning) manages the IoT resources in the system by provisioning the existing IoT devices to a working state and by enabling the discovery of new IoT resources along with their metadata.

* Finally, IoT system specific [Federation Adapters](https://github.com/SOFIE-project/Federation-Adapters) connect the IoT systems to the SOFIE Framework without requiring any changes to the systems themselves.

Individual component repositories contain examples of using that component, and the following example show multiple components can be jointly utilised:
* [Secure Marketplace for Access to Ubiquitous Goods (SMAUG)](https://github.com/SOFIE-project/SMAUG-Deployment) creates a decentralized and open marketplace where smart locker owners can put smart lockers for rent, and interested renters can purchase access to those smart lockers for limited amounts of time. It utilises *all Framework components*.
* [Scavenger Hunt](https://github.com/SOFIE-project/ScavengerHunt) is a location-based game utilising BLE beacons.

More information about the SOFIE Framework can be found in the *SOFIE deliverable D2.7*, while the underlying Architecture is described in the *SOFIE Deliverable D2.6*. Both are available on the [SOFIE Deliverables page](https://www.sofie-iot.eu/results/project-deliverables).

The SOFIE framework is licensed under Apache License 2.0. For any issues with the Framework, please, use GitHub’s issue mechanism, and for any questions  any question or comments about the Framework as a whole, please, drop us a message at *framework (at) sofie-iot.eu*!

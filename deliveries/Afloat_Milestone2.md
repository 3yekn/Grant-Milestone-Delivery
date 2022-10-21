# Milestone Delivery :mailbox:

**The [invoice form :pencil:](https://docs.google.com/forms/d/e/1FAIpQLSfmNYaoCgrxyhzgoKQ0ynQvnNRoTmgApz9NrMp-hd8mhIiO0A/viewform) has been filled out correctly for this milestone, and the delivery is according to the official [milestone delivery guidelines](https://github.com/w3f/Grants-Program/blob/master/docs/milestone-deliverables-guidelines.md).**  

* **Application Document:** https://github.com/w3f/Grants-Program/blob/master/applications/Afloat.md
* **Milestone Number:** 2

**Context** (optional)

A running instance of the code can be found [here](https://portal-dev.hashed.systems)

**Deliverables**

| Number | Deliverable | Link | Notes |
| -----: | ----------- | ------------- | ------------------- |
| 0a. | License | https://github.com/hashed-io/hashed-substrate/blob/main/LICENSE | MIT |
| 0b. | Documentation | See list of repos below for inline documentation, or [Hashed Network Runtime Documetation](https://hashed-io.github.io/hashed-substrate/hashed_runtime/index.html) |  |
| 0c. | Testing | https://github.com/hashed-io/hashed-substrate/blob/main/pallets/gated-marketplace/src/tests.rs | The tests are built directly into the corresponding Rust and Javascript projects |
| 0d. | Video | [English](https://youtu.be/dpFk2d0UXYc) and [Spanish](Afloat_Milestone2.md) versions | Explainer of features, context, and demonstration |
| 0e. | Article | [English](Afloat_Milestone2.md) and [Spanish](https://docs.google.com/document/d/1DNHgONQrZfpG4f0f79n6pS9h9jUQQDW52OlWCw1TiJA/edit?usp=sharing) versions | Afloat's and general use case of gated Marketplaces |
| 1. | Originate Tax Credit | [JS library](https://github.com/hashed-io/afloat-client-api/blob/master/src/model/polkadot-pallets/afloatApi.js#L34) [Pallet](https://github.com/hashed-io/hashed-substrate/blob/develop/pallets/fruniques/src/lib.rs#L177) | This video provides a demonstration and explainer for how new tax credit NFTs are being originated: [Youtube Video](https://youtu.be/dpFk2d0UXYc) | 
| 2. | Upload Confidential Documents | [JS library](https://github.com/hashed-io/hashed-confidential-docs-client-api/blob/015b59837eb8c0117fecb0c6323053d605a6f5fd/src/model/OwnedData.js#L57) | This feature allows for NFT originators to upload encrypted files attached to tax credits. The files will be accessible only by the user and the application administrator. This is also explained in the [video](https://youtu.be/dpFk2d0UXYc) | 
| 3. | Tax Credit verification | n/a | This functionality requires access to confidential data not accessible in the pallet. Instead, it should go on the client or client/market/dapp-specific services/oracle that can do the verifications. (Similar to Twitter/Email/Matrix verifications using the Identity pallet) |
| 4. | List for Sale | [JS Documentation](https://github.com/hashed-io/hashed-substrate/tree/main/pallets/gated-marketplace#put-an-asset-on-sale-1)  [Pallet](https://github.com/hashed-io/hashed-substrate/blob/main/pallets/gated-marketplace/src/lib.rs#L531) | Ability for Tax Credit (NFT) owners to assign a price and list it for sale.| 

**Repositories** 
(all MIT licensed)
| Component | Repo | Language |
| -----: | ----------- | ------- |
| Hashed Network | https://github.com/hashed-io/hashed-substrate | Substrate |
| Marketplace UI | https://github.com/hashed-io/hashed-network-portal-ui | Quasar/Vue |
| Marketplace pallets | https://github.com/hashed-io/hashed-substrate/tree/develop/pallets/gated-marketplace | Rust |
| Marketplace JS Library | https://github.com/hashed-io/marketplace-client-api | Javascript |
| Confidential Documents Server | https://github.com/hashed-io/hashed-private-server | Javascript |
| Confidential Documents API | https://github.com/hashed-io/hashed-confidential-docs-client-api | Javascript |



**Additional Information**


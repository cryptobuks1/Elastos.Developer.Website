

## Migration Notes by ClarenceL

_By default paths and names are referenced to old content in the `old` folder_

### User Personas

Roughly I am dividing users into 5 categories:

1. Build - people with a project in mind, "know Elastos basically" and want to get building 
2. Learn - people who want to know how Elastos works
3. Discover - people looking to "explore" the ecosystem and see what we have
4. Resources - someone who is "already developing" and needs to look up an API method, etc
5. FAQ - for people with questions, everything else (I broke from consistency here and put roadmap here instead of resources because I wanted it to be more prominent)

### A few notes

- We should not use the developer website to "sell" Elastos, if they are on the site already willing to learn, build or contribute we should focus on giving them the answers they are looking for. Other avenues can do the selling; therefore I have removed very content-heavy pages such as Elastos vs Competitors, Use-Cases, etc.

- No blank pages! Use `{{> redirect href="[URL]" <}}` to redirect blank pages to the first sub-page or use the hero boxes to create links for all the sub-pages. **Blank pages are an extra click and very jarring!**

#### Discover -> Learn

- [ ] What is Elastos? - Ignored, partially out of date info, better to use new Whitepaper content
- [ ] The Smart Web - Ignored, use new write-up by Alex in new Whitepaper -> NEW `/learn/vision`
- [ ] Development History - Ignored, out-of-date, need a new roadmap
- [x] Whitepapers - Copied Over
- [x] Roadmap - Moved to FAQ & Roadmap 
- [ ] Elastos vs Competitors - Removed, this is too word heavy and doesn't really belong in a Developer website
- [x] Business Use-Cases - I'll leave this in to beef up the content but it is out of date, it will be elastOS and later on digital capsules
- [x] Architecture - migrated sans the "Types of Apps on Elastos" 

##### Discover / Elastos core modules

- [ ] ELA main chain - merged part of this (the utility part) into the new `learn/elastos_blockchain`
- [ ] Ethereum Sidechain - removed, many items were outdated and the stats were off-point. I opted to go for the more recent write-up from the 2020 Internal Whitepaper.
- [ ] NEO Sidechain - removed, no longer important
- [ ] Token Sidechain - removed, no longer important
- [x] Wallets -> moved to "new" `Discover`
- [ ] Carrier - kept this, but it really needs an update, right now it's just a wall of text - TODO
- [ ] Hive - same as above, more or less a wall of text
- [x] elastOS - kept this, but it could be much more concise

#### Get Started

Fully removed, we should not confuse developers and expect them to run or interact with a local Elastos blockchain

#### Elastos Blockchain

- [ ] FAQ - removed, no content

#### Elastos Core Services / Samples & Demos

- [x] C / C++ Samples - ALL CARRIER RELATED - migrated to new `/services/carrier/demos`
- [x] Android Samples - ALL CARRIER RELATED - migrated to new `/services/carrier/demos`
- [x] iOS Samples - ALL CARRIER RELATED - migrated to new `/services/carrier/demos`
- [x] elastOS Samples - - migrated to new `/build/elastOS/demos`


#### Elastos Core Services / Guides

- [ ] Guides overview - can be improved
- [ ] Elastos scheme - REMOVED, this seems like an intro to the elastOS scheme? Examples are not done and it says it only works with the Elaphant wallet?
- [ ] Digital identities - REMOVED, not done, this is only TODOs
- [ ] Payments - REMOVED, not done, this is only TODOs
- [x] Data storage - migrated to new `/services/hive/guide`
- [x] Carrier networking - migrated to new `/services/carrier/guides`
- [x] Ethereum Smart Contracts - migrated to new `/services/eth_sidechain/guides` - but it's a bit out of date
- [ ] Token sidechain - REMOVED, no longer in development

#### Elastos Core Services / Reference

- [x] Android Kotlin / Carrier API - migrated to `/resources/APIs/Elastos Carrier`
- [x] Android Kotlin / Hive API - migrated to `/resources/APIs/Elastos Hive`
- [x] iOS Swift / Carrier API - migrated to `/resources/APIs/Elastos Carrier`
- [x] iOS Swift / Hive API - migrated to `/resources/APIs/Elastos Hive`
- [x] elastOS / elastOS Plugins API - migrated to `/resources/APIs/elastOS`
- [x] C++ / Carrier API - migrated to `/resources/APIs/Elastos Carrier`
- [x] C++ / Hive API - migrated to `/resources/APIs/Elastos Hive`
- [x] C++ / ELA Mainchain REST API - migrated to `/resources/APIs/Blockchains`
- [x] C++ / ELA Mainchain RPC API - migrated to `/resources/APIs/Blockchains`
- [x] SPV Wallet API - migrated to `/resources/APIs/Blockchains/SPV Wallet API`
- [x] Elastos scheme - migrated to `/build/elastos/elastos_scheme/`

#### Elastos Core Services / Reference
Migrated to FAQ & Roadmap Main Section / FAQs

#### Contributing

- [x] Contributing - `contribute/contributing` - renamed to "How to Contribute"
- [ ] Why Contribute? - Removed, EBP no longer active, mostly irrelevant
- [x] Contribution Guide Index - ADDED
- [ ] Modules List - Still has a TODO in there
- [ ] Send Suggestions - Missing Review! Included for now due to relevant content
- [ ] Modules development - Removed, content not completed - TODO
- [ ] Site Projects - Removed, some parts re-used in Discover

#### Learn

- [ ] Elastos DID Fees - `discover_elastos/core_modules/elastos_did` 

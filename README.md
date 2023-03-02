# Awesome Web3Knowledge

:cake: A collection of awesome knowledge about Web 3.0

## Classification

Throughout this list you'll find emojis next to resources, here's what each of them indicates:

:scroll:            Scientific paper

:books:             Course, long series or complete series

:bomb:              Collection of valuable resources

:school:            A programming library

:file_folder:       Documentation

:computer:          Official Website

:green_book:        Specific, written tutorial

:video_camera:      Video tutorial

:dizzy:             Stellar resource, not from this earth

:mag:               Search

:bulb:              Utility

:moneybag:          Grant

:anchor:            Decentralized Institution

:newspaper:         News

:airplane:          Location

## Content

- [Web 3.0 Definitions](#web-3.0-definitions)
- [Cryptography](#cryptography)
  - [Number Theory Curves Fields](#number-theory-curves-fields)
  - [Elliptic Curves](#elliptic-curves)
  - [Hash Functions](#hash-functions)
  - [Pairings](#pairings)
  - [Commitment Schemes](#commitment-schemes)
  - [Accumulators](#accumulators)
  - [Merkle Trees](#merkle-trees)
  - [Universal Composability (UC) Model Security](#universal-composability-model-security)
  - [Threshold Cryptography](#threshold-cryptography)
- [Constraint Systems and Arithmetization](#constraint-systems-and-arithmetization)
  - [Rank1 Constraint System (R1CS) and Quadratic Arithmetic Programs (QAPs)](#rank1-constraint-system-and-quadratic-arithmetic-programs)
  - [PLONK Arithemtization](#plonk-arithemtization)
  - [Arithmetic Intermediate Representation (AIR)](#arithmetic-intermediate-representation)
- [Zero Knowledge](#zero-knowledge)
  - [Trusted Setup](#trusted-setup)
  - [Universal Setup](#universal-setup)
  - [Transparent-No Setup](#transparent-no-setup)
  - [Unsorted ZKP Systems](#unsorted-zkp-systems)
  - [Recursive Proofs](#recursive-proofs)
  - [Short-lived ZKPs](#short-lived-zkps)
  - [Zero-knowledge Proxy](#zero-knowledge-proxy)
  - [Multi-Verifier Proofs](#multi-verifier-proofs)
  - [Multi-Prover Proofs](#multi-prover-proofs)
  - [Designated-Verifier Proofs](#designated-verifier-proofs)
  - [Garbled Circuits](#garbled-circuits)
  - [Interactive Proofs based on VOLE](#interactive-proofs-based-on-vole)
  - [zk Virtual Machines](#zk-virtual-machines)
- [Decentralized Finance](#decentralized-finance)
  - [Ethereum](#ethereum)
  - [Smart Contract Security](#smart-contract-security)
  - [Arbitrage](#arbitrage)
  - [Confidential UTXO and Mixers](#confidential-utxo-and-mixers)
- [Decentralized Key Management](#decentralized-key-management)
  - [Wallets](#wallets)
- [Decentralized Identity](#decentralized-identity)
  - [Group Signatures](#group-signatures)
  - [Credential Systems](#credential-systems)
  - [Distributed Trust](#distributed-trust)
  - [Decentralized Oracles](#decentralized-oracles)
- [Side Chain Committees](#side-chain-committees)
  - [Cryptoeconomic Security](#cryptoeconomic-security)
- [Decentralized Data Management](#decentralized-data-management)
  - [Access Control](#access-control)
  - [Data Sharing](#data-sharing)
  - [Storage](#storage)
  - [Secret Management](#secret-management)
  - [Privacy](#privacy)
- [Secure Computation](#secure-computation)
  - [Multi Party Computation](#multi-party-computation)
  - [Homomorphic Encryption](#homomorphic-encryption)
  - [Trusted Execution Environments (TEEs)](#trusted-execution-environments)
- [Privacy-preserving Computation](#privacy-preserving-computation)
  - [Differential Privacy](#differential-privacy)
  - [Data Lineage](#data-lineage)
- [Decentralized Computation](#decentralized-computation)
  - [Blockchain-coordinated Computation](#blockchain-coordinated-computation)
    - [On-chain Computation](#on-chain-computation)
    - [Off-chain Computation](#off-chain-computation)
    - [Hybrid Computation](#hybrid-computation)
  - [Policy-compliant Computation](#policy-compliant-computation)
  - [User Centricity and Data Sovereignty](#user-centricity-and-data-sovereignty)
- [Systematizations of Knowledge (SoK)](#systematizations-of-knowledge)
- [Application Development](#application-development)
  - [Decentralized Programming](#decentralized-programming)
  - [Smart Contracts](#smart-contracts)
  - [Layer 2 and Bridges](#layer-2-and-bridges)
  - [Oracles](#oracles)
  - [Web 3.0 Identity](#web-3.0-identity)
  - [Frontend](#frontend)
  - [Standardization](#standardization)
  - [Tooling](#tooling)
  - [Cryptographic Libraries](#cryptographic-libraries)
  - [Trusted Enclaves](#trusted-enclaves)
  - [Zero Knowledge Proofs](#zero-knowledge-proofs)
- [Programming](#programming)
  - [Golang](#golang)
  - [Rust](#rust)
  - [Solidity](#solidity)
- [Research](#research)
  - [Paper Search](#paper-search)
  - [Education](#education)
  - [Researchers to follow by domain](#researchers-to-follow-by-domain)
  - [Conferences](#conferences)
  - [Grants](#grants)
  - [Scientific Writing](#scientific-writing)
- [Companies](#companies)
  - [Blockchain Development](#blockchain-development)
  - [Identity Management](#identity-management)
  - [Storage Network](#storage-network)
  - [Data Management](#data-management)
  - [Resolution](#resolution)
  - [Asset Management](#asset-management)
- [Blockchain Projects](#blockchain-projects)
- [News](#news)

---

## Web 3.0 Definitions & Overviews

- :bomb: [Blockchain Roadmap - Everything you need to know](https://roadmap.sh/blockchain)
- :green_book: [Blockchains, crypto, & web3: Connections, models, more](https://a16z.simplecast.com/episodes/blockchains-crypto-web3-connections-models-QRYQ9oIi), [all episodes](https://a16z.simplecast.com/episodes)
- :green_book: [Web5: The Decentralized Web Platform](https://developer.tbd.website/docs/Decentralized%20Web%20Platform%20-%20Public.pdf)
- :green_book: [What is Web5, Jack Dorsey’s latest idea?](https://medium.com/geekculture/what-is-web5-jack-dorseys-latest-idea-d40d3a2e4973)
- :green_book: [Web3 is Self-Certifying](https://jaygraber.medium.com/web3-is-self-certifying-9dad77fd8d81)
- :green_book: [Decentralized Identity: Passport to Web3](https://medium.com/amber-group/decentralized-identity-passport-to-web3-d3373479268a)


## Cryptography

- :dizzy: [A Graduate Course in Applied Cryptography (Dan Boneh)](http://toc.cryptobook.us/)
- :bomb: [Crypto Stackexchange](https://crypto.stackexchange.com)
- :green_book: [Cryptopals - Collection of challenges on basic cryptography](https://cryptopals.com/)
- :green_book: [Notes on Cryptography and Computer Security](https://docs.google.com/viewer?url=https://github.com/mahdiz/lecture-notes/raw/master/crypto/main.pdf)
- :video_camera: :dizzy: [ZK Hack - ZK Whiteboard sessions](https://zkhack.dev/whiteboard/module-one/)
- :green_book: [David Crypto Blog](https://www.cryptologie.net/)

### Number Theory Curves Fields

- :video_camera: [Finite Fields in Cryptography: Why and How](https://www.youtube.com/watch?v=ColSUxhpn6A)
- [explained-from-first-principles: Number theory](https://explained-from-first-principles.com/number-theory/)
- [introduction to mathematical cryptography](https://drive.google.com/drive/u/1/folders/1ILBHUZrDZDku3HfK1yyp6AbBD_F3nRm5)
- :green_book: [Explaining BLS12–381 … The “Zero Knowledge Proof” Curve](https://medium.com/asecuritysite-when-bob-met-alice/explaining-bls12-381-the-zero-knowledge-proof-curve-aa5eabec8261)

### Elliptic Curves

- :green_book: [Elliptic Curve Cryptography: a gentle introduction](https://andrea.corbellini.name/2015/05/17/elliptic-curve-cryptography-a-gentle-introduction/)
- :books: [BLS12-381 for the rest of us](https://hackmd.io/@benjaminion/bls12-381#BLS12-381-For-The-Rest-Of-Us)
- [Elliptic Curve Cryptography (ECC)](https://cryptobook.nakov.com/asymmetric-key-ciphers/elliptic-curve-cryptography-ecc)
- [A survey of elliptic curves for proof systems](https://eprint.iacr.org/2022/586.pdf)
- [The animated elliptic curve](https://curves.xargs.org/)
- [An Illustrated Guide to Elliptic Curve Cryptography Validation](https://research.nccgroup.com/2021/11/18/an-illustrated-guide-to-elliptic-curve-cryptography-validation/)
- :green_book: [Explaining BLS12–381 … The “Zero Knowledge Proof” Curve](https://medium.com/asecuritysite-when-bob-met-alice/explaining-bls12-381-the-zero-knowledge-proof-curve-aa5eabec8261)

### Hash Functions

- :video_camera: [6 4 Constructing compression functions 8 min](https://www.youtube.com/watch?v=QukLrvrnr3U)
- :video_camera: [SHA-256 | COMPLETE Step-By-Step Explanation (W/ Example)](https://www.youtube.com/watch?v=orIgy2MjqrA&list=LL&index=14)

### Pairings

- :video_camera: [Pairings in Cryptography](https://www.youtube.com/watch?v=8WDOpzxpnTE&t=3208s)
- [Pairings for beginners](http://infosec.pusan.ac.kr/wp-content/uploads/2019/09/Pairings-For-Beginners.pdf)
- :green_book: [Exploring Elliptic Curve Pairings](https://medium.com/@VitalikButerin/exploring-elliptic-curve-pairings-c73c1864e627)

### Commitment Schemes

- [Functional Commitment Schemes: From Polynomial Commitments to Pairing-Based Accumulators from Simple Assumptions](https://hal.inria.fr/hal-01306152/file/poly-commit.pdf)
- [Notes for Lecture 27](http://theory.stanford.edu/~trevisan/cs276/lecture27.pdf)
- [Penumbra Value Commitments](https://protocol.penumbra.zone/main/protocol/value_commitments.html)
- [Efficient Functional Commitments: How to Commit to a Private Function](https://eprint.iacr.org/2021/1342.pdf)
- [Polynomial Commitment with a One-to-Many Prover and Applications](https://www.usenix.org/system/files/sec22summer_zhang-jiaheng.pdf)
- [Commit-Chains: Secure, Scalable Off-Chain Payments](https://eprint.iacr.org/2018/642.pdf)
- :video_camera: [Lecture 10 Premiere: Privacy on the Blockchain](https://www.youtube.com/watch?v=H3GmsxRU1Kw)

### Accumulators

- :scroll: [Batching Techniques for Accumulators with Applications to IOPs and Stateless Blockchains](https://eprint.iacr.org/2018/1188.pdf)
- :scroll: [An Expressive (Zero-Knowledge) Set Accumulator](https://user.eng.umd.edu/~cpap/published/accumEUROSP2017.pdf)

### Merkle Trees

- :green_book: [Some ways to use ZK-SNARKs for privacy](https://vitalik.ca/general/2022/06/15/using_snarks.html)
- :green_book: [Accelerating Penumbra's Merkle Tree by up to 4,000,000x](https://penumbra.zone/blog/tiered-commitment-tree/)

### Universal Composability Model Security

- [Universally Composable Security: A New Paradigm for Cryptographic Protocols](https://eprint.iacr.org/2000/067.pdf)
- [Security and Composition of Multiparty Cryptographic Protocols](https://link.springer.com/content/pdf/10.1007/s001459910006.pdf)
- [Security and Composition of Cryptographic Protocols: A tutorial](http://cs.tau.ac.il/~canetti/materials/sp09-sem-lec9.pdf)
- [iUC: Flexible Universal Composability Made Simple](https://eprint.iacr.org/2019/1073.pdf)
- [Obtaining Universally Composable Security: Towards the Bare Bones of Trust](https://eprint.iacr.org/2007/475.pdf)
- [Security and composition of cryptographic protocols: a tutorial (part I)](https://dl.acm.org/doi/abs/10.1145/1165555.1165570)

### Threshold Cryptography

- :scroll: [Mithril: Stake-based Threshold Multisignatures](https://eprint.iacr.org/2021/916.pdf)
- :scroll: [Threshold Cryptography as a Service (in the Multiserver and YOSO Models)](https://eprint.iacr.org/2021/1290)
- :video_camera: [Fast Multiparty Threshold ECDSA with Fast Trustless Setup](https://www.youtube.com/watch?v=PdfDZIwuZm0&list=LL&index=71)

## Constraint Systems and Arithmetization

Arithmetization is a preliminary process that derives an alternative circuit representation that allows for a more efficient proof computation.
In general, the "backend" of a SNARK considers pre-processing and formatting of an arithmetic or boolean circuit.
The "frontend" of a SNARK describes the actual proof algorithm, which leverages the intermediate description emitted from the backend to efficiently prove & verify that a prover knows a specific witness that satisfies the circuit at hand.
Most proof algorithms make use of pairings, where a specific elliptic curve is leveraged to homomorphically compute circuit satisfiability without disclosing the witness of the prover in plain.

- :green_book: [Simple Explanations of Arithmetic Circuits and Zero-Knowledge Proofs](https://medium.com/web3studio/simple-explanations-of-arithmetic-circuits-and-zero-knowledge-proofs-806e59a79785)

### Rank1 Constraint System and Quadratic Arithmetic Programs
Important for pairing based SNARKs, such as Groth16.

- :green_book: [R1CS & QAP Overview](https://medium.com/@VitalikButerin/quadratic-arithmetic-programs-from-zero-to-hero-f6d558cea649)
- [R1CS & QAP Implementation Example](https://asecuritysite.com/zero/go_qap)
- [Paper on DIZK that includes a good description of Groth16, R1CS and QAP](https://eprint.iacr.org/2018/691.pdf)

### PLONK Arithemtization

- :green_book: [PLONK Arithmetization](https://hackmd.io/@jake/plonk-arithmetization)
- :books: [Halo2](https://zcash.github.io/halo2/concepts/)
- :video_camera: [ZK HACK mini - Introduction to Plonky2](https://www.youtube.com/watch?v=p77Av0sXKQ4)

### Arithmetic Intermediate Representation
Important for zkEVM execution of SNARKS.

## Zero Knowledge

- :dizzy: [Proofs, Arguments and Zero-Knowledge (Justin Thaler)](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.pdf)
- :bomb: [ZK Research](https://0xst.notion.site/ZK-Research-94ba836c3b2a4e2491a871364ee5b13b)
- :bomb: [ingopedia: A curated list of ZK resources and links.](https://github.com/ingonyama-zk/ingopedia)
- :video_camera: [CESC ZKP Workshop](https://www.youtube.com/watch?v=SzBDWyJ3X6U&list=PLS01nW3Rtgor2MjOJBJexhQ6ZKWs6uQw8)
- :green_book: [BLS12-381 For The Rest Of Us](https://hackmd.io/@benjaminion/bls12-381)
- :green_book: [zkSNARKs in a nutshell](https://blog.ethereum.org/2016/12/05/zksnarks-in-a-nutshell/)
- :green_book: [A Brief Dive Into zk-SNARKs and the ZoKrates Toolbox on the Ethereum Blockchain](https://medium.com/cornellblockchain/a-brief-dive-into-zk-snarks-and-the-zokrates-toolbox-on-the-ethereum-blockchain-cb7bd7f00fdc)
- :green_book: [Quadratic Arithmetic Programs: from Zero to Hero](https://medium.com/@VitalikButerin/quadratic-arithmetic-programs-from-zero-to-hero-f6d558cea649)
- :green_book: [Zk-SNARKs: Under the Hood](https://medium.com/@VitalikButerin/zk-snarks-under-the-hood-b33151a013f6)
- :green_book: [An approximate introduction to how zk-SNARKs are possible](https://vitalik.ca/general/2021/01/26/snarks.html)
- :green_book: [Demystifying Zero Knowledge Proofs](https://docs.google.com/presentation/d/1gfB6WZMvM9mmDKofFibIgsyYShdf0RV_Y8TLz3k1Ls0/edit#slide=id.g443f641f0b_1_338)
- :green_book: [What are zk-SNARKs?](https://z.cash/technology/zksnarks/)
- :green_book: [Zero-Knowledge Proofs: STARKs vs SNARKs](https://consensys.net/blog/blockchain-explained/zero-knowledge-proofs-starks-vs-snarks/)
- :scroll: [Non-Interactive Zero-Knowledge Proofs for Composite Statements](https://eprint.iacr.org/2018/557)
- :green_book: [Delendum.xyz: ZK in Identity](https://delendum.xyz/2022/07/26/zk-identity-systems.html)

### Trusted Setup

### Universal Setup

- :bomb: [Awesome-PLONK](https://github.com/fluidex/awesome-plonk/blob/main/README.md)
- :books: [Polynomial IOP PLONK - Introduction Dan Boneh](https://www.youtube.com/watch?v=vxyoPM2m7Yg)
- [PlonK: Permutations over Lagrange-bases for Oecumenical Noninteractive arguments of Knowledge](https://eprint.iacr.org/2019/953.pdf)

### Transparent-No Setup

- :green_book: [From Zero Knowledge to Bulletproofs](https://github.com/AdamISZ/from0k2bp/blob/master/from0k2bp.pdf)

### Unsorted ZKP Systems
Todo: Separate the below list and filter universal, trusted transparent setup, etc.

- [Hyperproofs: Aggregating and Maintaining Proofs in Vector Commitments](https://www.usenix.org/system/files/sec22fall_srinivasan.pdf)
- [SNARKBlock: Federated Anonymous Blocklisting from Hidden Common Input Aggregate Proofs](https://eprint.iacr.org/2021/1577.pdf)
- [Many-out-of-many Proofs](https://github.com/ConsenSys/anonymous-zether/blob/master/docs/AnonZether.pdf)
- [Zero-Knowledge for Homomorphic Key-Value Commitments with Applications to Privacy-Preserving Ledgers](https://eprint.iacr.org/2021/1678.pdf)
- [Zero-Knowledge Proofs on Secret-Shared Data via Fully Linear PCPs](https://eprint.iacr.org/2019/188.pdf)
- [Proof of Replication](https://research.filecoin.io/assets/proof-of-replication.pdf)
- [Sealed-Glass Proofs: Using Transparent Enclaves to Prove and Sell Knowledge](https://eprint.iacr.org/2016/635.pdf)
- [ZoKrates - Scalable Privacy-Preserving Off-Chain Computations](https://www.ise.tu-berlin.de/fileadmin/fg308/publications/2018/2018_eberhardt_ZoKrates.pdf)
- [LegoSNARK: Modular Design and Composition of Succinct Zero-Knowledge Proofs](https://eprint.iacr.org/2019/142.pdf)
- :video_camera: [Youtube: Discrete Log based Zero-Knowledge Proofs - Dan Boneh, Stanford](https://www.youtube.com/watch?v=wB3DlND7KEw)
- [ZKProof Community Reference](https://docs.zkproof.org/pages/reference/reference.pdf)
- :books: [Lecture 5: Proofs of Knowledge, Schnorr’s protocol, NIZK](https://crypto.stanford.edu/cs355/19sp/lec5.pdf)
- :scroll: [Doubly-efficient zkSNARKs without trusted setup](https://eprint.iacr.org/2017/1132.pdf)
- :scroll: [zkStudyClub: PCD without zkSNARK with Pratyush Mishra (UC Berkeley) & Benedikt Bünz (Stanford)](https://www.youtube.com/watch?v=TRyep--q6jU)
- :scroll: [Mystique: Efficient Conversions for Zero-Knowledge Proofs with Applications to Machine Learning](https://www.usenix.org/system/files/sec21-weng.pdf)
- :scroll: [Libra: Succinct Zero-Knowledge Proofs with Optimal Prover Computation](https://eprint.iacr.org/2019/317.pdf)

### Recursive Proofs

- :scroll: [Darlin: Recursive proofs using Marlin](https://arxiv.org/pdf/2107.04315.pdf)

### Short-lived ZKPs

- :scroll: [Short-lived zero-knowledge proofs and signatures](https://eprint.iacr.org/2022/190.pdf)
- :scroll: [Verifiable Delay Functions](https://link.springer.com/chapter/10.1007/978-3-319-96884-1_25)

### Zero-knowledge Proxy

- :scroll: [Zero-Knowledge Middleboxes](https://eprint.iacr.org/2021/1022.pdf)
- :scroll: [Blind Certificate Authorities](https://par.nsf.gov/servlets/purl/10163755)

### Multi-Verifier Proofs

- :scroll: [Feta: Efficient Threshold Designated-Verifier Zero-Knowledge Proofs](https://eprint.iacr.org/2022/082.pdf)
- :scroll: [Non-Interactive Zero-Knowledge Proofs to Multiple Verifiers](https://eprint.iacr.org/2022/063.pdf)
- :scroll: [Verifiable Relation Sharing and Multi-Verifier Zero-Knowledge in Two Rounds: Trading NIZKs with Honest Majority*](https://eprint.iacr.org/2022/167.pdf)

### Multi-Prover Proofs

- [Experimenting with Collaborative zk-SNARKs: Zero-Knowledge Proofs for Distributed Secrets](https://eprint.iacr.org/2021/1530.pdf)

### Designated-Verifier Proofs

- :scroll: [Designated Verifier Proofs and Their Applications](https://link.springer.com/content/pdf/10.1007/3-540-68339-9_13.pdf)

### Garbled Circuits

- :scroll: [A Gentle Introduction to Yao’s Garbled Circuits](https://web.mit.edu/sonka89/www/papers/2017ygc.pdf)
- :video_camera: [MPC-Mike Rosulek-Lecture 2: Advanced Techniques and Optimizations for Garbled Circuits](https://www.youtube.com/watch?v=D6r6o2KQ3Oc&list=LL&index=55)
- :video_camera: [MPC-Mike Rosulek-Lecture 1-3: Overview of Secure Computation and Yao's Protocol](https://www.youtube.com/watch?v=4jZcGqgZKY8&list=LL&index=54)

### Interactive Proofs based on VOLE

- :scroll: [Introduction Vector Oblivious Linear Evaluation (Peter Scholl)](http://cyber.biu.ac.il/wp-content/uploads/2021/11/Vector_Oblivious_Linear_Evaluation-1.pdf)
- :scroll: [Wolverine: Fast, Scalable, and Communication-Efficient Zero-Knowledge Proofs for Boolean and Arithmetic Circuits](https://eprint.iacr.org/2020/925.pdf)
- :scroll: [Mac'N'Cheese Carsten Baum](https://eprint.iacr.org/2020/1410.pdf)
- :scroll: [QuickSilver Kang Yang](https://eprint.iacr.org/2021/076.pdf?ref=https://githubhelp.com)
- :scroll: [AntMan: Interactive Zero-Knowledge Proofs with Sublinear Communication*](https://eprint.iacr.org/2022/566.pdf)

### zk Virtual Machines

## Decentralized Finance

- :video_camera: [Decentralized Finance Lecture (Arthur Gervais)](https://www.youtube.com/watch?v=wlVFc7JklPY&list=PLOa3v6xgsJullbz4uD13nm-U5D_cw0xLh)
- :video_camera: [Decentralized Finance MOOC (Berkeley)](https://www.youtube.com/watch?v=gX3mc83CJtQ&list=PLS01nW3RtgopJOtsMVOK3N7n7qyNMPbJ_)

### Smart Contract Security

- [tbDEX: A Liquidity Protocol v0.1](https://tbdex.io/whitepaper.pdf)
- [The Ring of Gyges: Investigating the Future of Criminal Smart Contracts](https://dl.acm.org/doi/pdf/10.1145/2976749.2978362)
- [Marvel DC: A Blockchain-Based Decentralized and Incentive-Compatible Distributed Computing Protocol](https://arxiv.org/pdf/2207.14011.pdf)
- [Towards Efficient Data Valuation Based on the Shapley Value](http://proceedings.mlr.press/v89/jia19a/jia19a.pdf)
- [AuthSC: Mind the Gap between Web and Smart Contracts](https://arxiv.org/pdf/2004.14033.pdf)

### Arbitrage

- :scroll: [On the Just-In-Time Discovery of Profit-Generating Transactions in DeFi Protocols](https://arxiv.org/pdf/2103.02228.pdf)

### Confidential UTXO and Mixers

- :scroll: [Quisquis: A New Design for Anonymous Cryptocurrencies](https://discovery.ucl.ac.uk/id/eprint/10090371/1/asiacrypt-main.pdf)

## Decentralized Key Management

- :scroll: [NuCypher KMS: Decentralized key management system](https://arxiv.org/pdf/1707.06140.pdf)

### Wallets

- :scroll: [A Formal Treatment of Hardware Wallets](https://eprint.iacr.org/2019/034.pdf)
- :scroll: [On the Usability of Authenticity Checks for Hardware Security Tokens](https://www.usenix.org/system/files/sec21-pfeffer.pdf)
- :scroll: [What’s in Your Wallet? Privacy and Security Issues in Web 3.0](https://arxiv.org/pdf/2109.06836.pdf)

## Decentralized Identity

- :bomb: [Kantara Identity](https://kantara.atlassian.net/wiki/spaces/GI/overview)
- :bomb: [Blockchain and Identity](https://github.com/peacekeeper/blockchain-identity)
- :green_book: [Where to use a blockchain in non-financial applications?](https://vitalik.ca/general/2022/06/12/nonfin.html)
- :green_book: [iden3 Blog](https://blog.iden3.io/)
- :green_book: [Anonymous Credential Part 2: Selective Disclosure and CL Signature](https://medium.com/finema/anonymous-credential-part-2-selective-disclosure-and-cl-signature-b904a93a1565)
- :green_book: [The BBS Signature Scheme](https://identity.foundation/bbs-signature/draft-looker-cfrg-bbs-signatures.html)
- :green_book: [tutorial anoncreds](https://docknetwork.github.io/sdk/tutorials/tutorial_anoncreds.html)
- :green_book: [Zero Knowledge in DiDs and Social Networks](https://mirror.xyz/0xd8159c4DD43FEe99FA86D0BAaCA7a9cC33334864/NzuSXZ5rlgKMrdI6CdplM-03RHia6-k0ei67h3rPp-Y)

### Group Signatures

- [Verifiable Encryption, Group Encryption, and Their Applications to Separable Group Signatures and Signature Sharing Schemes](https://link.springer.com/content/pdf/10.1007/3-540-44448-3_25.pdf)
- [Group Signatures: Authentication with Privacy](https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/Publications/Studies/GruPA/GruPA.pdf?__blob=publicationFile)

### Credential Systems
Todo: separate into on-chain and off-chain credential systems.

- :scroll: [Proof-of-Personhood: Redemocratizing Permissionless Cryptocurrencies](https://bford.info/pub/dec/pop.pdf)
- :scroll: [Decentralized Trust Management](https://www.ieee-security.org/TC/SP2020/tot-papers/blaze-1996.pdf)
- :scroll: [NEXTLEAP: Decentralizing Identity with Privacy for Secure Messaging](https://hal.inria.fr/hal-01673292/file/ares2017.pdf)
- :scroll: [Compact Certificates of Collective Knowledge](http://people.csail.mit.edu/nickolai/papers/micali-compactcert.pdf)
- :file_folder: [CA Authorization Smart Contract Architecture](https://files.slack.com/files-pri/T02467QPZ5G-F03BK93D59T/image.png)
- :scroll: [On Enforcing the Digital Immunity of a Large Humanitarian Organization](https://discovery.ucl.ac.uk/id/eprint/10116630/1/Jovanovic_digital-immunity.pdf)
- :scroll: [Anonymity, Unlinkability, Unobservability, Pseudonymity, and Identity Management – A Consolidated Proposal for Terminology](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.154.421&rep=rep1&type=pdf)
- :scroll: [Security Analysis of Coconut, an Attribute-Based Credential Scheme with Threshold Issuance](https://eprint.iacr.org/2022/011.pdf)
- :scroll: [Zero-Knowledge Proof-of-Identity: Sybil-Resistant, Anonymous Authentication on Permissionless Blockchains and Incentive Compatible, Strictly Dominant Cryptocurrencies](https://arxiv.org/pdf/1905.09093.pdf)
- :scroll: [Towards Self-sovereign, Decentralized Personal Data Sharing and Identity Management](https://mediatum.ub.tum.de/doc/1545514/1545514.pdf)
- :scroll: [Auditable Credential Anonymity Revocation Based on Privacy-Preserving Smart Contracts](https://arxiv.org/pdf/1908.02443.pdf%20)
- :scroll: [Anonymous Credentials Light](https://cs.brown.edu/people/fbaldimt/papers/CCS13.pdf)
- :scroll: [SCPKI: A Smart Contract-based PKI and Identity System](http://library.usc.edu.ph/ACM/SIGSAC%202017/bcc/p35.pdf)
- :scroll: [Cinderella: Turning Shabby X.509 Certificates into Elegant Anonymous Credentials with the Magic of Verifiable Computation](http://www.contrib.andrew.cmu.edu/~bparno/papers/cinderella.pdf)
- :scroll: [With a Little Help from My Friends: Constructing Practical Anonymous Credentials](https://eprint.iacr.org/2021/1419.pdf)
- :scroll: [Towards Smart Contract-based Verification of Anonymous Credentials](https://eprint.iacr.org/2022/492.pdf)
- :scroll: [Exploring Web3 From the View of Blockchain](https://arxiv.org/pdf/2206.08821.pdf)
- :scroll: [zk-creds: Flexible Anonymous Credentials from zkSNARKs and Existing Identity Infrastructure](https://eprint.iacr.org/2022/878.pdf)
- :scroll: [Decentralized Anonymous Credentials](https://eprint.iacr.org/2013/622.pdf)
- :scroll: [A note on anonymous credentials using BLS signatures](https://arxiv.org/pdf/2006.05201.pdf)
- :scroll: [Zero-knowledge credentials with deferred revocation checks](https://github.com/decentralized-identity/snark-credentials/blob/master/whitepaper.pdf)
- :scroll: [Coconut: Threshold Issuance Selective Disclosure Credentials with Applications to Distributed Ledgers](https://arxiv.org/pdf/1802.07344.pdf)
- :scroll: [Anonymous credentials 2.0](https://wiki.hyperledger.org/download/attachments/6426712/Anoncreds2.1.pdf)
- :scroll: [An Efficient System for Non-transferable Anonymous Credentials with Optional Anonymity Revocation](https://link.springer.com/content/pdf/10.1007/3-540-44987-6_7.pdf)
- :scroll: [A Truly Self-Sovereign Identity System](https://arxiv.org/pdf/2007.00415.pdf)
- :scroll: [SAVER: SNARK-friendly, Additively-homomorphic, and Verifiable Encryption and decryption with Rerandomization](https://eprint.iacr.org/2019/1270.pdf)
- :scroll: [ZEBRA: Anonymous Credentials with Practical On-chain Verification and Applications to KYC in DeFi](https://eprint.iacr.org/2022/1286.pdf)

### Distributed Trust
Reputation and recommendation-based trust systems connected to blockchain verification.

- :scroll: [Privacy-Preserving Reputation Systems based on Blockchain and other Cryptographic Building Blocks: A Survey](https://perso.liris.cnrs.fr/omar.hasan/publications/hasan_2021_acm.pdf)
- :scroll: [A Survey on Authorization in Distributed Systems: Information Storage, Data Retrieval and Trust Evaluation](https://ieeexplore.ieee.org/abstract/document/8029549/)
- :scroll: [Reflections on trusting distributed trust](https://arxiv.org/pdf/2210.08127.pdf)

### Decentralized Oracles

- :scroll: [Chainlink 2.0: Next Steps in the Evolution of Decentralized Oracle Networks](https://research.chain.link/whitepaper-v2.pdf)
- :scroll: [Chainlink Off-chain Reporting Protocol](https://research.chain.link/ocr.pdf)
- :scroll: [Town Crier: An Authenticated Data Feed for Smart Contracts](https://dl.acm.org/doi/pdf/10.1145/2976749.2978326)
- :scroll: [DECO: Liberating Web Data Using Decentralized Oracles for TLS](https://dl.acm.org/doi/pdf/10.1145/3372297.3417239)
- :scroll: [Practical Decentralized Oracle Contracts for Cryptocurrencies](https://eprint.iacr.org/2022/499.pdf)
- :scroll: [Discreet Log Contracts](https://adiabat.github.io/dlc.pdf)
- :video_camera: [Youtube: Fan Zhang- "Connection Blockchains to the Real World"](https://www.youtube.com/watch?v=LWphxmUWXG0)
- :green_book: [How DECO Enables Undercollateralized DeFi Lending: A Proof of Concept With Teller](https://blog.chain.link/undercollateralized-lending-teller-deco-poc/)

## Side Chain Committees

- :green_book: [HoneyBadgerSwap: Making MPC as a Sidechain](https://medium.com/initc3org/honeybadgerswap-making-mpc-as-a-sidechain-364bebdb10a5)

### Cryptoeconomic Security

- :scroll: [Cryptoeconomic Security for Data Availability Committees](https://arxiv.org/pdf/2208.02999.pdf)
- :scroll: [Balance: Dynamic Adjustment of Cryptocurrency Deposits](https://dl.acm.org/doi/pdf/10.1145/3319535.3354221)

## Decentralized Data Management

- :green_book: [IPFS: Blog, news & more](https://blog.ipfs.tech/)

### Access Control

- :scroll: [CALYPSO: Private Data Management for Decentralized Ledgers](https://eprint.iacr.org/2018/209.pdf)
- :scroll: [Droplet: Decentralized Authorization and Access Control for Encrypted Data Streams](https://www.usenix.org/system/files/sec20-shafagh.pdf)
- :scroll: [Witness Encryption and its Applications](https://eprint.iacr.org/2013/258.pdf)
- :scroll: [LedgerView: Access-Control Views on Hyperledger Fabric](https://www.comp.nus.edu.sg/~ooibc/BlockchainView.pdf)
- :scroll: [WAVE: A Decentralized Authorization Framework with Transitive Delegation](https://www.usenix.org/system/files/sec19-andersen.pdf)
- :scroll: [Decentralizing Privacy: Using Blockchain to Protect Personal Data](http://homepage.cs.uiowa.edu/~ghosh/blockchain.pdf)
- :scroll: [Design of a Privacy-Preserving Decentralized File Storage with Financial Incentives](https://ieeexplore.ieee.org/abstract/document/7966965)
- :scroll: [Controlling Access to an Oblivious Database Using Stateful Anonymous Credentials](https://link.springer.com/content/pdf/10.1007/978-3-642-00468-1_28.pdf)
- :scroll: [A2L: Anonymous Atomic Locks for Scalability in Payment Channel Hubs](https://eprint.iacr.org/2019/589.pdf)
- :scroll: [Abuse Resistant Law Enforcement Access Systems](https://eprint.iacr.org/2021/321.pdf)
- :scroll: [TimeCrypt: Encrypted Data Stream Processing at Scale with Cryptographic Access Control](https://www.usenix.org/system/files/nsdi20-paper-burkhalter.pdf)
- :scroll: [Interactive Authentication](https://eprint.iacr.org/2022/1682.pdf)

### Data Sharing

- :scroll: [Ghostor: Toward a Secure Data-Sharing System from Decentralized Trust](https://www.usenix.org/system/files/nsdi20-paper-hu-yuncong.pdf)
- :scroll: [OblivP2P: An Oblivious Peer-to-Peer Content Sharing System](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_jia.pdf)
- :scroll: [Building a Secure Data Market on Blockchain](https://www.usenix.org/conference/enigma2019/presentation/song), [Youtube](https://www.youtube.com/watch?v=xF50qCIYwpQ)
- :scroll: [Zeph: Cryptographic Enforcement of End-to-End Data Privacy](https://www.usenix.org/system/files/osdi21-burkhalter.pdf)
- :scroll: [A Demonstration of Sterling: A Privacy-Preserving Data Marketplace](https://www.raymondcheng.net/download/papers/sterling-vldb.pdf)
- :scroll: [Towards Building a Responsible Data Economy (Dawn Song, UC Berkeley)](https://speakerdeck.com/anyscale/towards-building-a-responsible-data-economy-dawn-song-uc-berkeley?slide=53), [Youtube](https://www.youtube.com/watch?v=nBzufVswN1g)
- :scroll: [Federated Authorization over Access to Personal Data for Decentralized Identity Management](https://hardjono.mit.edu/sites/default/files/documents/DecentralizedIDmgmt-IEEE-Comms-2019.pdf)
- :scroll: [FileBounty: Fair Data Exchange](https://arxiv.org/pdf/2008.11362.pdf)
- :scroll: [Do You Know Where Your Data Are? Secure Data Capsules for Deployable Data Protection](https://www.usenix.org/legacy/events/hotos11/tech/final_files/ManiatisAkhawe.pdf)
- :scroll: [Towards Blockchain-based Auditable Storage and Sharing of IoT Data](https://arxiv.org/pdf/1705.08230.pdf)
- :scroll: [Universal Atomic Swaps: Secure Exchange of Coins Across All Blockchains](https://eprint.iacr.org/2021/1612.pdf)
- :scroll: [NFTs for Art and Collectables: Primer and Outlook](https://files.osf.io/v1/resources/gwzd7/providers/osfstorage/628cfa67be4dfd076a66dcb8?action=download&direct&version=1)

### Storage

- :scroll: [IPFS - Content Addressed, Versioned, P2P File System (DRAFT 3)](https://arxiv.org/pdf/1407.3561.pdf)
- :scroll: [Topology-Aware Cooperative Data Protection in Blockchain-Based Decentralized Storage Networks](https://arxiv.org/pdf/2001.04526.pdf)
- :scroll: [Secure Untrusted Data Repository (SUNDR)](https://www.usenix.org/legacy/event/osdi04/tech/full_papers/li_j/li_j.pdf)
- :scroll: [DORY: An Encrypted Search System with Distributed Trust](https://www.usenix.org/system/files/osdi20-dauterman_dory.pdf)
- :scroll: [Verifiable Set Operations over Outsourced Databases](https://link.springer.com/content/pdf/10.1007/978-3-642-54631-0_7.pdf)
- :scroll: [When Query Authentication Meets Fine-Grained Access Control: A Zero-Knowledge Approach](http://www.comp.hkbu.edu.hk/~xujl/Papers/sigmod18_auth.pdf)
- :scroll: [vSQL: Verifying Arbitrary SQL Queries over Dynamic Outsourced Databases](https://eprint.iacr.org/2017/1145.pdf)

### Secret Management

- :scroll: [Can a Public Blockchain Keep a Secret?](https://eprint.iacr.org/2020/464.pdf)
- :scroll: [CHURP: Dynamic-Committee Proactive Secret Sharing](https://dl.acm.org/doi/pdf/10.1145/3319535.3363203)
- :scroll: [Storing and Retrieving Secrets on a Blockchain](https://eprint.iacr.org/2020/504.pdf)
- :scroll: [Practical Non-interactive Publicly Verifiable Secret Sharing with Thousands of Parties](https://eprint.iacr.org/2021/1397.pdf)
- :scroll: [Refresh When You Wake Up: Proactive Threshold Wallets with Offline Devices](https://eprint.iacr.org/2019/1328.pdf)
- :scroll: [Long Live The Honey Badger: Robust Asynchronous DPSS and its Applications](https://eprint.iacr.org/2022/971.pdf)
- :scroll: [COBRA: Dynamic Proactive Secret Sharing for Confidential BFT Services](http://www.di.fc.ul.pt/~blferreira/papers/COBRA.pdf)
- :scroll: [Smart Contract With Secret Parameters](https://infoscience.epfl.ch/record/277810)

### Privacy
The privacy tropic in the context of decentralized data management incorporates (i) asset attestation, delegation, transfer, etc. (ii) private information retrieval, (iii) oblivious random access machines (ORAMs), and (iv) confidential access control policies. 

- :scroll: (i) [Espresso CAP Specification: Configurable Asset Privacy](https://raw.githubusercontent.com/EspressoSystems/cap/main/cap-specification.pdf)
- :scroll: (i) [Decentralized Cross-Blockchain Asset Transfers](https://arxiv.org/pdf/2004.10488.pdf)
- :scroll: (ii) [Heterogeneous Private Information Retrieval](https://par.nsf.gov/servlets/purl/10183612)
- :scroll: (ii) [Towards Extending Noiseless Privacy - Dependent Data and More Practical Approach](https://arxiv.org/pdf/1605.07956.pdf)
- :scroll: (iii) [MACAO: A Maliciously-Secure and Client-Efficient Active ORAM Framework](https://par.nsf.gov/servlets/purl/10205591)
- :scroll: (iii) [A Tale of Two Trees: One Writes, and Other Reads](https://par.nsf.gov/servlets/purl/10200542)
- :scroll: (iv) [Ciphertext policy Attribute based Encryption with anonymous access policy](https://arxiv.org/pdf/1011.0527.pdf)

## Secure Computation

- :green_book: [Secure computation: Homomorphic encryption or hardware enclaves?](https://medium.com/mc2-project/secure-computation-homomorphic-encryption-or-hardware-enclaves-83da90102593)

### Multi Party Computation

- :video_camera: [MPC-Mike Rosulek-Lecture 3: Oblivious Transfer and Extension](https://www.youtube.com/watch?v=l6EcGZYkTug&list=LL&index=53)
- :bomb: [A curated list of multi party computation resources and links.](https://github.com/rdragos/awesome-mpc)
- :scroll: [MP-SPDZ: A Versatile Framework for Multi-Party Computation](https://eprint.iacr.org/2020/521.pdf)
- :scroll: [Faster Secure Two-Party Computation in the Single-Execution Setting](https://eprint.iacr.org/2016/762.pdf)
- :scroll: [Computing on Encrypted Data](https://homes.esat.kuleuven.be/~nsmart/FHE-MPC/Yao.pdf)
- :scroll: [Publicly Auditable MPC-as-a-Service with succinct verification and universal setup](https://arxiv.org/pdf/2107.04248.pdf)
- :scroll: [Multiverse of HawkNess: A Universally-Composable MPC-based Hawk Variant](https://eprint.iacr.org/2022/421.pdf)
- :scroll: [Efficient Constant-Round MPC with Identifiable Abort and Public Verifiability](https://eprint.iacr.org/2020/767.pdf)
- :scroll: [MPC-TP: Fully Linear PCPs and their Cryptographic Applications - Niv Gilboa](https://www.youtube.com/watch?v=ognJEChMyrk)
- :scroll: [Founding Secure Computation on Blockchains](https://eprint.iacr.org/2019/253.pdf)
- :scroll: [YOSO: You Only Speak Once Secure MPC with Stateless Ephemeral Roles](https://eprint.iacr.org/2021/210.pdf)

### Homomorphic Encryption

- :video_camera: [Paillier homomorphic encryption and a share conversion protocol - Federico Mazzone](https://www.youtube.com/watch?v=bOOesu7O1f8&list=LL&index=52)
- :scroll:[Efficient Threshold FHE with Application to Real-Time Systems](https://eprint.iacr.org/2022/1625.pdf)

### Trusted Execution Environments

## Privacy-preserving Computation

### Differential Privacy

- [CHORUS: a Programming Framework for Building Scalable Differential Privacy Mechanisms](https://arxiv.org/pdf/1809.07750.pdf)
- [Non-Interactive Differentially Anonymous Router](https://eprint.iacr.org/2021/1242.pdf)
- [Differential Privacy for Directional Data](https://dl.acm.org/doi/pdf/10.1145/3460120.3484734)
- [GUPT: Privacy Preserving Data Analysis Made Easy](http://www.elaineshi.com/docs/gupt.pdf)
- [The Algorithmic Foundations of Differential Privacy](https://www.tau.ac.il/~saharon/BigData2018/privacybook.pdf)
- [The Composition Theorem for Differential Privacy](http://proceedings.mlr.press/v37/kairouz15.pdf)
- [Prio: Private, Robust, and Scalable Computation of Aggregate Statistics](https://www.usenix.org/system/files/conference/nsdi17/nsdi17-corrigan-gibbs.pdf)
- [Prio+: Privacy Preserving Aggregate Statistics via Boolean Shares](https://eprint.iacr.org/2021/576.pdf)
- [Lightweight techniques for private heavy hitters](https://eprint.iacr.org/2021/017.pdf)
- [Some Remarks and Ideas About Monetization of Sensitive Data](https://link-springer-com.eaccess.ub.tum.de/content/pdf/10.1007/978-3-319-29883-2.pdf#cite.Emiliano)
- [On the Tradeoff Between Privacy and Utility in Data Publishing](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.159.1900&rep=rep1&type=pdf)
- [Empirical privacy and empirical utility of anonymized data](http://archive.dimacs.rutgers.edu/~graham/pubs/papers/empiricalpriv.pdf)
- [Optimal Utility-Privacy Trade-off with Total Variation Distance as a Privacy Measure](https://arxiv.org/pdf/1801.02505.pdf)
- [Secure Multi-party Differential Privacy](https://proceedings.neurips.cc/paper/2015/file/a01610228fe998f515a72dd730294d87-Paper.pdf)
- [Secure Multiparty Computation for Privacy-Preserving Data Mining](https://journalprivacyconfidentiality.org/index.php/jpc/article/download/566/549/)
- [Differential Privacy Under Fire](https://www.usenix.org/legacy/events/sec11/tech/full_papers/Haeberlen.pdf)
- [Private Record Matching Using Differential Privacy](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1068.6437&rep=rep1&type=pdf)
- [Detecting Violations of Differential Privacy](https://dl.acm.org/doi/pdf/10.1145/3243734.3243818)
- [Verifiable Differential Privacy](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.726.795&rep=rep1&type=pdf)
- [DPGen: Automated Program Synthesis for Differential Privacy](https://arxiv.org/pdf/2109.07441.pdf)
- [LightDP: Towards Automating Differential Privacy Proofs](https://arxiv.org/pdf/1607.08228.pdf)
- [εktelo: A Framework for Defining Differentially-Private Computations](https://dl.acm.org/doi/pdf/10.1145/3183713.3196921)
- [Approximate Span Liftings](https://arxiv.org/pdf/1710.09010.pdf)
- [Differentially Private Bayesian Programming](https://dl.acm.org/doi/pdf/10.1145/2976749.2978371)

### Data Lineage

- [SAC: A System for Big Data Lineage Tracking](http://merlintang.github.io/paper/sac_icde.pdf)
- [Capturing and Querying Fine-grained Provenance of Preprocessing Pipelines in Data Science](https://eprints.soton.ac.uk/449939/1/ChapmanVLDB2021.pdf)
- [Data quality: “Garbage in – garbage out”](https://journals.sagepub.com/doi/pdf/10.1177/1833358318774357)

## Decentralized Computation

- :green_book: [Navigating Privacy on Public Blockchains](https://wdai.us/posts/navigating-privacy/)

### Blockchain-coordinated Computation
Todo: Separate blockchain coordinated computation into off-chain computation and smart contract execution.

#### On-chain Computation
- :scroll: [On-Chain Fully Homomorphic Encryption: smartFHE: Privacy-Preserving Smart Contracts from Fully Homomorphic Encryption](https://eprint.iacr.org/2021/133.pdf)
- :scroll: [zkay: Specifying and Enforcing Data Privacy in Smart Contracts](https://thanghoang.github.io/teaching/sp21/cs5594/files/paper/zkay.pdf)
- :scroll: [Zapper: Smart Contracts with Data and Identity Privacy](https://files.sri.inf.ethz.ch/website/papers/ccs22-zapper.pdf)

#### Off-chain Computation
- :scroll: [VERI-ZEXE: Decentralized Private Computation with Universal Setup](https://eprint.iacr.org/2022/802.pdf)
- :scroll: [Zexe: Enabling Decentralized Private Computation](https://eprint.iacr.org/2018/962.pdf)
- :video_camera: [Zexe Youtube](https://www.youtube.com/watch?v=aqkzV81sLmQ&t=5s)
- :scroll: [BUILDING PRACTICAL SYSTEMS THAT COMPUTE ON ENCRYPTED DATA](https://people.eecs.berkeley.edu/~raluca/Thesis.pdf)
- :scroll: [Arbitrum: Scalable, private smart contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kalodner.pdf)
- :scroll: [CLOAK: Enabling Confidential Smart Contract with Multi-party Transactions](https://arxiv.org/pdf/2106.13926.pdf)
- :scroll: [Scalable and Privacy-preserving Off-chain Computations](https://www.depositonce.tu-berlin.de/bitstream/11303/13087/4/eberhardt_jacob.pdf)

#### Hybrid Computation
- :scroll: [Hawk: The Blockchain Model of Cryptography and Privacy-Preserving Smart Contracts](https://eprint.iacr.org/2015/675.pdf)
- :scroll: [HoneyBadgerMPC and AsynchroMix: Practical Asynchronous MPC and its Application to Anonymous Communication](https://dl.acm.org/doi/pdf/10.1145/3319535.3354238)
- :scroll: [Ekiden: A Platform for Confidentiality-Preserving, Trustworthy, and Performant Smart Contracts](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8806762)
- :scroll: [Enigma: Decentralized Computation Platform with Guaranteed Privacy](https://arxiv.org/pdf/1506.03471.pdf)
- :scroll: [Decentralized Privacy-preserving Timed Execution in Blockchain-based Smart Contract Platforms](https://arxiv.org/pdf/1902.05613.pdf)
- :scroll: [ACE: Asynchronous and Concurrent Execution of Complex Smart Contracts](https://dl.acm.org/doi/pdf/10.1145/3372297.3417243)
- :scroll: [Piranha: A GPU Platform for Secure Computation](https://eprint.iacr.org/2022/892.pdf)
- :scroll: [Pesca: A Privacy-Enhancing Smart-Contract Architecture](https://wdai.us/files/2022/PESCA.pdf)
- :scroll: [Flexible Anonymous Transactions (FLAX): Towards Privacy-Preserving and Composable Decentralized Finance](https://eprint.iacr.org/2021/1249.pdf)
- :scroll: [Auditable, Available and Resilient Private Computation on the Blockchain via MPC](https://eprint.iacr.org/2022/398.pdf)
- :scroll: [Cerebro: A Platform for Multi-Party Cryptographic Collaborative Learning](https://www.usenix.org/system/files/sec21-zheng.pdf)
- :scroll: [A Blockchain Model in Tamarin and Formal Analysis of Hash Time Lock Contract](https://drops.dagstuhl.de/opus/volltexte/2020/13418/pdf/OASIcs-FMBC-2020-5.pdf)

### Policy-compliant Computation

- [Blockchain Enabled Privacy Audit Logs](https://www.researchgate.net/profile/Reza-Samavi/publication/320203888_Blockchain_Enabled_Privacy_Audit_Logs/links/5a8f271d0f7e9ba42969773b/Blockchain-Enabled-Privacy-Audit-Logs.pdf)
- [Blockchain Enabled Privacy Audit Logs](https://link.springer.com/chapter/10.1007/978-3-319-68288-4_38)
- [PRIVGUARD: Privacy Regulation Compliance Made Easier](https://www.usenix.org/system/files/sec22summer_wang-lun.pdf)
- [LucidiTEE: A TEE-Blockchain System for Policy-Compliant Multiparty Computation with Fairness](https://eprint.iacr.org/2019/178.pdf)

#### User Centricity and Data Sovereignty

- [User Centricity: A Taxonomy and Open Issues](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.466.343&rep=rep1&type=pdf)
- [Dawn Song (Berkeley)- "Data Sovereignty and Decentralized Data Science"](https://www.youtube.com/watch?v=g8pk89kc940)
- [User-Managed Access to Web Resources](https://eprints.ncl.ac.uk/file_store/production/161154/15A97BD1-4A42-49DF-A5F3-3D3DC9CC8730.pdf)
- [Federated Authorization over Access to Personal Data for Decentralized Identity Management](https://hardjono.mit.edu/sites/default/files/documents/DecentralizedIDmgmt-IEEE-Comms-2019.pdf)
- [Bringing Privacy Control back to Citizens](https://www.ipvs.uni-stuttgart.de/departments/as/publications/stachch/sac_20_dispel.pdf)
- [Metaverse for Social Good: A University Campus Prototype](https://arxiv.org/pdf/2108.08985.pdf)
- [Personal Data: The Emergence of a New Asset Class](https://www3.weforum.org/docs/WEF_ITTC_PersonalDataNewAsset_Report_2011.pdf)
- [Property Rights By Armen A. Alchian](https://www.econlib.org/library/Enc/PropertyRights.html)
- [User Data Privacy: Facebook, Cambridge Analytica, and Privacy Protection](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8436400)
- [Decentralized Society: Finding Web3’s Soul](https://wrenchinthegears.com/wp-content/uploads/2022/05/Vitalek-Buterin-Soulbound-Token-Paper-May-2022.pdf)
- [Policy-Sealed Data: A New Abstraction for Building Trusted Cloud Services](https://www.usenix.org/system/files/conference/usenixsecurity12/sec12-final22.pdf)
- [PrivacyGuard: Enforcing Private Data Usage Control with Blockchain and Attested Off-chain Contract Execution](https://arxiv.org/pdf/1904.07275.pdf)
- [Towards Contractual Agreements for Revocation of Online Data](http://poepper.net/papers/revocation-contracts2019.pdf)

## Systematizations of Knowledge

- :scroll: [SoK: Off The Chain Transactions](https://nms.kcl.ac.uk/patrick.mccorry/SoKoffchain.pdf)
- :scroll: [Formalizing Anonymous Blacklisting Systems](https://oaklandsok.github.io/papers/henry2011.pdf)
- :scroll: [SoK: Privacy-Preserving Computing in the Blockchain Era](https://eprint.iacr.org/2021/727.pdf)
- :scroll: [SoK: A Taxonomy of Cryptocurrency Wallets](https://eprint.iacr.org/2020/868.pdf)
- :scroll: [SoK: Off The Chain Transactions](https://nms.kcl.ac.uk/patrick.mccorry/SoKoffchain.pdf)
- :scroll: [SoK: Certified Robustness for Deep Neural Networks](https://sokcertifiedrobustness.github.io/)
- :scroll: [SoK: Computer-Aided Cryptography](https://oaklandsok.github.io/papers/barbosa2021.pdf)
- :scroll: [SoK: Blockchain Light Clients](https://eprint.iacr.org/2021/1657.pdf)
- :scroll: [SoK: General Purpose Compilers for Secure Multi-Party Computation](https://www.cis.upenn.edu/~stevez/papers/HHNZ19.pdf)
- :scroll: [SoK: TEE-assisted Confidential Smart Contract](https://arxiv.org/pdf/2203.08548.pdf)
- :scroll: [SoK: Differential Privacy as a Causal Property](https://oaklandsok.github.io/papers/tschantz2020.pdf)
- :scroll: [SoK: Research Perspectives and Challenges for Bitcoin and Cryptocurrencies](https://oaklandsok.github.io/papers/bonneau2015.pdf)
- :scroll: [SoK: Delegation and Revocation, the Missing Links in the Web’s Chain of Trust](https://oaklandsok.github.io/papers/chuat2020.pdf)
- :scroll: [SoK: Oracles from the Ground Truth to Market Manipulation](https://arxiv.org/pdf/2106.00667.pdf)
- :scroll: [SoK: Benchmarking Flaws in Systems Security](https://arxiv.org/pdf/1801.02381.pdf)
- :scroll: [SoK: Communication Across Distributed Ledgers](https://allquantor.at/blockchainbib/pdf/zamyatin2019sok.pdf)

## Application Development

- :file_folder: [roadmap.sh](https://roadmap.sh/)
- :file_folder: [A collection of (mostly) technical things every software developer should know about](https://github.com/mtdvio/every-programmer-should-know)

### Decentralized Programming

- :file_folder: [CoLink: Decentralized Programming](https://co-learn.notion.site/co-learn/Welcome-to-CoLink-5bf0c431201441e68cba07a5f7101728)

### Smart Contracts

- :school: [openzeppelin-contracts: OpenZeppelin Contracts is a library for secure smart contract development.](https://github.com/OpenZeppelin/openzeppelin-contracts)
- :file_folder: [How To Use AccessControl.sol](https://medium.com/coinmonks/how-to-use-accesscontrol-sol-9ea3a57f4b15)
- :file_folder: [Role Based Access Control for the Ethereum Blockchain](https://hackernoon.com/role-based-access-control-for-the-ethereum-blockchain-bcc9dfbcfe5c)
- :school: [Creating Zero knowledge Proofs with ZoKrates](https://www.youtube.com/watch?v=_ZvGZxhCFfE)
- :school: [Ethereum Contract Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book)
- :green_book: [How To Script An Automatic Token Airdrop for 40k subscribers](https://medium.com/hackernoon/how-to-script-an-automatic-token-airdrop-for-40k-subscribers-e40c8b1a02c6)

### Layer 2 and Bridges

- :green_book: [Fantastic Zero-Knowledge Proofs](https://medium.com/@outsideranalytics/fantastic-zero-knowledge-proofs-ef4bb746f838)
- :green_book: [Scaling Relic Protocol with zk-SNARKs](https://relicprotocol.medium.com/scaling-relic-protocol-with-zk-snarks-7c5c319c8e9f)
- :school: [Arbitrum: The most secure L2](https://bridge.arbitrum.io/)
- :school: [Arbitrum Developer Quickstart](https://developer.offchainlabs.com/docs/developer_quickstart)

### Oracles

- :school: [libocr consists of a Go library and a set of Solidity smart contracts that implement the Chainlink Offchain Reporting Protocol](https://github.com/smartcontractkit/libocr)
- :file_folder: [This demonstrates how a smart contract on NEAR can access off-chain data via Chainlink's oracle solution.](https://github.com/near-examples/chainlink-demo)

### Web 3.0 Identity

- :file_folder: [Sign-In with Ethereum](https://docs.login.xyz/)
- :school: [ethr-did-resolver: DID resolver for Ethereum Addresses with support for key management](https://github.com/decentralized-identity/ethr-did-resolver)
- :school: [Golang SSI Framework](https://github.com/TBD54566975/ssi-sdk)
- :file_folder: [NFT3 | The First Unified Virtual Identity Network for Web3](https://www.nft3.com/)
- :file_folder: [The essential web3 toolkit for sharing and funding anything.](https://mirror.xyz/)
- :file_folder: [Identity protocol for open applications](https://idx.xyz/)
- :file_folder: [Polygon DID Implementation](https://docs.polygon.technology/docs/develop/did-implementation/getting-started/)
- :file_folder: [Introducing Polygon ID, Zero-Knowledge Identity for Web3](https://blog.polygon.technology/introducing-polygon-id-zero-knowledge-own-your-identity-for-web3/)
- :file_folder: [Claim your passport](https://arcx.game/passport)
- :file_folder: [decentralized-identity / snark-credentials](https://github.com/decentralized-identity/snark-credentials/blob/master/whitepaper.pdf)
- :file_folder: [spruceID: Your Keys, Your Data](https://www.spruceid.com/), :school: [github](https://github.com/spruceid)
- :file_folder: [iden3: Prove your access rights, not your identity](https://iden3.io/)
- :school: [emmy: Library for zero-knowledge proof based applications (like anonymous credentials](https://github.com/xlab-si/emmy)

### Infrastructure
This section is about running blockchain nodes and scaling of backend services.

- :school: [Ranger - A Rust library for listening to P2P traffic without a full node](https://github.com/Rjected/ranger)
- :school: [Go Ethereum Development](https://geth.ethereum.org/)
- :school: [Learn Kubernetes](https://youtube.com/playlist?list=PL34sAs7_26wNBRWM6BDhnonoA5FMERax0)
- :school: [Welcome to the IPFS docs](https://docs.ipfs.tech/)

### Backend

- :school: [go ethereum client](https://goethereumbook.org/en/client-setup/)

### Frontend

- :school: [ether.js: Complete Ethereum library and wallet implementation in JavaScript](https://github.com/ethers-io/ethers.js)
- :school: [Explore the world’s leading design portfolios](https://dribbble.com/)

### Standardization

- :file_folder: [Encrypted Data Vaults 0.1](https://digitalbazaar.github.io/encrypted-data-vaults/#why-do-we-need-encrypted-data-vaults)
- :file_folder: [Decentralized Identifier Resolution (DID Resolution) v0.2](https://w3c-ccg.github.io/did-resolution/#resolver-architectures-proxied)
- :file_folder: [A Primer for Decentralized Identifiers](https://w3c-ccg.github.io/did-primer/)
- :file_folder: [Verifiable Credentials Data Model v1.1](https://www.w3.org/TR/vc-data-model/)
- :file_folder: [3ID DID Method Specification](https://github.com/ceramicnetwork/CIP/blob/main/CIPs/CIP-79/CIP-79.md#example-2)
- :school: [ERC1238: Non-transferrable Non-Fungible Tokens (NTT)](https://github.com/ethereum/EIPs/issues/1238)
- :school: [EIP-721: Non-Fungible Token Standard](https://eips.ethereum.org/EIPS/eip-721)
- :school: [ERC-725 - Ethereum Identity Standard](https://docs.ethhub.io/built-on-ethereum/identity/ERC725/)
- :school: [ERC-735: Claim Holder #735](https://github.com/ethereum/eips/issues/735)
- :school: [EIP-1155: Multi Token Standard](https://eips.ethereum.org/EIPS/eip-1155)
- :school: [EIP-1462: Base Security Token](https://eips.ethereum.org/EIPS/eip-1462)
- :school: [EIP-1056: Ethereum Lightweight Identity](https://eips.ethereum.org/EIPS/eip-1056)
- :school: [Ethereum Improvement Proposals](https://eips.ethereum.org/all)
- :file_folder: [Blockchain Identity](https://decentralized-id.com/blockchain/)

### Tooling

- :school: [Regular Expressions 101](https://regex101.com/)
- :school: [curl-to-Go](https://mholt.github.io/curl-to-go/)

### Cryptographic Libraries

- :school: [RELIC](https://github.com/relic-toolkit/relic)
- :school: [ark-crypto-primitives](https://github.com/arkworks-rs/crypto-primitives)

### Trusted Enclaves

- :file_folder: [Keystone Enclave An Open-Source Secure Enclave for RISC-V](https://keystone-enclave.org/files/keystone-risc-v-summit.pdf)

### Zero Knowledge Proofs

- :file_folder: [Starkware STARK 101](https://starkware.co/stark-101/)
- :file_folder: [zkSync is a user-centric zk rollup platform from Matter Labs (opens new window). It is a scaling solution for Ethereum, already live on Ethereum mainnet.](https://docs.zksync.io/userdocs/)
- :school: [zkSNARK implementation in JavaScript & WASM](https://github.com/iden3/snarkjs)
- :school: [ZoKrates](https://zokrates.github.io/)
- :school: [arkworks is a Rust ecosystem for zkSNARK programming](https://github.com/arkworks-rs)
- :school: [gnark is a fast zk-SNARK library that offers a high-level API to design circuits](https://github.com/ConsenSys/gnark)
- :school: [mimblewimble ](https://github.com/mimblewimble)
- :school: [Go-snark-study](https://github.com/arnaucube/go-snark-study)
- :green_book: [ZK from Scratch](https://asecuritysite.com/zero/#zero3)
- :file_folder: [circom and snarkjs](https://cs251.stanford.edu/hw/proj4.pdf)
- :school: [zkSnark circuit compiler](https://github.com/iden3/circom)
- :school: [zkSNARK implementation in JavaScript & WASM](https://github.com/iden3/snarkjs)
- :school: [Circom circuits used by the iden3 core protocol.](https://github.com/iden3/circuits)
- :file_folder: [zkrp package](https://pkg.go.dev/github.com/0xdecaf/zkrp#section-readme)
- :school: [Ethereum implementation of the Coconut smart contract library](https://github.com/musalbas/coconut-ethereum)
- :school: [MerkleTree compatible with circomlib/sm](https://github.com/iden3/go-merkletree)
- :video_camera: [IDEN3: Scalable distributed identity infrastructure using zero-knowledge proofs to guarantee privacy](https://www.youtube.com/watch?v=VFD2Z_mlSbM)
- :file_folder: [Iden3 Documentation: Iden3 Docs](https://docs.iden3.io/)
- :school: [Circom and SnarkJS](https://docs.iden3.io/circom-snarkjs/)
- :file_folder: [zkDocs](https://github.com/a16z/zkdocs)
- :green_book: [Create your first zero-knowledge snark circuit using circom and snarkjs](https://blog.iden3.io/first-zk-proof.html)
- :green_book: [ZKP— PlonK Algorithm Introduction](https://trapdoortech.medium.com/zkp-plonk-algorithm-introduction-834556a32a)
- :school: [Feta: Efficient Threshold Designated-Verifier Zero-Knowledge Proofs](https://github.com/KULeuven-COSIC/Feta)

### STARKs

- :school: [Winterfell 🐺: A STARK prover and verifier for arbitrary computations](https://github.com/facebook/winterfell)
- :school: [Caigo: Golang Library for StarkNet/Cairo](https://github.com/dontpanicdao/caigo)

### Multi Party Computation

- :file_folder: [MPC-SoK Frameworks](https://github.com/MPC-SoK)
- :school: [dpss python](https://github.com/tyurek/dpss)
- :green_book: [Robust MPC-based confidentiality layer for blockchains](https://github.com/initc3/HoneyBadgerMPC)
- :scroll: [Anonymous Zether: A private payment system for Ethereum-based blockchains, with no trusted setup.](https://github.com/ConsenSys/anonymous-zether)
- :school: [emp-toolkit](https://github.com/emp-toolkit)
- :file_folder: [ABY Developer Guide](https://www.informatik.tu-darmstadt.de/media/encrypto/encrypto_code/abydevguide.pdf)
- :computer: [The Confidential Computing Platform for Collaborative Analytics and AI](https://opaque.co/)
- :scroll: [Zether: Towards Privacy in a Smart Contract World](https://eprint.iacr.org/2019/191.pdf)
- :school: [A collection of Bristol format circuit files](https://github.com/n-for-1-auth/circuits)
- :file_folder: ['Bristol Fashion' MPC Circuits](https://homes.esat.kuleuven.be/~nsmart/MPC/)

## Programming

- :bomb: [Practical Cryptography for Developers](https://cryptobook.nakov.com/)

### Golang

- :books: [A Tour of Go - The Go Programming Language](https://go.dev/tour/welcome/1)

### Rust

- :books: [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
- :books: [Rust Crypto Engineering Course](https://uncloak.org/courses/rust+cryptography+engineering/course-Rust+Cryptography+Engineering+Study+Group+Syllabus)
- :books: [Rust Crypto Engineering Study Group](https://hackmd.io/@thor314/ryEWRY6Qs)
- :video_camera: [Rust Crypto Engineering Study Group](https://drive.google.com/drive/folders/1506sz7G5o6ATeGObP1AEwMV4msaLK3HD)

### Solidity

## Research

### Paper Search

- :bulb: [Explore connected papers in a visual graph](https://www.connectedpapers.com/)
- :bulb: [researchrabbit ai](https://researchrabbitapp.com/)

### Education

- :video_camera: [Blockchain Lecture (Arthur Gervais)](https://www.youtube.com/watch?v=wlVFc7JklPY&list=PLOa3v6xgsJullbz4uD13nm-U5D_cw0xLh)
- :file_folder: [Asecuritysite.com](https://asecuritysite.com/)
- :books: [Mhadi Zamani: Resources](http://mahdiz.com/resources.html)
- :books: [Mhadi Zamani: Crypto](http://mahdiz.com/crypto/)
- :books: [Decentralized Systems Lab](https://decentralize.ece.illinois.edu/)
- :books: [CS294/194-196: Special Topics on Science and Technology of Decentralization and Decentralized Intelligence](https://berkeley-desys.github.io/s22)
- :books: [ZK-STARK Theory & Implementation](https://berkeley-desys.github.io/assets/material/lec5_eli_ben_sasson_zk_stark.pdf)
- :books: [Proofs, Arguments, and Zero-Knowledge](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.html), :scroll: [PDF](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.pdf), :video_camera: [Youtube](https://www.youtube.com/watch?v=esBIB_ZaFVg&list=PLj80z0cJm8QEmZkGgSOLpr_8B08SCWVQ7)
- :books: [CSN09112 Module](https://github.com/billbuchanan/csn09112), :school: [Example file encryption using scrypt and NaCl for the gocrypto book](https://github.com/billbuchanan/filecrypt)
- :books: [ECE/CS 598 AM: Cryptography with Ideal Functionalities](https://decentralize.ece.illinois.edu/ece-cs-598-am-cryptography-with-ideal-functionalities/)
- :books: [Einführung in die Kryptographie von Christof Paar](https://www.youtube.com/channel/UCuJu8DOJLMltMt8RcX1tdBw/videos)
- :books: [Decentralized Systems Lab](https://decentralize.ece.illinois.edu/)
- :books: [Zero-Knowledge Proofs](https://zkp.science/)
- :books: [Lecture slides Blockchain-based Systems Engineering](https://github.com/sebischair/bbse)
- :books: [Iden3 Documentation: Publications](https://docs.iden3.io/publications/publications/)
- :books: [Onur Mutlu: Digital Design and Computer Architecture Spring 2020 (252-0028-00L)](https://safari.ethz.ch/digitaltechnik/spring2020/doku.php?id=start)
- :books: [Onur Mutlu: Lecture Video Playlist on YouTube](https://safari.ethz.ch/digitaltechnik/spring2019/doku.php?id=schedule)
- :books: [Andrew Miller: ECE498AC/CS498AM: Applied Cryptography, Fall 2019](https://soc1024.ece.illinois.edu/teaching/ece498ac/fall2019/)
- :books: [Decentralized Systems Lab: Courses](https://decentralize.ece.illinois.edu/courses/)
- :books: [Christine Parlour, Dawn Song: CS294-177/CS194-177/PHDBA 297T.1/MFE 230T.3: Decentralized Finance](https://berkeley-defi.github.io/f21)
- :books: [Intuitive Advanced Cryptography](https://raw.githubusercontent.com/cryptosubtlety/intuitive-advanced-cryptography/master/advancedcrypto.pdf)
- :books: [A Graduate Course in Applied Cryptography](https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup_0_5.pdf)
- :video_camera: [IC3 Initiative for Cryptocurrencies and Contracts](https://www.youtube.com/channel/UCz-eTbD4kHkYxGhUfXawHow)
- :video_camera: [DeFi MOOC](https://www.youtube.com/channel/UCB67PxhB5LAWEbI4etQS7aw)
- :video_camera: [CryptoClear](https://www.youtube.com/c/CryptoClear)
- :video_camera: [UC Model Youtube: MACS Frontier](https://www.youtube.com/channel/UCIm7ruYT6rUvhm76YeIKiLw)
- :video_camera: [Zero Knowledge](https://www.youtube.com/channel/UCYWsYz5cKw4wZ9Mpe4kuM_g)
- :video_camera: [Grand Amphi Théatre](https://www.youtube.com/channel/UC_kOxlaYNOTtNwtwySZ0B8w)
- :video_camera: [ZK Whiteboard Sessions](https://www.youtube.com/playlist?list=PLj80z0cJm8QErn3akRcqvxUsyXWC81OGq)

### Researchers to follow by domain

<table>
  <thead>
    <tr>
      <th><sub>Name</sub></th>
      <th><sub>Blockchain Security</sub></th>
      <th><sub>Consensus Algorithms</sub></th>
      <th><sub>Decentralized Finance</sub></th>
      <th><sub>Decentralized Identity</sub></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><sub><a href="https://scholar.google.com/citations?user=MwLqCs4AAAAJ&hl=en&oi=ao">Dan Boneh</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://www.semanticscholar.org/author/S.-Micali/1689467">Silvio Micali</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://vitalik.ca/">Vitalik Buterin</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://scholar.google.com/citations?hl=en&user=Nv2jil0AAAAJ">Andrew Miller</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://scholar.google.com/citations?user=84WzBlYAAAAJ&hl=en&oi=ao">Dawn Song</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://scholar.google.com/citations?user=jLr_xi4AAAAJ&hl=en&oi=ao">Arthur Gervais</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub> </sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub> </sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://scholar.google.com/citations?hl=en&user=TwyzQP4AAAAJ">Bryan Ford</a></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://scholar.google.com/citations?user=Hj82r7MAAAAJ&hl=en&oi=sra">Benedikt Bünz</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://scholar.google.com/citations?user=NvKHgzkAAAAJ&hl=en&oi=ao">Raluca Ada Popa</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://pratyushmishra.com/">Pratyush Mishra</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://scholar.google.com/citations?user=Ko1bXSkAAAAJ&hl=en&oi=ao">Joseph Bonneau</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://scholar.google.com/citations?user=LpknufIAAAAJ&hl=en&oi=sra">Paul Grubbs</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://scholar.google.com/citations?user=GMW8K8EAAAAJ&hl=en&oi=ao">Ariel Gabizon</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://www.semanticscholar.org/author/S.-Goldwasser/1706681">Shafi Goldwasser</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://people.cs.georgetown.edu/jthaler/">Justin Thaler</a></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
    </tr>
    <tr>
      <td><sub><a href="https://scholar.google.com/citations?user=gadgSR4AAAAJ&hl=en&oi=sra">E. Glen Weyl</a></sub></td>
      <td><sub><span>&#10003;</span></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
      <td><sub></sub></td>
    </tr>
  </tbody>
</table>

### Conferences

- :bomb: [Cryptography Conferences](https://waset.org/cryptography-conferences)
- :bomb: [Security and Privacy Conference Deadlines](https://sec-deadlines.github.io/)
- :bomb: [Security Conference Ranking](https://people.engr.tamu.edu/guofei/sec_conf_stat.htm)
- :airplane: [CESC: Crypto Economics Security Conference](https://cesc.io/)
- :airplane: [ICBC: IEEE International Conference on Blockchain and Cryptocurrency](https://icbc2023.ieee-icbc.org/authors/call-papers)
- :airplane: [CAAW: 1st International Workshop on Cryptoasset Analytics](https://caaw.io/)
- :airplane: [IEEE-Security](https://www.ieee-security.org/)
- :airplane: [Usenix Security Symposium](https://www.usenix.org/conferences/byname/108)
- :airplane: [Eurocrypt](https://eurocrypt.iacr.org/2023/)
- :airplane: [Crypto](https://www.iacr.org/conferences/)
- :airplane: [S&P: IEEE Symposium on Security and Privacy](https://www.ieee-security.org/TC/SP-Index.html)
- :airplane: [NDSS Symposium](https://www.ndss-symposium.org/)
- :airplane: [CCS (sigsag): ACM Conference on Computer and Communications Security](https://www.sigsac.org/ccs.html)

### Grants

- :moneybag: [Gitcoin Grants](https://gitcoin.co/grants/)

### Scientific Writing

- :scroll: [Scientific Methods in Computer Science](http://poincare.math.rs/~vladaf/Courses/Matf%20MNSR/Literatura/Scientific%20Methods%20in%20Computer%20Science.pdf)
- :video_camera: [How to Write a Great Research Paper (7 Excellent Tips)](https://www.youtube.com/watch?v=VEXaUHNmpQw)
- :scroll: [Benchmarking Crimes: An Emerging Threat in Systems Security](https://arxiv.org/pdf/1801.02381.pdf)

## Companies

### Blockchain Development

- :computer: [Consensys](https://consensys.net/)
- :computer: [Infura](https://www.infura.io/)
- :computer: [Polygon](https://polygon.technology/)

### Identity Management

- :scroll: [Hyperledger CL Credentials](https://github.com/hyperledger/ursa-docs/blob/main/docs/features/attribute_equality_anoncreds.md)
- :scroll: [Hyperledger BBS+ Credentials](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjprZizn-n5AhWcXvEDHRjMCdAQFnoECAYQAQ&url=https%3A%2F%2Fwiki.hyperledger.org%2Fdownload%2Fattachments%2F6426712%2FAnoncreds2.1.pdf&usg=AOvVaw2B-a7JFWfJ1LVFOidVWVhD), :scroll: [PDF Title: Anonymous credentials 2.0](Anoncreds2.1-3.pdf)
- :computer: [Veramo](https://veramo.io/), :school: [docs](https://veramo.io/docs/basics/introduction/), :school: [specs](https://github.com/uport-project/specs)
- :computer: [SpruceID](https://www.spruceid.com/), :school: [docs](https://www.spruceid.dev/), :school: [cryptoscript](https://github.com/spruceid/cryptoscript)
- :computer: [iden3](https://iden3.io/), :school: [docs](https://docs.iden3.io/)
- :computer: [Mattr](https://mattr.global/), :school: [docs](https://github.com/mattrglobal), :green_book: [learn](https://learn.mattr.global/docs/concepts/digital-identity)
- :computer: [Trinsic](https://trinsic.id/), :school: [docs](https://docs.trinsic.id/docs/introduction)
- :computer: [Lukso](https://lukso.network/), :school: [docs](https://docs.lukso.tech/)
- :computer: [Ceramic](https://ceramic.network/), :school: [docs](https://developers.ceramic.network/docs/advanced/standards/application-protocols/identity-index/)
- :computer: [Ocean Protocol](https://oceanprotocol.com/), :school: [docs](https://github.com/oceanprotocol/docs)
- :computer: [Secret Network](https://scrt.network/), :school: [docs](https://docs.scrt.network/secret-network-documentation/)
- :computer: [Oasis Labs](https://www.oasislabs.com/), :school: [docs](https://docs.oasislabs.com/parcel/latest/quickstart/getting-started.html)
- :computer: [iExec](https://iex.ec/), :school: [docs](https://docs.iex.ec/)
- :computer: [Sia](https://siawiki.tech/)
- :computer: [Kepler](https://www.kepler.xyz/), :school: [docs](https://github.com/spruceid)
- :computer: [Storj](https://www.storj.io/), :scroll: [paper](https://www.storj.io/storj.pdf)
- :computer: [Filecoin](https://filecoin.io/), :scroll: [paper](https://filecoin.io/filecoin.pdf)
- :computer: [Gitcoin Passport](https://passport.gitcoin.co/)
- :computer: [Sismo](https://www.sismo.io/)
- (optional) :computer: [brightID](https://www.brightid.org/), :school: [docs](https://github.com/BrightID)
- (optional) :computer: [civic](https://www.civic.com/), :school: [docs](https://docs.civic.com/)
- (optional) :computer: [Decentralized Identity Foundation](https://identity.foundation/), :school: [docs](https://github.com/decentralized-identity)
- (optional) :computer: [ShoCard](https://www.shocard.com/en.html), :school: [docs](https://www.shocard.com/en/developer.html)
- (optional) :computer: [Phala](https://www.phala.network/en/), :school: [docs](https://wiki.phala.network/en-us/build/developer/intro/)
- (optional) :computer: [iDX](https://idx.xyz/), :school: [docs](https://developers.idx.xyz/learn/welcome/)
- (optional) :computer: [Serto](https://www.serto.id/), :school: [docs](https://docs.serto.id/docs/intro)

### Storage Network

- :computer: [Smart contracts + provable storage = FVM](https://fvm.filecoin.io/)
- :green_book: [Decentralized Web Node](https://identity.foundation/decentralized-web-node/spec/#abstract)
- :school: [Decentralized Web Node (DWN) SDK](https://developer.tbd.website/projects/dwn-sdk-js/readme/)

### Data Management

- :computer: (airdrop) [POAP - The bookmarks of your life](https://poap.xyz/)
- :computer: [Atlan: The new way for data-driven teams to discover, understand, trust, and collaborate on data assets](https://atlan.com/)
- :computer: [Promethium: Fast Data Discovery and Governance](https://www.pm61data.com/)
- :computer: [Steem: Powering Communities and Opportunities](https://steem.com/)
- :computer: [Affinidi: Changing data ownership for good](https://www.affinidi.com/)
- :computer: [GET protocol: Ticketing is the start of something bigger](https://www.get-protocol.io/white-label)
- :computer: [SISMO: The key primitive for web3 identities](https://www.sismo.io/)
- :computer: [Proof of Interest](https://whitepaper.firstbatch.xyz/)
- :computer: [MystenLabs: Enigneering asset ownership](https://mystenlabs.com/)

### Resolution

- :computer: [Decentralized naming and certificate authority](https://handshake.org/)
- :school: [An ACME-based certificate authority, written in Go](https://github.com/letsencrypt/boulder)
- :computer: [ENS](https://docs.ens.domains/)
- :scroll: [Ethereum Name Service: the Good, the Bad, and the Ugly](https://arxiv.org/pdf/2104.05185.pdf?ref=https://githubhelp.com)
- :file_folder: [Asecuritysite: DNSSEC](https://asecuritysite.com/encryption/go_dnssec)
- :computer: [The industry leading Web3 API](https://www.alchemy.com/supernode)
- :computer: [The World’s Most Powerful Blockchain Development Suite](https://infura.io/)
- :file_folder: [Sign-in with Ethereum RFP](https://notes.ethereum.org/@djrtwo/sign-in-with-ethereum-RFP)
- :file_folder: [Ceramic Protocol Specification](https://github.com/ceramicnetwork/ceramic/blob/main/SPECIFICATION.md#looking-up-a-stream)
- :computer: (web2) [Okta](https://www.okta.com/products/single-sign-on/)
- :video_camera: (web2) [Youtube: OAuth 2.0 & OpenID Connect (OIDC): Technical Overview](https://www.youtube.com/watch?v=rTzlF-U9Y6Y)

### Asset Management

- :computer: [Asset management for a DeFi world](https://www.tokensets.com/)
- :computer: [Institutional crypto-capital network](https://www.maple.finance/)
- :video_camera: [Data DAO part 1 DataDAO introduction](https://www.youtube.com/watch?v=8YuagajvFJ0&t=2s)

## Blockchain Projects

- :anchor: [Ethereum](https://ethereum.org/en/)
- :anchor: [Algorand](https://www.algorand.com/)
- :anchor: [Avalanche](https://www.avax.network/)
- :anchor: [Tezos](https://tezos.com/)
- :anchor: [Cardano](https://cardano.org/)
- :anchor: [Internet Computer](https://internetcomputer.org/)
- :anchor: [Polkadot](https://polkadot.network/)
- :computer: [Ceramic](https://ceramic.network/)

## News

- :video_camera: [Bankless](https://www.youtube.com/c/Bankless)
- :newspaper: [rekt](https://rekt.news/)
- :newspaper: [IC3 Newsletter.](https://myemail.constantcontact.com/IC3-Blockchain-Camp-Details-and-News.html?soid=1126638416463&aid=Mhix7NUji-U)
- :newspaper: [YCombinator: Hacker News](https://news.ycombinator.com/)
- :newspaper: [Web 5: TBD](https://developer.tbd.website/)
- :newspaper: [Tezos News](https://tezos.com/#news)
- :video_camera: [Grand Amphi Théatre](https://www.youtube.com/@grandamphitheatre6328)

------------------------------------------------------------

## Others

### TLS1.3

- :dizzy: [A Cryptographic Analysis of the TLS 1.3 Handshake Protocol](https://s3.amazonaws.com/files.douglas.stebila.ca/files/research/papers/JC-DFGS21.pdf)
- :scroll: [Cycling Attacks on GCM, GHASH and Other Polynomial MACs and Hashes](https://eprint.iacr.org/2011/202.pdf)
- [Nonce-Disrespecting Adversaries: Practical Forgery Attacks on GCM in TLS](https://eprint.iacr.org/2016/475.pdf)
- :scroll: [Twisted Polynomials and Forgery Attacks on GCM](https://link.springer.com/content/pdf/10.1007/978-3-662-46800-5_29.pdf)
- :scroll: [GCM Security Bounds Reconsidered](https://link.springer.com/chapter/10.1007/978-3-662-48116-5_19)
- :scroll: [Message Franking via Committing Authenticated Encryption](https://www.iacr.org/archive/crypto2017/10401394/10401394.pdf)
- :scroll: [Fast Message Franking: From Invisible Salamanders to Encryptment](https://eprint.iacr.org/2019/016.pdf)
- :scroll: [Beyond Birthday Bound Secure MAC in Faulty Nonce Model](https://eprint.iacr.org/2019/127.pdf)
- :scroll: [Partitioning Oracle Attacks](https://www.usenix.org/system/files/sec21_slides_len.pdf)
- [Implementing and Proving the TLS 1.3 Record Layer](https://cseweb.ucsd.edu/~dstefan/cse227-spring20/papers/tls1.3.pdf)
- :bulb: [The Illustrated TLS 1.3 Connection](https://tls13.xargs.org/)
- [ROSEN: RObust and SElective Non-repudiation (for TLS)](https://dl.acm.org/doi/pdf/10.1145/3474123.3486763), [link2](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/522340/3474123.3486763.pdf?sequence=3&isAllowed=y)
- [Whom You Gonna Trust? A Longitudinal Study on TLS Notary Services](https://publications.sba-research.org/publications/TLSnotaries_preprint.pdf)
- :scroll: [TLS-N: Non-repudiation over TLS Enabling Ubiquitous Content Signing](http://pages.cpsc.ucalgary.ca/~joel.reardon/blockchain/readings/ndss2018_09-4_Ritzdorf_paper.pdf)

### Decentralizing IoT Management

- [Identity Management in IoT Networks Using Blockchain and Smart Contracts](https://ieeexplore-ieee-org.eaccess.ub.tum.de/stamp/stamp.jsp?tp=&arnumber=8726730&tag=1)
- [Smart Contract-Based Access Control for the Internet of Things](https://arxiv.org/pdf/1802.04410.pdf)
- [PPCA: Privacy-Preserving Conditional Actions for IoT Environments Using Smart Contracts](https://dl.acm.org/doi/pdf/10.1145/3360774.3360794)
- [LegIoT: Ledgered Trust Management Platform for IoT](https://www.researchgate.net/profile/Alexandra-Dmitrienko/publication/344292946_LegIoT_Ledgered_Trust_Management_Platform_for_IoT/links/605112d392851cd8ce484013/LegIoT-Ledgered-Trust-Management-Platform-for-IoT.pdf)
- [A Minimalist Approach to Formalizing Analog Sensor Security](https://oaklandsok.github.io/papers/yan2020.pdf)
- [SmartDID: A Novel Privacy-preserving Identity based on Blockchain for IoT](https://ieeexplore.ieee.org/abstract/document/9687671)
- [INVITED Things, Trouble, Trust: On Building Trust in IoT Systems](https://asset-pdf.scinapse.io/prod/2401503174/2401503174.pdf)
- [Smart Contract Data Feed Framework for Privacy-Preserving Oracle System on Blockchain](https://www.mdpi.com/2073-431X/10/1/7)

### Compiler Frameworks

- [SIRNN: A Math Library for Secure RNN Inference](https://eprint.iacr.org/2021/459.pdf)

### Consensus

- [Bullshark: DAG BFT Protocols Made Practical](https://sonnino.com/papers/bullshark.pdf)

### Blockchain networking

- [Dandelion++: Lightweight Cryptocurrency Networking with Formal Anonymity Guarantees](https://arxiv.org/pdf/1805.11060.pdf)

### Securing Certificate Issuing

- :scroll: [Experiences Deploying Multi-Vantage-Point Domain Validation at Let’s Encrypt](https://www.usenix.org/system/files/sec21-birge-lee.pdf)
- :scroll: [Pistis: Issuing Trusted and Authorized Certificates With Distributed Ledger and TEE](https://ieeexplore.ieee.org/abstract/document/9582795)
- :scroll: [CanDID: Can-Do Decentralized Identity with Legacy Compatibility, Sybil-Resistance, and Accountability](https://eprint.iacr.org/2020/934.pdf)
- :scroll: [TeSC: TLS/SSL-Certificate Endorsed Smart Contracts](https://ieeexplore.ieee.org/abstract/document/9566203)

### DNSSEC

- :scroll: [One Key to Sign Them All Considered Vulnerable: Evaluation of DNSSEC in the Internet](https://www.usenix.org/system/files/conference/nsdi17/nsdi17-shulman.pdf)
- :scroll: [Designing for Tussle in Encrypted DNS](https://dl.acm.org/doi/pdf/10.1145/3484266.3487383)

### Anonymity

- :scroll: [k-ANONYMITY: A MODEL FOR PROTECTING PRIVACY](https://www.win.tue.nl/~jhartog/CourseVerif/Papers/10.1.1.90.4099.pdf) 

---

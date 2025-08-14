## A) Abstract

The true power of democracy lies not in elections or officials, but in the shared capacity of individuals to influence the systems that shape their lives. Today, that capacity is constrained by concentrated power, gatekeeping institutions, and political processes often driven more by financial influence than by public will. This paper proposes a hybrid framework for decentralized democracy that combines peer-to-peer trust-graph voting, federated collective governance, and a blockchain backbone for global verifiability.

The design prioritizes privacy, resilience, and human accountability. It offers structural deterrence against harmful activity while maintaining neutrality in its core protocol, enabling adoption across diverse legal and cultural contexts. Key features include a cryptographically secure identity and pseudonym system, trust-weighted decision-making, modular discussion and polling tools, and post-quantum-ready security.

This is not a replacement for brick-and-mortar governance; rather, it is an augmenting layer that existing institutions can adopt, adapt, and coexist with. The system is designed as a set of independently deliverable modules that can be developed in parallel, allowing governments, organizations, and communities to participate without committing to an all-or-nothing deployment.

## B) Introduction

Democracy was conceived to distribute power across society, ensuring that every individual has a voice and a stake in the collective future. Over time, that promise has eroded. Power has migrated from monarchs to the intertwined hands of wealth, influence, and political gatekeeping. Systems intended to amplify individual voices often dilute them instead, leaving most people with little meaningful influence over the decisions that shape their lives.

The gap between public opinion and political action is now quantifiable. In the United States, empirical studies indicate that the probability of a law passing remains near 30%, whether it has overwhelming public support or none at all. The strongest predictor of passage is not public sentiment, but lobbying expenditure. This reality erodes trust and reinforces the perception that policy is purchased rather than earned through democratic consensus.

At the same time, technological capacity has outpaced political adaptation. The ability to connect, deliberate, and self-organize now spans the globe, yet these tools are often co-opted to reinforce existing power structures rather than challenge them. As public trust in institutions declines, the need for a democratic architecture suited to the realities of the 21st century becomes urgent.

This paper introduces a hybrid democratic framework built on three pillars:

1. **Peer-to-Peer (P2P) Trust-Graph Voting** — enabling individuals to propagate decisions directly through their trusted connections.  


2. **Federated Collective Governance** — allowing organizations and governments to operate validator nodes that provide a human face for accountability.  


3. **Blockchain Backbone** — recording critical events and proofs in a globally verifiable, cryptographically secure ledger.  


The goal is not to replace existing physical governance but to integrate with it, providing a channel for continuous public engagement and decision-making. Adoption requires both institutional willingness and public trust, and the framework is designed to encourage both. It incorporates structural deterrence to align participants toward broadly shared moral norms while maintaining a neutral protocol that can adapt to shifting laws and cultural standards.

By modularizing the system into independent deliverables, development can proceed in parallel, allowing incremental adoption without systemic disruption. This document outlines the ethical foundations, conceptual abstractions, usage patterns, technical requirements, and research gaps necessary to realize such a system — and invites collaboration across disciplines to bring it to life.

## C) Ethics & Morals

A democratic system cannot be judged solely by its efficiency or security; it must also be evaluated against the ethical and moral principles it embodies. Existing political structures, while varied in form, share systemic vulnerabilities: susceptibility to corruption, inertia against meaningful reform, and a tendency to serve entrenched interests over the collective will.

This proposed framework inherits its own moral and ethical challenges. By design, it protects anonymity, decentralizes power, and resists centralized control. These same qualities can also shield bad-faith actors, enable coordination among those pursuing harmful aims, or make enforcement of existing laws more difficult. Criminal activity is not just a hypothetical risk — it is inevitable in any open system.

The ethical stance taken here is one of **structural deterrence** rather than universal prohibition. Harmful sub-communities may emerge, but the surrounding social graph and collective governance structures create a counterbalance. Participants are incentivized — through trust weighting, reputation systems, and access control — to remain aligned with the broader moral norms of their societies. Communities can choose to limit engagement with untrustworthy nodes without the protocol itself imposing moral or legal judgments.

The system’s neutrality at the core protocol level ensures it can adapt across jurisdictions and cultural contexts, reflecting the reality that laws and norms evolve. Compliance modules can be implemented by adopting entities to enforce local regulations, but these are optional and programmable. No global authority has the ability to unilaterally suppress speech, block participation, or dismantle the network.

This moral architecture acknowledges that complete safety is impossible. Instead, it seeks to build resilience — encouraging openness, enabling diverse forms of governance, and providing tools for communities to defend themselves without granting any single entity the power to dominate the whole.

## D) High-Level Abstraction of Core Concepts

### 1. Trust

Trust is the foundation of any democratic process. In this framework, trust is modeled explicitly through a *bounded social graph* — each participant connects to a limited number of others whose integrity they can personally attest to. This makes trust both measurable and resilient: the graph can be analyzed for patterns of reliability, historical behavior, and proximity to known bad actors, while still remaining a subjective judgment at the individual level.

Trust serves multiple purposes:

- **Sybil resistance** — limits the ability of malicious actors to flood the system with false identities.  

- **Reputation weighting** — enables decisions to be influenced more by those with a proven record of constructive participation.  

- **Structural deterrence** — encourages alignment with broader community norms without imposing centralized control.  

In essence, trust is both a personal choice and a collective signal, aggregating individual perceptions into a network-wide measure of credibility.

### 2. Identity

Identity in this system is **layered**:

1. **Base identity** — established through proof of humanity and anchored in an identity wallet; creation requires live biometric verification and witness confirmation from an existing trusted participant.  


2. **Pseudonyms** — operational identities that can be fully public, partially private, or entirely secret, each with its own authentication methods.  


This separation allows individuals to participate under multiple pseudonyms without linking them publicly, while still preventing large-scale abuse through the witness and trust-graph system.

The identity design emphasizes:

- **Privacy** — no central authority holds the mapping between pseudonyms and base identity.  

- **Customizable security** — pseudonyms can require anything from a long passphrase to multi-factor biometric authentication.  

- **Recovery** — compromised identities can be restored through social authentication from trusted connections.  

### 3. Social Structures

While trust and identity operate at the individual level, *social structures* organize these elements into communities, organizations, and governance units.

Social structures in this framework are:

- **Voluntary** — participants choose which groups to join and which to avoid.  

- **Flexible** — groups can define their own rules for membership, decision-making, and representation.  

- **Composable** — smaller collectives can form alliances or federations without losing their autonomy.  

By mirroring real-world governance and community structures, the system integrates more easily with existing institutions and allows multiple governance models to coexist. This fosters policy experimentation and the diffusion of successful practices across regions.

### 4. Security

Security in this system has two intertwined goals: **protecting participants from coercion or surveillance**, and **ensuring the integrity of the democratic process**.

Core security principles include:

- **End-to-end encryption (E2EE)** for all communications.  

- **Metadata protection** through privacy networks (e.g., Tor, I2P, mixnets) and cover traffic for sensitive actions like voting.  

- **Post-quantum readiness** — all cryptographic components are chosen or designed to resist both classical and quantum attacks.  

- **Crypto agility** — the system can migrate to new algorithms and protocols without breaking historical integrity.  

- **Device and identity hardening** — secure update channels, sandboxing, and social recovery prevent endpoint compromise from undermining participation.  

Security is not treated as an afterthought or a bolt-on layer; it is embedded in the design at every level, from individual device handling to global consensus verification.

## E) High-Level Abstraction of Usage

### 1. Discussion and Deliberation

Participants engage in structured conversations using a classification-based interface that goes beyond simple “like” or “dislike.”  
Available classifications include:

- **I like / dislike this**  

- **I agree / disagree with this**  

- **I don’t fully agree with this**  

- **This challenged / inspired my opinion**  

**Purpose:** Encourage nuanced responses, help machine learning tools cluster related viewpoints, and make echo chambers visible rather than invisible.  
**Outcome:** Discussions become more searchable, less polarizing, and more productive.

**Integration with votes:**

- Every vote can have its own dedicated discussion board for context and deliberation.  

- Discussions from across the network can also be algorithmically correlated with related votes, allowing participants to see relevant perspectives that might otherwise be siloed.  

### 2. Voting

Two primary modes exist:

- **Proof-required voting** — for formal, high-stakes decisions where eligibility and uniqueness must be verified through zero-knowledge proofs, biometric confirmation, or geospatial checks.  

- **Proof-free voting** — for open, exploratory polls where broad participation matters more than strict eligibility, with trust-weighted analysis to detect manipulation.  

Votes can propagate peer-to-peer through the trust graph, be aggregated at collective levels, or be anchored to the blockchain for public verifiability.  
**Collectives are treated as peers** in the trust network — allowing a collective to propagate decisions directly to all members without intermediate steps.

**Purpose:** Ensure voting can be both secure for high-stakes decisions and accessible for open participation, without compromising trust.  
**Outcome:** Broader engagement with decision-making while preserving integrity where it matters most.

### 3. Polling and Feedback Loops

Individuals or collectives can run polls to gauge sentiment on policies, proposals, or emerging issues.

- **Trust-based filtering** allows analysts to view results weighted by reputation, excluding low-trust clusters if desired.  

**Purpose:** Provide a low-friction way to measure opinion and detect trends in real time.  
**Outcome:** Decision-makers can respond to authentic community sentiment instead of being swayed by the loudest voices.

### 4. Organizational Governance

Communities of any size can form organizations within the system. Membership requirements are intentionally **unrestricted in form** — from government-issued ID verification via ZKPs to unconventional or symbolic initiation rituals.

- Rules can be based on identity proofs, trust graph endorsements, geographic boundaries, or any custom process the collective defines.  

- The system supports integration with specialized servers, token systems, or other mechanisms needed to enforce these requirements.  

Once formed, organizations can:

- Conduct internal discussions, votes, and policy tests.  

- Join federations or alliances for larger-scale decision-making.  

- Propagate decisions directly to their entire membership as a peer in the trust network.  

**Purpose:** Allow any group, from governments to grassroots collectives, to govern themselves using their own rules.  
**Outcome:** Encourages diversity of governance models while maintaining interoperability across the network.

### 5. Representation and Engagement Filtering

Not every participant will want to engage with every issue.

- **Representation** allows users to delegate their vote to trusted individuals or groups, with the ability to reclaim it at any time.  

- **Engagement filters** let users see only the votes or discussions they care about, reducing noise without removing their voice from the process.  

**Purpose:** Respect varying levels of desired engagement while keeping every voice in the decision-making process.  
**Outcome:** Higher sustained participation without overwhelming less active members.

### 6. Analytical Tools for Collective Awareness

The framework includes privacy-preserving analytics to help communities understand themselves and their place in the broader network.

- **Ideological heat maps** — large-scale, anonymized visualizations of political and cultural leanings across regions.  

- **Gradient-of-ideology propagation** — tracking how ideas, values, or policies spread over time and across communities, highlighting early adopters, resistant regions, and potential bridges.  

Safeguards include:

- Minimum aggregation thresholds to protect small groups.  

- Trust-weighted inputs to improve reliability.  

- **Privacy-preserving aggregation** — geospatial and statistical outputs are modified with calibrated noise (differential privacy techniques) so that no individual or small group can be reverse-identified, even by a well-resourced adversary.  

**Purpose:** Give communities a clear, safe view of how ideologies and policies spread, adapt, and succeed.  
**Outcome:** Enables democratic “natural selection” of ideas while protecting individuals and small groups from exposure.

## F) High-Level Technical Overview

The framework’s technical pillars define how its core principles — trust, privacy, resilience, and scalability — are implemented. Each pillar is structured with a clear **Goal**, **Candidate Approaches / Technologies**, and **Research & Verification Needed [see I) References]**.

### 1. Identity and Trust Layer

**Goal**  
Protect identities as the foundational security requirement, ensuring no derivation of a user’s identity wallet secrets from any pseudonym public keys. Establish a privacy-preserving, Sybil-resistant trust graph that is both technically and socially resilient. Liveness checks and human witness attestations help prevent the creation of fake participants and strengthen the integrity of the trust network.

**Candidate Approaches / Technologies**  
- Identity wallets with secure key storage, credential issuance, and recovery.  
- Onboarding with live biometric checks and human witness attestations.  
- Bounded trust graphs limiting attestations per participant to reduce Sybil risk.  
- Social recovery using threshold signatures (e.g., Shamir’s Secret Sharing, FROST).

**Research & Verification Needed [see I) References]**  
- Optimal trust-graph metrics that preserve diversity and resist echo chamber entrenchment [1][2][3][4][5][6][7][8].  
- ZKP protocols proving uniqueness without revealing biometrics or personal data [51][52][53][54][55].  
- Threat modeling of witness-based onboarding to detect collusion or manipulation [51][52][53][54][55].

### 2. Discussion, Voting, and Polling Layer

**Goal**  
Provide the technical means for anyone to create a binding vote or a non-binding poll (discussion-based opinion gathering) and to host free-standing threaded discussions. Discussions should be organized, support sub-discussions, and enable the discovery of related conversations across time, geography, and topics. System should detect echo chambers, identify ideological “bridges,” and reduce bad-faith flooding through trust penalties and filtering.

**Candidate Approaches / Technologies**  
- Reddit-style threaded discussion structure with trust-based filtering.  
- Integrated discussion–vote correlation to give voters context.  
- Proof-required voting using ZKPs, biometrics, or geospatial proofs.  
- Proof-free polls/discussions with trust-weighted sentiment analysis.  
- Anti-flood measures: rate-limiting, trust-score penalties, and spam detection.

**Research & Verification Needed [see I) References]**  
- Scalable ZKP voting systems (Halo 2, zk-STARKs) for large populations [9][10][11][12][13][14][15][16][17].  
- Cross-linking algorithms for related discussions without algorithmic bias [7][8].  
- Machine learning models for echo chamber mapping and bridge detection [7][8].

### 3. Organizational Governance Layer

**Goal**  
Provide governance capabilities at any scale — from global to household — with customizable, enforceable membership requirements. Ensure hierarchical autonomy: lower-level peers (e.g., municipalities) can bypass intermediate layers to participate directly in higher-level governance, preserving dissenting voices and avoiding representation failures.

**Candidate Approaches / Technologies**  
- Membership modules supporting government ID + ZKP, trust attestations, tokens, or custom rituals.  
- Governance templates: quadratic voting, liquid democracy, council systems.  
- Federation protocols for linking autonomous collectives.

**Research & Verification Needed [see I) References]**  
- Secure “membership API” for arbitrary entry requirements [51][52][54].  
- Standard formats for governance metadata to allow cross-collective participation [51][54].  
- Infiltration resistance models for hostile takeover attempts [1][2][3][4][5][6][7][8].

### 4. Security and Privacy Layer

**Goal**  
Protect against surveillance and the resulting risks of oppression and manipulation. Secure data at rest and in transit, confirm that votes are recorded without interception or discarding, and ensure cryptographic resistance against both classical and quantum attacks.

**Candidate Approaches / Technologies**  
- E2EE protocols (Double Ratchet, MLS) for all communications.  
- Metadata protection with Tor, I2P, or mixnets plus cover traffic.  
- PQC primitives (CRYSTALS-Kyber, Dilithium) for all cryptographic functions.  
- Crypto agility with versioned, upgradable protocols.  
- Device hardening: signed updates, reproducible builds, sandboxing.  
- Vote receipts providing verifiable proof of recording without revealing content.

**Research & Verification Needed [see I) References]**  
- Efficient PQC-compatible ZKP protocols [18][19][20][21][22][23].  
- Mixnet performance tuning for interactive democratic processes [28][29][30][31][32].  
- Endpoint compromise resistance in diverse device environments [38][39][40][41][42][43][44].

### 5. Data and Analytics Layer

**Goal**  
Deliver privacy-preserving analytics to support governance decisions, measure trust and confidence in votes (especially proof-free votes), and visualize ideological landscapes over time.

**Candidate Approaches / Technologies**  
- Differential privacy for noise injection in aggregated outputs.  
- Trust-weighted aggregation algorithms.  
- Heat maps and gradient propagation models for tracking ideological spread.

**Research & Verification Needed [see I) References]**  
- Balancing privacy noise with signal clarity for decision-making [45][46][47][48].  
- Visualization standards preventing micro-targeting or individual identification [45][46][47][48][49][50].  
- Decentralized computation to avoid central aggregation risks [45][46][47][48].

### 6. Network and Consensus Layer

**Goal**  
Prevent tracing votes and discussion activity to specific devices or endpoints, while ensuring a tamper-resistant global record of decisions. Guarantee correctness and availability of network state even in the presence of failures or malicious actors.

**Candidate Approaches / Technologies**  
- Hybrid architecture:  
  - P2P trust-graph propagation for small-scale actions.  
  - Federated governance nodes for scaling and accountability.  
  - Blockchain backbone for immutable anchoring.  
- Light clients and pruned nodes to minimize storage burden.  
- Archival nodes for full historical retention.

**Research & Verification Needed [see I) References]**  
- Consensus mechanisms optimized for hybrid federated/public designs (Tendermint, HotStuff, Narwhal/Bullshark) [33][34][35][36].  
- State proof systems (Verkle trees, succinct proofs) for light clients [37].  
- Recovery protocols for network partitions or validator compromise [33][34][35][36].

## G) Low-Level Technical Details (Established and Implementable)

**Note:**  
Due to the open research requirements outlined in **F) High-Level Technical Overview**, this section is not complete. The following specifications cover components and configurations already in widespread, verifiable use or undergoing formal standardization. All parameters remain subject to revision based on future testing, security audits, and expert review.

### 1. Cryptographic Standards
- **Asymmetric Encryption (classical)** — X25519 (Curve25519) for key exchange; Ed25519 for digital signatures [25][26]. *(Not quantum-safe — to be paired with PQC algorithms.)*  
- **Post-Quantum Cryptography (PQC)** — CRYSTALS-Kyber (key encapsulation) and CRYSTALS-Dilithium (signatures), per NIST PQC Round 3 selections [18][19].  
- **Symmetric Encryption** — AES-256-GCM for general-purpose encryption *(quantum-resistant; Grover’s algorithm reduces effective key strength to ~128 bits)*; ChaCha20-Poly1305 for mobile/low-power environments.  
- **Hashing** — SHA3-256 and BLAKE3 for general hashing *(quantum-resistant under Grover’s algorithm)*; Poseidon hash for zero-knowledge proof (ZKP) circuits [17].  
- **Key Derivation** — HKDF with SHA3-256 for session key derivation.

### 2. Identity Wallet Structure
- **Storage** — Encrypted with AES-256-GCM using a key derived from user credentials via Argon2id (memory-hard key derivation).  
- **Recovery** — Social recovery via threshold signatures (e.g., 3-of-5 trusted peers) using FROST multisignature scheme [38].  
- **Onboarding** — Live biometric check combined with witness-signed attestations, committed to the trust graph via signed proof objects [51][52][53][54].

### 3. Trust Graph Representation
- **Graph Structure** — Directed graph stored locally with periodic hashed summaries anchored to the blockchain.  
- **Connection Limit** — Soft limit on attestations per user to reduce Sybil attack potential (tunable via governance).  
- **Scoring** — Multi-factor trust weighting (historical accuracy, peer endorsements, anomaly detection) [1][2][3][4][5][6][7][8].

### 4. Communication Protocols
- **Transport Security** — Noise Protocol Framework for encrypted sessions [25], layered over QUIC for low-latency transport [27].  
- **Metadata Protection** — Pluggable routing layer supporting Tor [28], I2P [32], or mixnets [29][30][31]; cover traffic enabled for voting and other sensitive actions.  
- **Message Format** — Protobuf or FlatBuffers for efficient serialization; optional JSON for human-readable debugging.

### 5. Voting Protocol (Proof-Required Mode)
- **Proof Types** — Zero-knowledge proof of eligibility (zk-SNARKs or zk-STARKs) without revealing voter identity [9][10][11][12][13][14][15][16][17].  
- **Ballot Structure** — Commit–Reveal scheme:  
  1. Commitment hash of vote choice and nonce submitted.  
  2. Reveal phase publishes choice + nonce for verification.  
- **Auditability** — Merkle tree of commitments anchored to blockchain; voters can verify inclusion without revealing vote content.

### 6. Voting Protocol (Proof-Free Mode)
- **Authentication** — Pseudonymous signatures using Ed25519 [26].  
- **Aggregation** — Trust-weighted tally computed locally and verifiably aggregated via federated nodes.  
- **Anti-Spam** — Per-pseudonym rate limits and trust-score adjustments for suspected flooding.

### 7. Data Analytics Privacy Controls
- **Differential Privacy Parameters** — ε (epsilon) set between 0.1 and 1.0 for strong privacy; tunable per query type [45][46][47][48].  
- **Noise Distribution** — Laplace or Gaussian mechanism depending on output domain.  
- **Minimum Aggregation Threshold** — No output generated below 100 unique contributors (configurable via governance).

### 8. Network & Consensus
- **Consensus Algorithm** — Tendermint Core (Byzantine Fault Tolerant) for federated node coordination [33].  
- **State Commitments** — Merkle-Patricia trie roots anchored to blockchain at fixed intervals.  
- **Light Client Proofs** — Verkle trees for compact state verification [37].  
- **Storage Strategy** — Light clients keep recent state; pruned nodes retain partial history; archival nodes store full history with cryptographic proof of completeness.


## H) Deliverables (Modular, Parallelizable)

**Note:** Deliverables are designed to be small, self-contained modules with clear interfaces so multiple teams can build in parallel. Each item lists **Goal**, **Outputs**, **Interfaces**, **Dependencies**, and **Done when**. “Soft” dependencies indicate optional coupling for richer functionality.



### 1. Identity Wallet (Local-first)
**Goal:** Create & manage base identities and pseudonyms with secure local key storage and social recovery.  
**Outputs:** Desktop/mobile apps; CLI; encrypted wallet file schema; recovery ceremony guide.  
**Interfaces:** Local API (IPC/HTTP) for key ops; export/import of signed attestations; recovery API (threshold approval).  
**Dependencies:** None (foundational).  
**Done when:** Keys can be generated/recovered; pseudonyms created; attestations signed/verified; UX passes basic usability tests.



### 2. Witness Onboarding & Liveness Kit
**Goal:** Human-witness attestations + liveness checks for identity creation.  
**Outputs:** Attestation protocol spec; liveness SDK (camera/voice/gesture); witness app flow.  
**Interfaces:** Wallet consumes/produces signed attestation objects; verifier library.  
**Dependencies:** (Soft) Identity Wallet.  
**Done when:** Two devices can complete a witnessed onboarding with stored, verifiable proofs.



### 3. Trust Graph Engine (Bounded Degree)
**Goal:** Maintain per-user trust edges with limits; compute trust metrics locally.  
**Outputs:** Graph store; scoring library (with plug-in metrics); snapshot/restore format.  
**Interfaces:** gRPC/HTTP for add/remove edge, list neighbors, score node/subgraph; snapshot hash API.  
**Dependencies:** Identity Wallet (pseudonym keys).  
**Done when:** Users can add ≤N attestations; compute default trust scores; export a hashed snapshot.



### 4. Discussion & Classification Service
**Goal:** Threaded discussions with classification inputs and cross-linking to votes/polls.  
**Outputs:** Discussion service; classification schema; correlation indexer.  
**Interfaces:** REST/GraphQL for create thread/comment, classify, search; subscription API for updates.  
**Dependencies:** (Soft) Trust Graph for filtering; (Soft) Analytics for correlation.  
**Done when:** Users can create/read/classify threads; related discussions are discoverable across topics/time.



### 5. Proof‑Free Polling Module
**Goal:** Low-friction polls tied to discussions; trust‑weighted aggregation.  
**Outputs:** Poll objects; tally service; trust filter plugin.  
**Interfaces:** Create/close poll; submit ballot (pseudonymous sig); fetch tallies with filters.  
**Dependencies:** Trust Graph Engine; Discussion Service.  
**Done when:** Polls run at scale; tallies reproducible from inputs; manipulation resistance tests pass (rate limits, filters).



### 6. Proof‑Required Voting (Proof-Required Voting Pilot)
**Goal:** Binding votes with ZK eligibility; commit‑reveal ballots; inclusion proofs.  
**Outputs:** ZK circuits/templates; commit‑reveal workflow; verifier library; ballot spec.  
**Interfaces:** Prover/Verifier APIs; ballot submission; inclusion proof retrieval.  
**Dependencies:** Identity Wallet; Witness Kit; (Soft) Network Privacy for submission.  
**Done when:** End‑to‑end demo: user proves eligibility, submits commitment, reveals, verifies inclusion without identity leakage.



### 7. Network Privacy Layer (Routing & Cover)
**Goal:** Metadata-resistant transport (Tor/I2P/mixnet) with automatic safe defaults for sensitive ops.  
**Outputs:** Pluggable transport adapter; policy engine (when to use which); cover-traffic scheduler.  
**Interfaces:** Drop-in SOCKS/HTTP proxy; SDK hooks (submit_vote_secure, fetch_via_privacy).  
**Dependencies:** None (can be integrated later by modules).  
**Done when:** Sensitive actions automatically route over privacy transports; latency/throughput baselines documented.



### 8. Federated Node (Reference Implementation)
**Goal:** Operable node for organizations/municipalities: auth, rate‑limit, aggregate, publish snapshots.  
**Outputs:** Node binary/helm chart; admin console; logging/metrics; snapshot signer.  
**Interfaces:** Ingest APIs (discussions, polls, votes); publish APIs (snapshots, tallies); health/observability endpoints.  
**Dependencies:** (Soft) Trust Graph Engine; (Soft) Voting/Polling modules.  
**Done when:** A federation of nodes can accept input, produce signed periodic snapshots, and withstand basic DoS tests.



### 9. Light‑Client Anchoring & Proofs
**Goal:** Anchor critical summaries to a ledger; enable clients to verify with compact proofs.  
**Outputs:** Anchoring service; light‑client verifier; state proof format (e.g., Merkle/Verkle).  
**Interfaces:** submit_anchor(hash, metadata); get_proof(anchor_id); verify_proof().  
**Dependencies:** Federated Node (snapshots); (Soft) chosen ledger.  
**Done when:** Clients can verify snapshot inclusion/immutability without running a full node.



### 10. Differential‑Privacy Analytics Toolkit
**Goal:** Safe aggregates (heat maps, trends) with calibrated noise and minimum thresholds.  
**Outputs:** DP library (ε, δ policies); geospatial binning; report templates; reviewer simulator to test re‑identification risk.  
**Interfaces:** dp_query(dataset, metric, epsilon); thresholding; audit logs.  
**Dependencies:** (Soft) Federated Node (data feeds).  
**Done when:** Reports meet utility targets (signal retention) and pass privacy adversary tests.



### 11. Secure Update & Supply‑Chain Hardening
**Goal:** Ship trustworthy binaries; prevent malicious updates.  
**Outputs:** Reproducible build pipelines; signed releases (multi‑sig); rollback protection (e.g., TUF‑style); SBOMs.  
**Interfaces:** Update client; signature verification; transparency log publish.  
**Dependencies:** All client/server deliverables adopt this.  
**Done when:** Independent parties can reproduce releases; clients reject unsigned/rolled‑back updates; SBOMs available.



### 12. Governance & Membership API
**Goal:** Pluggable membership checks (ID+ZKP, trust threshold, tokens, custom rituals) and policy‑driven org governance.  
**Outputs:** Membership plugin framework; policy DSL; reference plugins.  
**Interfaces:** check_membership(pseudonym, policy); issue/revoke membership proofs; org policy endpoints.  
**Dependencies:** Identity Wallet; Trust Graph Engine; (Soft) Proof‑Required Voting.  
**Done when:** Orgs can define/modify membership rules and enforce them via plugins; interop tests across orgs pass.



### 13. Representation & Delegation Module
**Goal:** User‑controlled proxying (delegate and reclaim at will) with transparent audit.  
**Outputs:** Delegation objects; tally integration; UI for delegate selection.  
**Interfaces:** set_delegate()/revoke(); list_delegations(); compute_tally_with_delegation().  
**Dependencies:** Voting/Polling modules; Trust Graph (for visibility/weighting).  
**Done when:** Delegations are honored in tallies; revocation is immediate; audit views available.



### 14. SDKs & Reference UIs
**Goal:** Make it easy to build third‑party apps and run realistic pilots.  
**Outputs:** JS/TS, Rust, Python SDKs; reference web/mobile clients; sample org admin UI.  
**Interfaces:** Typed client libraries covering all public APIs; mock servers.  
**Dependencies:** All public modules.  
**Done when:** External developers can build a working pilot app using only the SDKs and docs.



## Minimal Parallel Build Plan (suggested)

- **Track A (Identity & Trust):** 1, 2, 3, 11  
- **Track B (Deliberation & Polls):** 4, 5, 13, 14  
- **Track C (Voting & Privacy):** 6, 7, 9  
- **Track D (Federation & Analytics):** 8, 10  
- **Cross‑cutting:** 11 (updates) applies everywhere; 12 (membership) slots in once 1/3 exist.

**Integration milestones**  
1. **M1 – Local Civic Pilot:** 1+3+4+5+14 (no ledger, no federation).  
2. **M2 – Org Pilot:** 1+3+4+5+8+10+11+12 (adds federation, membership, safe analytics).  
3. **M3 – Binding Vote Pilot:** 1+2+3+6+7+8+9+11 (adds ZK eligibility, private routing, anchoring).

## I) References

[1] Yu, H., Gibbons, P., Kaminsky, M., Flaxman, A. **SybilGuard: Defending Against Sybil Attacks via Social Networks.** SIGCOMM ’06. (PDF). — **Mature**.  
[2] Yu, H., et al. **SybilLimit: A Near‑Optimal Social Network Defense against Sybil Attacks.** IEEE S&P ’08. (PDF). — **Mature**.  
[3] Danezis, G., Mittal, P. **SybilInfer: Detecting Sybil Nodes using Social Networks.** NDSS ’09. (PDF). — **Mature**.  
[4] Cao, Q., et al. **SybilRank: Aiding the Detection of Fake Accounts in Large Scale OSNs.** NSDI ’12. — **Mature**.  
[5] Viswanath, B., et al. **An Analysis of Social Network‑based Sybil Defenses.** SIGCOMM CCR ’10. — **Mature**.  
[6] Jia, J., Wang, B., Gong, N. **Random Walk based Fake Account Detection in OSNs.** — **Mature**.  
[7] Survey: Ramalingam, D., et al. **Fake profile detection techniques in large‑scale OSNs.** Computers & Electrical Engineering 2018. — **Mature**.  
[8] NDSS page. **SybilInfer.** — **Mature**.

[9] Adida, B. **Helios: Web‑based Open‑Audit Voting.** USENIX Security ’08. — **Mature**.  
[10] Pereira, O., et al. **Internet Voting with Helios.** Real‑World E‑Voting (2018). — **Mature**.  
[11] Hao, F., Ryan, P.Y.A. **Anonymous Voting by Two‑Round Public Discussion (AV‑net / Open Vote Network).** (2009/2015). — **Mature**.  
[12] Stančíková, I., Homoliak, I. **SBvote: Scalable Self‑Tallying Blockchain‑Based Voting.** ACM AFT ’23. — **Emerging**.  
[13] Groth, J. **On the Size of Pairing‑Based Non‑Interactive Arguments.** EUROCRYPT ’16 (Groth16). — **Mature**.  
[14] ECC. **Explaining Halo 2** + **Halo2 Protocol Book**. 2020–2023. — **Emerging**.  
[15] Ben‑Sasson, E., et al. **STARKs: Scalable, Transparent ARguments of Knowledge.** (ePrint/lectures, 2018–). — **Emerging**.  
[16] MACI docs. **Minimal Anti‑Collusion Infrastructure.** — **Emerging**.  
[17] Benchmarking. **ZK‑friendly hashes (Poseidon/Poseidon2) in SNARKs.** arXiv 2024. — **Cutting‑edge**.

[18] NIST **FIPS‑203: ML‑KEM** (Kyber). Final 2024. — **Mature**.  
[19] NIST **FIPS‑204: ML‑DSA** (Dilithium). Final 2024. — **Mature**.  
[20] NIST **FIPS‑205: SLH‑DSA** (SPHINCS+). Final 2024. — **Mature**.  
[21] Signal. **PQXDH: Post‑Quantum Extended X3DH.** 2023. — **Emerging**.  
[22] Cryspen/Inria. **Analysis of PQXDH.** 2023. — **Emerging**.  
[23] Latacora. **Crypto Right Answers: Post‑Quantum Edition (hybrids).** 2024. — **Emerging**.

[24] IETF **RFC 9420: Messaging Layer Security (MLS).** 2023/2024. — **Mature**.  
[25] Perrin, T. **The Noise Protocol Framework.** (spec). — **Mature**.  
[26] Perrin, T.; Marlinspike, M. **The Double Ratchet Algorithm.** 2016. — **Mature**.  
[27] IETF **RFC 9000: QUIC Transport.** 2021. — **Mature**.

[28] Dingledine, R., Mathewson, N., Syverson, P. **Tor: The Second‑Generation Onion Router.** USENIX Security ’04. — **Mature**.  
[29] Piotrowska, A.M., et al. **Loopix: The Loopix Anonymity System.** USENIX Security ’17. — **Mature**.  
[30] Sasy, S., et al. **SoK: Metadata‑Protecting Communication Systems.** PoPETs 2024. — **Emerging**.  
[31] Das, D., et al. **Are Continuous Stop‑and‑Go Mixnets Provably Secure?** PoPETs 2024. — **Cutting‑edge**.  
[32] I2P Specs & Docs. **Invisible Internet Project.** (living specs). — **Mature**.

[33] Buchman, E. **Tendermint: BFT in the Age of Blockchains.** 2016. — **Mature**.  
[34] Yin, M., et al. **HotStuff: BFT Consensus with Linearity and Responsiveness.** 2019. — **Mature**.  
[35] Danezis, G., et al. **Narwhal and Tusk: A DAG‑based Mempool and Efficient BFT Consensus.** 2021. — **Emerging**.  
[36] Spiegelman, A., et al. **Bullshark: DAG BFT Protocols Made Practical.** CCS ’22. — **Emerging**.  
[37] Kuszmaul, J. **Verkle Trees: A Bandwidth‑Efficient Alternative to Merkle Trees.** 2018/2019. — **Emerging**.

[38] The Update Framework. **TUF** (spec & project site). — **Mature**.  
[39] Torres‑Arias, S., et al. **in‑toto: Farm‑to‑Table Guarantees for Bits and Bytes.** USENIX Security ’19. — **Mature**.  
[40] Reproducible Builds — project docs & why. — **Mature**.  
[41] SPDX **Specification v3.0.1**. — **Mature**.  
[42] OWASP **CycloneDX** (ECMA‑424) — spec overview. — **Mature**.  
[43] Linux Foundation. **SPDX 3.0 announcement.** 2024. — **Mature**.  
[44] CycloneDX v1.5 release notes / overview. — **Mature**.

[45] Dwork, C., Roth, A. **The Algorithmic Foundations of Differential Privacy.** 2014. — **Mature**.  
[46] U.S. Census Bureau. **Disclosure Avoidance and the 2020 Census (TopDown Algorithm brief).** 2023. — **Mature**.  
[47] Abowd, J.M., et al. **The 2020 Census Disclosure Avoidance System TopDown Algorithm.** 2021/2022. — **Mature**.  
[48] U.S. Census. **Understanding Differential Privacy** (resource hub). — **Mature**.  
[49] Google Research. **Differentially Private Heatmaps.** 2023. — **Emerging**.  
[50] PPMF Tech Docs. **2020 Census Privacy‑Protected Microdata File.** 2024. — **Mature**.

[51] W3C. **Decentralized Identifiers (DID) v1.0** — Recommendation. 2022. — **Mature**.  
[52] Maram, S.K.D., et al. **CanDID: Can‑Do Decentralized Identity with Legacy Compatibility, Sybil‑Resistance, and Accountability.** IEEE S&P ’21. — **Emerging**.  
[53] Adler, S., et al. **Personhood Credentials** (arXiv). 2024/2025. — **Cutting‑edge**.  
[54] Survey. **DIDs and Verifiable Credentials** (arXiv 2024). — **Emerging**.  
[55] Web3/Gitcoin & ecosystem resources on **MACI** deployments. 2024. — **Emerging**.

---

### Link bundle (for convenience)

[1] SybilGuard (SIGCOMM ’06) — https://www.math.cmu.edu/~adf/research/SybilGuard.pdf  
[2] SybilLimit (IEEE S&P ’08) — https://www.comp.nus.edu.sg/~yuhf/yuh-sybillimit.pdf  
[3] SybilInfer (NDSS ’09) — https://www.princeton.edu/~pmittal/publications/sybilinfer-ndss09.pdf  
[4] SybilRank (NSDI ’12) — https://www.usenix.org/system/files/conference/nsdi12/nsdi12-final42_2.pdf  
[5] Analysis of Sybil defenses — https://ccr.sigcomm.org/online/files/p363.pdf  
[9] Helios (USENIX Security ’08) — https://www.usenix.org/event/sec08/tech/full_papers/adida/adida.pdf  
[12] SBvote (AFT ’23) — https://dl.acm.org/doi/pdf/10.1145/3555776.3578603  
[13] Groth16 — (overview) https://www.semanticscholar.org/paper/On-the-Size-of-Pairing-Based-Non-interactive-Groth/510aec2a12d43bbd6ddb85d09def188273f6c024  
[14] Halo 2 explainer — https://electriccoin.co/blog/explaining-halo-2/  
[15] STARK overview — https://rdi.berkeley.edu/berkeley-desys/assets/material/lec5_eli_ben_sasson_zk_stark.pdf  
[16] MACI docs — https://maci.pse.dev/  
[18] FIPS‑203 ML‑KEM — https://csrc.nist.gov/pubs/fips/203/final  
[19] FIPS‑204 ML‑DSA — https://csrc.nist.gov/pubs/fips/204/final  
[20] FIPS‑205 SLH‑DSA — https://csrc.nist.gov/pubs/fips/205/final  
[21] PQXDH — https://signal.org/blog/pqxdh/  
[24] RFC 9420 (MLS) — https://www.rfc-editor.org/info/rfc9420  
[25] Noise — https://noiseprotocol.org/noise.pdf  
[26] Double Ratchet — https://signal.org/docs/specifications/doubleratchet/doubleratchet.pdf  
[27] RFC 9000 (QUIC) — https://www.rfc-editor.org/info/rfc9000  
[28] Tor (USENIX ’04) — https://www.usenix.org/conference/13th-usenix-security-symposium/tor-second-generation-onion-router  
[29] Loopix (USENIX ’17) — https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-piotrowska.pdf  
[30] SoK Metadata‑Protecting Comms (PoPETs ’24) — https://petsymposium.org/popets/2024/popets-2024-0030.pdf  
[31] Continuous stop‑and‑go mixnets (PoPETs ’24) — https://petsymposium.org/popets/2024/popets-2024-0136.pdf  
[33] Tendermint (thesis) — https://knowen-production.s3.amazonaws.com/uploads/attachment/file/1814/Buchman_Ethan_201606_Msater%2Bthesis.pdf  
[34] HotStuff (SIGACT/CCS ’19) — https://dl.acm.org/doi/pdf/10.1145/3293611.3331591  
[35] Narwhal/Tusk — https://arxiv.org/pdf/2105.11827  
[36] Bullshark (CCS ’22) — https://dl.acm.org/doi/10.1145/3548606.3559361  
[37] Verkle trees — https://math.mit.edu/research/highschool/primes/materials/2018/Kuszmaul.pdf  
[38] TUF project — https://theupdateframework.io/  
[39] in‑toto (USENIX ’19) — https://www.usenix.org/system/files/sec19-torres-arias.pdf  
[40] Reproducible Builds — https://reproducible-builds.org/  
[41] SPDX 3.0.1 — https://spdx.github.io/spdx-spec/v3.0.1/  
[42] CycloneDX spec — https://github.com/CycloneDX/specification  
[45] Dwork & Roth (book) — https://www.cis.upenn.edu/~aaroth/Papers/privacybook.pdf  
[46] Census TopDown brief — https://www2.census.gov/library/publications/decennial/2020/census-briefs/c2020br-04.pdf  
[47] TopDown algorithm (paper) — https://systems.cs.columbia.edu/private-systems-class/papers/Abowd2022Census.pdf  
[49] Google Research — DP heatmaps — https://research.google/blog/differentially-private-heatmaps/  
[50] PPMF Tech Docs (2024) — https://www2.census.gov/programs-surveys/decennial/2020/technical-documentation/complete-tech-docs/privacy-protected-microdata-file/2020census-privacy-protected-microdata-file.pdf  
[51] W3C DID Core — https://www.w3.org/TR/did-core/  
[52] CanDID (IEEE S&P ’21) — (program page) https://www.ieee-security.org/TC/SP2021/program.html  
[53] Personhood Credentials — https://arxiv.org/abs/2408.07892  
[54] DIDs/VCs survey — https://arxiv.org/abs/2402.02455  
[55] MACI overview (ecosystem) — https://support.gitcoin.co/gitcoin-knowledge-base/gitcoin-grants-program/mechanisms/maci

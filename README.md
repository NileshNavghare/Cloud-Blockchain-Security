# 📘 **Cloud and Blockchain Security**

## **(A Complete Unit-Wise Reference Book)**

**As per Rev-2024 Syllabus**

---

# 🧱 **UNIT 1: BLOCKCHAIN TECHNOLOGY**

![Image](https://d32myzxfxyl12w.cloudfront.net/assets/images/article_images/bb5cbccab13a4a4e651a942f9abfee83b26e8ac9.webp?1702474556=)

![Image](https://media.geeksforgeeks.org/wp-content/uploads/20221111160733/Structureofblocksinblockchain.png)

![Image](https://vezgo.com/blog/wp-content/uploads/2024/05/Public-vs-Private-Blockchain.png)

![Image](https://www.researchgate.net/profile/Georgios_Michail_Makrakis/publication/329519998/figure/fig1/AS%3A701878534946816%401544352291030/What-is-Distributed-Ledger-Technology.jpg)

---

## 1.1 Introduction to Blockchain

Blockchain is a **distributed and decentralized digital ledger** used to record transactions in a **secure, transparent, and tamper-proof manner**. Instead of storing data in a single central server, blockchain stores identical copies of data across **multiple nodes** in a network.

Each transaction is grouped into a **block**, and each block is linked to the previous block using **cryptographic hash values**, forming a continuous chain called a **blockchain**.

### Why Blockchain Was Introduced

Traditional systems depend on:

* Central authorities
* Manual verification
* Third-party trust
* Single point of failure

Blockchain removes these limitations by:

* Eliminating intermediaries
* Using cryptography for trust
* Enforcing consensus among nodes

> **Core Philosophy:**
> *Trust is achieved through mathematics and algorithms, not institutions.*

---

## 1.2 Key Characteristics of Blockchain

### 1. Decentralization

In blockchain, data is not stored on a single server. Instead, it is distributed across multiple nodes.
This eliminates:

* Central control
* Single point of failure
* Data monopoly

### 2. Immutability

Once data is written to a blockchain, it **cannot be altered or deleted**.
This is achieved using **hash linking** between blocks.

### 3. Transparency

All transactions are visible to network participants, ensuring accountability.

### 4. Trustless Operation

Participants do not need to trust each other. The system itself enforces trust using cryptographic rules.

### 5. Security

Blockchain uses:

* Hash functions
* Digital signatures
* Consensus mechanisms

| Feature       | Meaning              |
| ------------- | -------------------- |
| Decentralized | No central authority |
| Immutable     | Cannot be changed    |
| Transparent   | Publicly verifiable  |
| Secure        | Cryptography-based   |

---

## 1.3 Types of Blockchains

### Public Blockchain

* Open to anyone
* Permissionless
* Highly decentralized

**Example:** Bitcoin

### Private Blockchain

* Controlled by one organization
* Faster performance
* Restricted access

**Example:** Enterprise supply chain systems

### Consortium Blockchain

* Controlled by a group of organizations
* Common in banking and finance

### Private Instance of Public Blockchain

* Uses public blockchain technology
* Restricted participation

**Example:** Enterprise Ethereum

| Blockchain Type | Control    | Access     |
| --------------- | ---------- | ---------- |
| Public          | Community  | Open       |
| Private         | Single Org | Restricted |
| Consortium      | Group      | Restricted |

---

## 1.4 Blockchain vs Traditional Database

| Parameter    | Blockchain    | Database    |
| ------------ | ------------- | ----------- |
| Ownership    | Distributed   | Centralized |
| Data Change  | Immutable     | Editable    |
| Trust Model  | Cryptographic | Admin-based |
| Failure Risk | Very low      | High        |

**Conclusion:**
Blockchain is best for **trustless, auditable systems**, while databases are suitable for **internal applications**.

---

## 1.5 Distributed Ledger Technology (DLT)

DLT is the underlying technology where:

* Every node maintains a copy of the ledger
* All copies remain synchronized
* Consensus ensures data consistency

### Advantages of DLT

* High fault tolerance
* Transparency
* Security

---

## 1.6 Block Creation Process

### Step-by-Step Process

```
1. Transaction initiated
2. Transaction broadcast to nodes
3. Validation by network
4. Block formation
5. Hash calculation
6. Consensus achieved
7. Block added to chain
8. Ledger updated
```

---

## 1.7 Structure of a Block

### Block Header

* Previous block hash
* Timestamp
* Nonce
* Merkle Root

### Block Body

* List of validated transactions

**Security Insight:**
Any modification changes the hash and breaks the chain.

---

## 1.8 Initial Coin Offerings (ICO)

ICO is a **blockchain-based fundraising mechanism** where organizations issue digital tokens to raise capital.

### Advantages

* No intermediaries
* Global reach
* Fast fundraising

### Risks

* Lack of regulation
* Fraud
* Market volatility

---

### 📝 **UNIT 1 – Points to Remember**

* Blockchain is immutable
* Hash linking ensures integrity
* Consensus ensures trust

---

# 🔐 **UNIT 2: CRYPTOGRAPHY AND CRYPTOCURRENCIES**

![Image](https://assets.bytebytego.com/diagrams/0349-symmetric-encryption-vs-asymmetric-encryption.png)

![Image](https://www.thesslstore.com/blog/wp-content/uploads/2021/01/how-hashing-works-breakdown-1024x640.png)

![Image](https://comodosslstore.com/blog/wp-content/uploads/2017/05/digital-signature.jpg)

![Image](https://bitcoin.design/assets/images/guide/how-it-works/transactions/inputs-and-outputs.svg)

![Image](https://www.researchgate.net/publication/370561031/figure/fig1/AS%3A11431281159206754%401684312419230/System-Architecture-Diagram-for-Ethereum-Smart-Contract-in-Supply-Chain-Management.png)

---

## 2.1 Introduction to Cryptography

Cryptography is the science of **protecting information** by transforming it into an unreadable format using mathematical algorithms.

### Security Objectives

1. Confidentiality
2. Integrity
3. Authentication
4. Non-repudiation

---

## 2.2 Symmetric Key Cryptography

Uses the **same key** for encryption and decryption.

### Advantages

* Fast
* Efficient for large data

### Limitation

* Secure key sharing is difficult

| Algorithm | Description     |
| --------- | --------------- |
| AES       | Secure and fast |
| DES       | Obsolete        |

---

## 2.3 Asymmetric Key Cryptography

Uses **two keys**:

* Public Key
* Private Key

### Advantages

* Secure key exchange
* Enables digital signatures

| Algorithm | Usage                |
| --------- | -------------------- |
| RSA       | Secure communication |
| ECC       | Blockchain wallets   |

---

## 2.4 Hash Functions

Hash functions convert input data into a **fixed-length output**.

### Properties

* One-way
* Collision-resistant
* Deterministic

| Hash Algorithm | Use        |
| -------------- | ---------- |
| SHA-256        | Bitcoin    |
| MD5            | Deprecated |

---

## 2.5 Digital Signatures

Digital signatures ensure **authentication and integrity**.

### Signing

```
Message → Hash → Encrypt with Private Key → Signature
```

### Verification

```
Decrypt with Public Key → Compare Hash
```

---

## 2.6 Bitcoin

Bitcoin is a **decentralized peer-to-peer digital currency**.

### Key Features

* Proof of Work
* Limited supply
* No central authority

### Ecosystem

* Miners
* Nodes
* Wallets
* Exchanges

---

## 2.7 Cryptocurrency Wallets

| Wallet   | Description      |
| -------- | ---------------- |
| Software | Easy access      |
| Hardware | Highest security |
| Paper    | Offline storage  |

---

## 2.8 Ethereum

Ethereum supports **smart contracts**, which are self-executing programs stored on blockchain.

### Applications

* DeFi
* NFTs
* Supply chain tracking

---

### 📝 **UNIT 2 – Points to Remember**

* Hash ≠ Encryption
* Private key = ownership
* Ethereum enables automation

---

# 🕵️ **UNIT 3: CYBER CRIMES AND CYBER OFFENSES**

![Image](https://www.researchgate.net/publication/347143188/figure/fig1/AS%3A970424615723009%401608378666777/The-Classification-of-Cybercrime-13.png)

![Image](https://www.imperva.com/learn/wp-content/uploads/sites/13/2019/01/social-engineering.png)

![Image](https://www.indusface.com/wp-content/uploads/2019/08/2.jpg)

![Image](https://www.cloudflare.com/resources/images/slt3lc6tev37/oUd084IG6Zq2dW6mI1TT7/891a2c62bec90326d560326e8790a5ed/what_is_an_attack_vector.png)

![Image](https://d2ds8yldqp7gxv.cloudfront.net/Blog%2BExplanatory%2BImages/Cloud%2BCyber%2BAttacks%2B1.webp)

---

## 3.1 Cyber Crime Definition

Cybercrime refers to **illegal activities carried out using computers, networks, or digital systems**.

---

## 3.2 Classification of Cyber Crimes

| Category            | Example         |
| ------------------- | --------------- |
| Against Individuals | Identity theft  |
| Against Property    | Ransomware      |
| Against Government  | Cyber terrorism |

---

## 3.3 Cyber Kill Chain

The cyber kill chain describes the **stages of an attack**.

```
Reconnaissance →
Weaponization →
Delivery →
Exploitation →
Installation →
Command & Control →
Actions
```

---

## 3.4 Social Engineering

Social engineering attacks manipulate **human psychology**.

| Attack   | Explanation   |
| -------- | ------------- |
| Phishing | Fake emails   |
| Vishing  | Phone fraud   |
| Baiting  | Malicious USB |

---

## 3.5 Botnets

Botnets are **networks of infected devices** controlled by attackers.

### Uses

* DDoS attacks
* Spam campaigns

---

## 3.6 Cyber Crime and Cloud Computing

Cloud environments introduce:

* Shared responsibility risks
* Misconfiguration vulnerabilities
* Identity-based attacks

---

### 📝 **UNIT 3 – Points to Remember**

* Humans are weakest link
* Misconfiguration is major cloud risk

---

# ☁️ **UNIT 4: CLOUD SECURITY CONCEPTS, COMPLIANCE AND IDENTITY**

![Image](https://learn.microsoft.com/en-us/azure/security/fundamentals/media/shared-responsibility/shared-responsibility.svg)

![Image](https://miro.medium.com/1%2AwYUTKw8NHxvlZ1YZ6o1NNA.png)

![Image](https://www.brickworkindia.com/AdminFiles/What-is-Zero-Trust-Architecture-_1.jpg)

![Image](https://curity.io/images/resources/neo_security/curity-authentication-vs-authorization-article-image.svg)

![Image](https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/identity/images/active-directory-federation-services.svg)

---

## 4.1 Shared Responsibility Model

Security responsibility is shared between:

* Cloud Provider
* Customer

| Provider    | Customer  |
| ----------- | --------- |
| Physical DC | Data      |
| Hardware    | Identity  |
| Network     | OS & Apps |

---

## 4.2 Defense in Depth

Defense in depth uses **multiple layers of security**.

```
Perimeter → Network → Host → Application → Data
```

---

## 4.3 Zero Trust Model

Zero Trust assumes **no implicit trust**.

### Principles

* Verify explicitly
* Least privilege
* Continuous monitoring

---

## 4.4 Identity as Security Perimeter

In cloud computing:

* Network boundaries disappear
* Identity becomes primary security control

---

## 4.5 Authentication vs Authorization

| Authentication | Authorization   |
| -------------- | --------------- |
| Who you are    | What you can do |

---

## 4.6 Active Directory and Federation

* Central identity management
* Federation allows cross-organization authentication

---

### 📝 **UNIT 4 – Points to Remember**

* Identity is new perimeter
* Zero Trust is modern standard

---

# 🆔 **UNIT 5: CAPABILITIES OF CLOUD ACTIVE DIRECTORY**

![Image](https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/identity/images/azure-active-directory.svg)

![Image](https://learn.microsoft.com/en-us/entra/identity/hybrid/connect/media/reference-connect-ports/required3.png)

![Image](https://learn.microsoft.com/en-us/entra/identity/conditional-access/media/plan-conditional-access/conditional-access-overview-how-it-works.png)

![Image](https://azure-training.com/wp-content/uploads/2022/03/pim5.png)

---

## 5.1 Azure Active Directory

Azure AD is a **cloud-based IAM service** used to manage identities and access.

---

## 5.2 Azure AD Identity Types

| Type       | Description          |
| ---------- | -------------------- |
| Cloud Only | Cloud users          |
| Hybrid     | On-prem synced users |
| External   | Guest users          |

---

## 5.3 Authentication Methods

* Password
* Multi-Factor Authentication
* Passwordless
* Certificate-based

---

## 5.4 Conditional Access

Controls access based on:

* Location
* Device state
* Risk level

---

## 5.5 Role-Based Access Control (RBAC)

RBAC ensures **least privilege access**.

---

## 5.6 Privileged Identity Management (PIM)

PIM provides:

* Just-in-time admin access
* Time-bound privileges

---

### 📝 **UNIT 5 – Points to Remember**

* MFA prevents most attacks
* PIM reduces admin risk

---

# 🛡️ **UNIT 6: CLOUD SECURITY SOLUTIONS**

![Image](https://learn.microsoft.com/en-us/azure/ddos-protection/media/ddos-best-practices/ddos-protection-overview-architecture.png)

![Image](https://learn.microsoft.com/en-us/azure/firewall/media/features-by-sku/firewall-overview.png)

![Image](https://www.cloudflare.com/img/learning/ddos/glossary/waf/waf.png)

![Image](https://learn.microsoft.com/en-us/azure/bastion/media/bastion-overview/architecture.png)

![Image](https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/media/microsoft-sentinel-automated-response-architecture.svg)

---

## 6.1 Network Security Solutions

| Tool            | Purpose                |
| --------------- | ---------------------- |
| DDoS Protection | Prevent traffic floods |
| Firewall        | Stateful filtering     |
| NSG             | Network access rules   |
| Bastion         | Secure VM access       |

---

## 6.2 Data Protection

* Encryption at rest
* Encryption in transit
* Secure key management

---

## 6.3 Cloud Security Posture Management (CSPM)

CSPM continuously monitors cloud security posture.

---

## 6.4 Microsoft Defender for Cloud

* Threat detection
* Secure score
* Compliance management

---

## 6.5 SIEM and SOAR

| SIEM             | SOAR               |
| ---------------- | ------------------ |
| Log analysis     | Automated response |
| Threat detection | Remediation        |

---

## 6.6 Microsoft Sentinel

Microsoft Sentinel is a **cloud-native SIEM** with AI-driven analytics.

---

### 📝 **UNIT 6 – Points to Remember**

* Cloud security requires automation
* Security = Prevent + Detect + Respond

---
- Nilesh Navghare

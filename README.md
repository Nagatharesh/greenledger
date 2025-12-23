# GreenLedger

**Farm-to-fork transparency using a blockchain-inspired ledger system.**

GreenLedger is an agri-supply chain transparency platform that demonstrates how farmers, agents (warehouses/government), and consumers can interact on a **tamper-resistant, traceable transaction flow**. The project focuses on **eliminating opacity and middleman manipulation** by making every step auditable.

> ⚠️ This is a **prototype**. All data, users, and transactions are simulated to demonstrate system design and flow.

---

## 🎯 Problem Statement

India’s agricultural supply chain suffers from:

* Price manipulation by intermediaries
* No transparent record of crop movement
* Farmers lacking visibility into final selling price
* Consumers unable to verify product origin

Existing systems (eNAM, APMC portals) focus on marketplaces — **not immutable traceability**.

---

## 💡 Solution Overview

GreenLedger introduces a **ledger-driven supply chain model** where:

* Every crop batch is logged at source (farmer)
* Transfers are recorded through agents/warehouses
* Consumers can trace products back to origin
* Records are append-only and verifiable

Blockchain is **simulated** to focus on architecture, logic, and governance feasibility.

---

## 👥 Roles & System Flow

### 🌱 Farmer

* Registers crop batch
* Declares quantity, quality, and base price
* Initiates first ledger entry

### 🏢 Agent (Warehouse / Authority)

* Verifies incoming produce
* Records storage, grading, and transfer
* Acts as a regulated validator

### 🛒 Consumer

* Views product details
* Traces complete journey (farm → warehouse → market)
* Verifies authenticity and pricing history

---

## 🔗 Ledger Concept (Simulated Blockchain)

Each transaction block contains:

* Previous hash
* Current transaction data
* Timestamp
* Actor role (Farmer / Agent / Consumer)

This ensures:

* Immutability (no silent edits)
* Full traceability
* Audit-ready records

---

## 🏗️ System Architecture

```
Frontend  : React / HTML-CSS-JS
Ledger    : Simulated Blockchain Logic
Storage   : Local / JSON-based (Prototype)
Roles     : Farmer, Agent, Consumer
```

> Designed to be **blockchain-portable** (can be migrated to Hyperledger / Ethereum).

---

## 🖥️ User Interface

* Minimal, clean role-based entry screen
* Clear separation of responsibilities
* Focus on clarity over visual noise

Roles are intentionally explicit to reflect **real-world governance**.

---

## 🔐 Security & Integrity (Conceptual)

* Append-only transaction design
* Role-based permissions
* Hash-linked records
* Audit-friendly data model

Smart contracts are **conceptually mapped**, not deployed.

---

## 🚧 Limitations (Intentional)

* No real blockchain network (simulation only)
* No real payments
* No Aadhaar / KYC integration
* No live government APIs

These are out of scope for an academic prototype.

---

## 🔮 Future Scope

* Hyperledger Fabric integration
* Government-run validator nodes
* Smart contracts for MSP enforcement
* Seed, fertilizer, and subsidy tracking
* Integration with eNAM instead of replacement

---

## 📌 Project Intent

GreenLedger is built to:

* Demonstrate **how** blockchain fits agriculture
* Show **where** current systems fail
* Propose a **governance-ready architecture**

It is not a crypto project. It is a **transparency project**.

---

## 📄 Disclaimer

This project is developed for academic, research, and demonstration purposes only. It does not represent an official government system or live agricultural marketplace.

---

## 👤 Author

**Naresh Kotti**
Engineering Student | System Design & Applied Blockchain

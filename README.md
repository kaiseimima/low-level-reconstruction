# Low-Level Engineering Mastery
## Reconstructing Computer Systems from Scratch with Rust

## 🚀 Overview
This repository documents a multi-year journey to master the fundamentals of computer science by rebuilding core systems from the ground up. 

In a world of high-level abstractions, this project aims to demystify the "magic" of modern computing. By focusing on manual implementation in Rust, I seek to gain a profound understanding of the boundary between hardware and software.

## 🛠 Project Roadmap

### Phase 1: Compiler
**"Mastering Language Internals"**
- **Goal:** Build a compiler for a C-subset language.
- **Focus:** Tokenizing, AST Parsing, Code Generation (ARM64/x86-64), and Self-hosting.
- **Objective:** Understand how high-level code is transformed into machine instructions and master memory layouts.

### Phase 2: TCP/IP Stack
**"Defining the Laws of Communication"**
- **Goal:** Implement a network stack without using OS standard libraries.
- **Focus:** Ethernet, ARP, IPv4, ICMP, and TCP (Retransmission & Congestion Control).
- **Objective:** Gain packet-level control over communications and understand the backbone of cloud infrastructure.

### Phase 3: Operating System
**"Dominating the Hardware"**
- **Goal:** Develop a microkernel that runs on bare metal.
- **Focus:** Bootloaders, Memory Management (Paging), Multitasking, and System Calls.
- **Objective:** Control CPU/Memory resources directly to understand virtualization and containerization at their core.

### Phase 4: Browser Engine
**"Deconstructing the Web Pipeline"**
- **Goal:** Create a rendering engine that parses and displays HTML/CSS.
- **Focus:** DOM/CSSOM Construction, Layout Algorithms, and Painting.
- **Objective:** Understand the structural mechanics of how information is visualized in a modern web environment.

### Phase 5: Distributed KVS
**"Reaching the Truth of Distributed Systems"**
- **Goal:** Build a highly available, scalable distributed storage system.
- **Focus:** Raft/Paxos Consensus, Data Replication, and CAP Theorem.
- **Objective:** Master the trade-offs of consistency and availability required for planet-scale system design.

---

## 📝 Learning Philosophy
1. **No Magic:** Avoid opaque libraries; implement core logic from scratch.
2. **Document First:** Define design specifications and rationale before writing code.
3. **Rust as a Weapon:** Leverage Rust's safety and performance across all phases.
4. **Theory to Practice:** Translate RFCs and academic papers directly into working implementations.

---

## 📂 Repository Structure
```text
.
├── README.md           # This roadmap
├── phase1-compiler/    # Compiler project (Rust)
├── phase2-tcpip/       # Network stack (Future)
├── phase3-os/          # Operating system (Future)
├── phase4-browser/     # Browser engine (Future)
└── phase5-kvs/         # Distributed system (Future)
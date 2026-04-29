# 🦀 Vault CLI (Rust)
> A lightning-fast command-line interface for encrypted note management and local file vaulting.

---

## 📖 Overview
Built with **Rust**, this CLI tool focuses on performance and data safety. It manages local persistent storage with strict ownership rules, demonstrating my proficiency in memory-safe languages and low-level file manipulation.

## ✨ Key Features
- 🚀 **Zero-Cost Abstractions**: High-speed data processing using Rust.
- 📦 **Serde Integration**: Efficient JSON serialization/deserialization for note persistence.
- ⌨️ **Intuitive CLI**: Action-based commands (add, list, patch, delete) with descriptive error handling.

## 🛠 Tech Stack
- **Language**: Rust (Edition 2021).
- **Libraries**: Serde, Serde_JSON, Rand.

## 🚀 Usagebash
# Build the project
cargo build --release

# Add a note
./vault-cli notes.json add "New Note"

# List notes
./vault-cli notes.json list

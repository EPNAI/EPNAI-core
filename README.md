# EPNAI Core
![EPNAI](https://github.com/user-attachments/assets/5166f9de-a290-4be5-817e-c8394221c3f7)

## Overview
The core protocol logic for Machine-Centric Protocol (EPNAI) on Solana. This repository contains the fundamental Solana programs (smart contracts) that power the EPNAI ecosystem.

## Components
- **Registry Layer**: Agent, context, and permission management
- **Execution Tracking**: Transaction monitoring and metering
- **IDL Files**: Anchor-compatible interface definition files
- **Client Bindings**: JavaScript/TypeScript SDK for Solana using Anchor

## Development Setup
```bash
# Install dependencies
npm install

# Build the Solana programs
anchor build

# Run tests
npm test
```

## Repository Structure
- `/programs` - Solana smart contracts written in Rust with Anchor
- `/clients` - JavaScript/TypeScript SDK for interacting with EPNAI
- `/tests` - Unit and integration tests
- `/.github` - CI/CD workflows for testing and deployment

## Links
- [Documentation](https://github.com/EPNAI/EPNAI-docs)
- [Examples](https://github.com/EPNAI/EPNAI-examples)
- [Agents](https://github.com/EPNAI/EPNAI-agents)
- [Server](https://github.com/EPNAI/EPNAI-server)

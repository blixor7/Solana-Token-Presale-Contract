# Solana Token Presale Contract

A sophisticated Solana smart contract for managing token presales with allocation-based participation. Built with Anchor framework to provide secure and flexible token sale mechanics.

## Core Features

- Dual-Phase Sales: Configurable presale and public sale periods with separate timing controls
- Allocation Ticket System: Reserve purchase spots during presale phase
- SPL Token Integration: Native support for Solana Program Library tokens
- Customizable Parameters: 
  - Presale/public sale start/end times
  - Token pricing structure
  - Allocation limits per ticket
  - Flexible configuration options

## Prerequisites

Ensure you have the following installed:

- Rust (latest stable version)
- Cargo (Rust package manager)
- Anchor CLI
- Node.js (v16 or higher)
- Yarn package manager

## Quick Start

1. Clone & Setup
```bash
git clone https://github.com/blixor7/Solana-Token-Presale-Contract.git
cd Solana-Presale-Smart-Contract
yarn install
```

2. Build Contract
```bash
anchor build
```

3. Run Test Suite
```bash
anchor test
```

4. Deploy
```bash
# Switch to your target network first
anchor deploy
```

## Project Structure

```
Solana-Presale-Smart-Contract/
- programs/                 # Anchor program source
- tests/                   # Test suites
- migrations/              # Deployment scripts
- app/                     # Frontend integration (if applicable)
```

## Usage

The contract enables project creators to:
- Set up timed presale phases with exclusive access
- Manage allocation tickets for fair distribution
- Handle SPL token sales with customizable parameters
- Transition smoothly between presale and public sale phases

Built with security and flexibility in mind for Solana token launches.

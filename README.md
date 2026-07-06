# GitScout Casper Oracle Agent 🔍

An autonomous AI data oracle agent powered by Casper x402 micropayments.

## What it does
GitScout autonomously collects, verifies, and publishes data on-chain 
on Casper Network — paying per request via x402 protocol and earning 
CSPR for every data point served.

## Features
- ✅ Autonomous data collection agent
- ✅ ZK proof generation and verification
- ✅ x402 micropayment integration (pay-per-request)
- ✅ On-chain data publishing to Casper
- ✅ Agent earns CSPR automatically

## Tech Stack
- Rust
- Casper Network
- x402 Protocol
- Zero Knowledge Proofs
- Odra Framework

## How it works
1. Agent requests data via x402 — pays 0.003 CSPR per request
2. Data is collected and ZK proof generated
3. Verified data published on Casper blockchain
4. Other agents pay to consume the verified data
5. GitScout earns CSPR automatically 24/7

## Run it
```bash
cargo run
```

## Hackathon
Built for Casper Agentic Buildathon 2026 on DoraHacks
Track: Agentic AI

## 🧪 Testing Instructions (Step by Step)

### Prerequisites
- Rust installed (`rustup.rs`)
- Git installed

### Step 1 — Clone the repo
```bash
git clone https://github.com/Investordaniel-lgtm/gitscout-casper
cd gitscout-casper
```

### Step 2 — Run the agent
```bash
cargo run
```

### Step 3 — Expected output
- ✅ x402 payment simulation on Casper
- ✅ 5 data points collected and verified
- ✅ ZK proofs generated for each data point
- ✅ Agent earnings summary in CSPR displayed

## 🔗 Contract Details
- **Network:** Casper Testnet
- **Stack:** Rust, x402 Protocol, ZK Proofs, Odra Framework
- **Agent type:** Autonomous data oracle

## 🏆 Hackathon
Built for **Casper Agentic Buildathon 2026** on DoraHacks
- Track: Agentic AI
- Built in under 24 hours

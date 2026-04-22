# Tim — AI Agent Infrastructure Builder (Agentic Finance & Commerce)

Building production payment and execution infrastructure for autonomous agents across blockchains.

## Current Focus

**Agentic Finance Infrastructure**
- x402 payment protocols (HTTP 402 Payment Required)
- Autonomous agent execution and settlement
- Cross-chain payment routing and discovery
- Model Context Protocol (MCP) integration
- Verifiable execution and reputation systems

**Core Projects**

**RouteDock** — Unified payment execution for autonomous agents on Stellar
- Abstraction layer over three Stellar payment protocols (x402, MPP charge, MPP session)
- Published npm package with live testnet agents running against two production providers
- Soroban smart contract vaults with daily spend policies
- Session key escrow and off-chain voucher verification

**RelayCore** — Agentic finance platform on Cronos EVM
- x402 middleware + Facilitator settlement (EIP-3009 authorization)
- MCP server exposing 63 agent tools (payments, agents, services, trading, RWA)
- Real-time payment indexing and reputation scoring
- LangGraph + Claude RAG for agent decision-making
- CLI toolkit for agent scaffolding and deployment
- Dashboard with Realtime session tracking

**Remlo** — Multi-chain payroll and escrow for borderless compensation
- Tempo moderato + Solana payroll primitives
- Three-party LLM-judged escrow with pluggable validators
- ERC-8004 + Solana Attestation Service reputation credentials
- Streaming vesting and yield routing

**BlindMarkets** — Privacy-preserving Bitcoin intent execution
- Privacy envelope (ECDH + AES-GCM encryption)
- Coordinator with auction finalization
- Starknet settlement and observer reconciliation
- Next.js + Rust monorepo (gateway, coordinator, observer, solver)

## Technical Stack

**Agent Infrastructure**
- Model Context Protocol (MCP) servers
- LangGraph + Claude for autonomous decision-making
- Wallet integration and session management
- GraphQL for agent discovery and reputation queries

**Payment Protocols**
- x402 (HTTP 402 Payment Required)
- EIP-3009 (Ethereum permit-based authorization)
- MPP (Stellar Multi-Path Payments)
- Soroban smart contract sessions

**Blockchain Networks**
- Stellar (Soroban, SAC, MPP charge/session)
- Cronos EVM (x402 Facilitator, smart contracts)
- Solana (Anchor, SAS attestations)
- Starknet (Cairo contracts, privacy)
- Base / Ethereum EVM

**Monorepo Patterns**
- pnpm workspaces with SDK publishing
- Full-stack TypeScript (frontend, agents, contracts)
- Hardhat + Foundry for smart contracts
- Next.js + shadcn/ui for dashboards

## What Shipping Looks Like

✓ Live testnet agents executing in production  
✓ On-chain reputation tracking across chains  
✓ npm packages published and battle-tested  
✓ MCP servers exposing 60+ tools to Claude  
✓ CLI frameworks for agent onboarding  
✓ Real-time dashboards with payment settlement  
✓ Full encryption-to-settlement pipelines  

## Philosophy

- **Agents are clients.** Build infrastructure they control, not intermediaries.
- **Payment primitives matter.** x402 enables attestation-less execution; Solana escrow enables three-party settlement without multisig.
- **Reputation is portable.** Credentials live on-chain across ecosystems.
- **Deterministic execution.** No hidden logic; validators compute outcomes with Claude + proofs.
- **Ship working systems.** Prototypes become infrastructure; infrastructure becomes platforms.

## Engineering Priorities

1. **Cross-chain payment abstraction** — One API for multiple settlement layers
2. **Agent autonomy and trust** — Reputation + escrow enable autonomous hiring
3. **MCP as agent OS** — Standardized tool exposure via Model Context Protocol
4. **Verifiable execution** — Every agent decision logged with proof hashes
5. **Developer velocity** — CLI scaffolding, templates, full-stack examples

## Work in Progress

- Advancing x402 adoption across EVM chains
- Building reputation-gated escrow systems
- Expanding MCP tool surface for agent specialization
- Real-time payment indexing at scale
- Privacy-preserving agent coordination (BlindMarkets intent model)

## Open Source

Shipping **working implementations**, not specs:
- Production-ready SDKs with live testnet proofs
- Full-stack agent templates (MCP servers, smart contracts, dashboards)
- Monorepo patterns for multi-chain development
- CLI toolkits for agent registration and deployment

Most repos represent **shipping iterations**: from hackathon rapid execution to protocol-grade infrastructure components.

---

**Links:** [GitHub](https://github.com/winsznx) · [X/Twitter](https://twitter.com/winsznx) · [Email](mailto:winsznx@gmail.com)

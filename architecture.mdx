---
title: "Architecture"
description: "Real-time risk analysis powered by Solana RPC, Redis caching, and WebSocket streaming"
---

Pump Guard is built as a lightweight, modular system that analyzes tokens in real-time and delivers results instantly to users.

## System Components

### Frontend (React + Vite)
- Token search and address validation
- Live risk reports with visual metrics
- Real-time updates via WebSockets
- Recent scans tracking with local storage

### Backend (Node.js + Express)
- REST API for token analysis
- Solana RPC integration for blockchain data
- DexScreener API for market data
- Redis caching for performance
- Socket.io for live updates

### Infrastructure
- **Solana RPC**: Fetches holder balances and wallet history
- **Redis**: Caches wallet data (24h) and risk scores (15s)
- **WebSockets**: Broadcasts scan events to all connected users

## How a Scan Works

1. User enters token address on [pumpguard.xaxios.com](https://pumpguard.xaxios.com)
2. Backend validates address and checks DexScreener for market data
3. System fetches top 50 holders from Solana blockchain
4. Each wallet analyzed: creation date, SOL balance, token amount
5. Risk metrics calculated using our scoring algorithm
6. Results cached and returned to user
7. Scan event broadcast to all connected clients

## Performance Strategy

**Caching**:
- Wallet creation data cached 24 hours (rarely changes)
- Risk scores cached 15 seconds (balance between freshness and speed)
- Token metadata cached indefinitely (immutable)

**Rate Limiting**:
- 2 requests per second per IP
- 10 requests per 15 seconds
- 30 requests per minute

**Real-time Updates**:
- Socket.io broadcasts new scans globally
- Homepage shows community scan activity live
- No page refresh needed

## Tech Stack

**Backend**:
- Express.js + TypeScript
- @solana/web3.js for blockchain
- Redis (ioredis) for caching
- Socket.io for WebSockets
- Axios for external APIs

**Frontend**:
- React 18 + TypeScript
- Vite for fast builds
- Tailwind CSS for styling
- Zustand for state management
- Socket.io-client for live updates

## Open Source

The entire codebase is open source on [GitHub](https://github.com/xaxios/pump-guard-monorepo):

- Full backend and frontend code
- Deployment configurations
- API documentation
- Risk algorithm implementation

Anyone can run their own instance, verify the scoring logic, or contribute improvements.

---

> **Note**: This is a community-focused tool. For production use cases requiring higher throughput or custom metrics, the architecture can be extended with dedicated RPC nodes, gRPC streams, and advanced indexing.

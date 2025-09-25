# AI YieldNet - Cross-Chain USDC Yield Aggregator

A comprehensive DeFi yield aggregation platform that enables seamless cross-chain USDC transfers and automated yield optimization using AI agents.

## 🏗️ Architecture

This is a monorepo containing three main components:

### 📁 Repository Structure

```
aptos-cctp/
├── backend/          # Node.js/TypeScript Backend API
├── contracts/        # Aptos Move Smart Contracts  
├── frontend/         # React/TypeScript Frontend
├── docs/            # Documentation
└── tests/           # Integration Tests
```

## 🚀 Components

### 1. **Backend** (`/backend`)
- **Technology**: Node.js, TypeScript, Express
- **Features**: 
  - CCTP Bridge Integration
  - AI Agent Orchestration
  - Real-time WebSocket Updates
  - Circle Iris API Polling
- **Repository**: [aicctp-backend](https://github.com/Rohanarora17/aicctp-backend)

### 2. **Contracts** (`/contracts`)
- **Technology**: Aptos Move
- **Features**:
  - Native USDC Vault Contract
  - Fungible Asset Integration
  - Resource Account Management
- **Repository**: [aicctp-contracts](https://github.com/Rohanarora17/aicctp-contracts)

### 3. **Frontend** (`/frontend`)
- **Technology**: React, TypeScript, Vite
- **Features**:
  - Aptos Wallet Integration
  - CCTP Bridge Interface
  - Real-time Status Updates
- **Repository**: [aicctp-frontend](https://github.com/Rohanarora17/aicctp-frontend)

## 🔗 CCTP Integration

- **Cross-Chain Protocol**: Circle's CCTP for trustless USDC transfers
- **Supported Chains**: Ethereum, Base, Arbitrum, Optimism, Aptos
- **Real-time Updates**: Server-Sent Events for bridge status
- **AI Optimization**: Automated yield strategy generation

## 🛠️ Development Setup

### Prerequisites
- Node.js 18+
- Aptos CLI
- Git

### Quick Start
```bash
# Clone the repository
git clone https://github.com/Rohanarora17/aptos-cctp.git
cd aptos-cctp

# Install dependencies for each component
cd backend && npm install
cd ../frontend && npm install  
cd ../contracts && npm install

# Start development servers
cd ../backend && npm run dev
cd ../frontend && npm run dev
```

## 📚 Documentation

- [Technical Architecture](./TECHNICAL_ARCHITECTURE.md)
- [CCTP Guidelines](./CCTP_GUIDELINES.md)
- [Complete Flow](./README_COMPLETE_FLOW.md)

## 🤝 Contributing

Each component has its own repository for focused development:
- Backend changes: `aicctp-backend`
- Contract changes: `aicctp-contracts`  
- Frontend changes: `aicctp-frontend`

## 📄 License

MIT License - see LICENSE file for details.
# Project Documentation: Vibe – AI-Assisted Trading dApp on BNB Chain

> The release of Vibe’s open-source code will be made available in the future.  
> During beta, this repository serves as public-facing documentation and a project overview.

## Overview

**Vibe** is an AI-assisted crypto trading application built for the **BNB Chain ecosystem**.  
It combines conversational AI with real-time blockchain data to help users make informed trading decisions through natural language interactions.  
The app follows a "vibe trading" philosophy — think "vibe coding" but for crypto trading — where users can ask questions and get intelligent, data-driven responses about tokens, markets, and trading opportunities.

**Key Philosophy**: This is a **self-custody** application.  
Vibe does not implement custodial accounts or burner wallets. Users connect their own Web3 wallets (e.g., MetaMask, WalletConnect-compatible) and maintain full control of their assets.

---

## Core Functionality

### 🤖 AI-Powered Trading Assistant
- **Natural Language Queries**: Users can ask questions like:
  - "Show me top trending tokens"
  - "Swap 0.1 BNB to USDT"
  - "What’s the technical analysis for BNB?"
  - "Give me news about this token"
- **Real-time Data Integration**: AI uses multiple **Model Context Protocol (MCP)** tools to fetch live on-chain and market data.
- **Intelligent Responses**: AI delivers analysis, recommendations, and actionable insights.

### 🔧 MCP Tools Integration
The AI assistant has access to powerful tools for real-time data:
- **Token Data Tools** – Search metadata and market information.
- **Swap Tools** – Fetch swap quotes and generate ready-to-sign transactions via liquidity aggregators on BNB Chain.
- **Portfolio Tools** – Analyze wallet holdings and performance.
- **Chart Tools** – Fetch OHLCV data for charting and technical analysis.
- **Web Search Tools** – Pull current news and relevant token info.

### 🔄 Trading Workflow
1. **User Query**: User asks about tokens or requests a swap.  
2. **AI Analysis**: AI selects appropriate MCP tools to gather live data.  
3. **Response**: AI provides analysis, swap routes, or technical signals.  
4. **Transaction Generation**: AI prepares a ready-to-sign transaction.  
5. **User Signing**: User executes with their Web3 wallet.  
6. **Self-Custody**: User keeps full control — no intermediaries.  

### 💳 Wallet Integration
- **Self-Custody Model**: Connect via standard EVM wallets (MetaMask, WalletConnect).  
- **BNB Chain Integration**: Seamless transaction signing for token swaps and portfolio tracking.  
- **User-Controlled Signing**: All swaps require explicit wallet approval.  

---

## Technical Architecture
- **Next.js 15 + React 19**: Modern single-page application.  
- **Responsive Layout**: Header, main, and footer optimized for all screens.  
- **AI Runtime**: OpenAI model integrated with MCP tools for generative DeFAI.  
- **Rate Limiting System**: Multi-tier usage with credits and free prompts for wallet users.  
- **Draggable Chart System**: Professional TradingView integration with live OHLCV data.  

---

## Key Features
- **Conversational Swaps** – Execute trades with prompts.  
- **Generative Research** – Token insights and fundamentals powered by AI.  
- **Chart Intelligence** – Real-time TA and indicators.  
- **Portfolio Analysis** – Track, analyze, and rebalance seamlessly.  
- **News & Market Updates** – AI-summarized token and DeFi news.  

---

## Security & Self-Custody
- **No Custodial Services**: Users keep keys and assets.  
- **Wallet Authentication**: Secure wallet connections via EVM standards.  
- **Transaction Verification**: AI-prepared routes, but always user-signed.  
- **Privacy**: No storage of balances or sensitive data.  

---

## Summary
**Vibe** is a next-generation **generative DeFAI dApp** on BNB Chain.  
It unifies **research, execution, and portfolio management** into an **all-in-one conversational interface** where users can trade by prompt.  

By combining **Model Context Protocol (MCP)** with AI-driven insights and on-chain execution, Vibe makes DeFi trading as natural as having a conversation.

**Prompt. Sign. Swap. That’s the vibe.**

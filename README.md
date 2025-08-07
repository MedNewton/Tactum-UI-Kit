# Tactum UI Kit

A curated React TypeScript UI component library designed for Web3 projects — optimized for NFT, DeFi, and generic blockchain interfaces.

---

## 🚀 About

Tactum UI Kit is a modern, lightweight, and extensible UI component library built with React and TypeScript. It aims to accelerate Web3 app development by providing reusable, accessible, and well-tested components tailored for NFT marketplaces, DeFi dashboards, and blockchain utilities.

---

## ⚙️ Features

- Fully typed with TypeScript  
- ESLint + Prettier integration for clean, consistent code style  
- Absolute imports support (`@/components`, `@/types`, etc.)  
- Designed without heavy CSS frameworks — minimal CSS, easily customizable  
- Components covering generic Web3 UI, NFT previews, DeFi-specific cards, and more  
- Tested with React Testing Library for reliability  

---

## 📦 Installation

```bash
npm install tactum-ui-kit
# or
yarn add tactum-ui-kit
```

---

## 🔨 Usage

```tsx
import React from 'react';
import { NFTPreviewCard, TokenSwapInterface } from 'tactum-ui-kit';

function App() {
  return (
    <div>
      <NFTPreviewCard tokenName="Cool NFT" price="2.5 ETH" />
      <TokenSwapInterface />
    </div>
  );
}

export default App;
```

---

## 🧰 Development

Clone the repo and install dependencies:

```bash
git clone https://github.com/yourusername/tactum-ui-kit.git
cd tactum-ui-kit
npm install
```

Run in development mode:

```bash
npm start
```

Run lint and fix issues:

```bash
npm run lint
npm run format
```

Run tests:

```bash
npm test
```

---

## 🧩 Included Components

### Generic Web3

- User Profile Card  
- Balance Card  
- Portfolio Distribution Card  
- Holdings Table  
- Token Card  
- Notification Feed  
- Activity Timeline  
- Stats Overview Cards  
- Transaction Summary Card  
- Compact Token List  
- Data Breakdown Card  
- Multi-Chain Wallet Overview  
- Mini KPI Grid  
- Compact Address Tag  
- Compact Chart Card  

### NFT Specific

- NFT Preview Card  
- NFT Detail View  
- Collection Overview Component  

### DeFi Specific

- Asset Balance Card  
- Token Swap Interface  
- APR / APY Yield Card  
- Transaction History Feed  
- Staking/Farming Card  

---

## ⚖️ Code Quality

- ESLint with Airbnb + TypeScript rules  
- Prettier for formatting  
- VSCode recommended settings provided  
- Absolute import path aliases configured via `tsconfig.json`

---

## 🔗 Links

- [Repository](https://github.com/yourusername/tactum-ui-kit)  
- [Issue Tracker](https://github.com/yourusername/tactum-ui-kit/issues)  
- [Changelog](https://github.com/yourusername/tactum-ui-kit/releases)

---

## 📄 License

MIT License © 2025 Tactum

# Chainmind

# ChainMind — AI Wallet Intelligence

**Modern clone of [https://chainmind.lovable.app/](https://chainmind.lovable.app/)**

On-chain wallet analysis powered by AI. Analyze trading patterns, risk profiles, behavior, and portfolio intelligence directly from the blockchain.

![ChainMind Preview](https://chainmind.lovable.app/og-image.png)

## ✨ Features

- Beautiful dark glassmorphic UI (exact match to original)
- Multi-chain support (Ethereum, Base, Solana)
- AI-powered mock wallet analysis with realistic insights
- Tabbed navigation: Analysis • Compare • History
- Responsive design
- Smooth animations with Framer Motion
- Ready for real blockchain + AI integration

## 🚀 Quick Start

```bash
# 1. Create the project
npx create-next-app@latest chainmind-ai-wallet --typescript --tailwind --eslint --app --yes

# 2. Navigate and install dependencies
cd chainmind-ai-wallet
npm install lucide-react framer-motion

# 3. Replace files with the ones from this repo
# 4. Run the dev server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## Tech Stack

- **Next.js 15** (App Router)
- **TypeScript**
- **Tailwind CSS**
- **Lucide React** (icons)
- **Framer Motion** (animations)

## Project Structure

```
chainmind-ai-wallet/
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── WalletInput.tsx
│   ├── AnalysisResult.tsx
│   ├── CompareWallets.tsx
│   └── History.tsx
├── tailwind.config.ts
├── package.json
└── README.md
```

## How It Works

1. Select a chain (Ethereum / Base / Solana)
2. Enter any wallet address (mock data works with any input)
3. Click **Analyze** → Get instant AI-generated insights, risk score, portfolio value, etc.
4. Switch between **Analysis**, **Compare**, and **History** tabs

## Future Enhancements (Easy to Add)

- Real on-chain data using **Moralis**, **Covalent**, or **GenLayer** APIs
- Connect to **OpenAI / Grok / Claude** for dynamic AI insights
- Wallet connection (MetaMask, Phantom, etc.)
- Export analysis as PDF
- Shareable report links



```bash
npm run build
```

## License

MIT License — Feel free to use this for personal or commercial projects.

---

**Made with ❤️ for the Web3 community**
```


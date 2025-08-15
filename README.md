# 🦈 Luneshark - AI-Powered Web3 Platform

A comprehensive Web3 platform featuring AI-powered tools, cryptocurrency analytics, and media content access. Built with Next.js 14 and integrated with the Solana blockchain.

## ✨ Key Features

### 🎮 Torrent Game Search & Download
- Search for games across multiple torrent sources
- Filter by various qualities and versions
- Direct download links for easy access

### 🎬 Torrent Movie Search & Download
- Search movies with detailed metadata
- Multiple quality options and sources
- Stream or download your favorite content

### 📊 Token Analytics
- Real-time Solana token price tracking
- Detailed token metrics and statistics
- Interactive price charts and historical data
- Market cap, volume, and price change indicators

### 🎨 AI Image Generator
- Generate unique images using AI
- Customizable prompts and styles
- High-resolution downloads
- Save and manage your creations

### 💬 AI Chatbot Assistant
- Intelligent conversation with AI
- Context-aware responses
- Multiple interaction modes
- Web3 and crypto knowledge base

### 📈 Trending Tokens
- Discover trending Solana tokens
- Real-time price updates
- Volume and market cap tracking
- Quick access to token analytics

## 🛠️ Tech Stack

- **Frontend**: Next.js 14, React, TypeScript
- **Styling**: Tailwind CSS, Shadcn UI
- **Blockchain**: Solana (Web3.js, @solana/wallet-adapter)
- **AI**: Custom AI integration for chat and image generation
- **State Management**: React Context, React Query
- **API**: Next.js API Routes
- **Deployment**: Vercel/Netlify ready

## 🚀 Getting Started

### Prerequisites

- Node.js 18.0.0 or higher
- npm 9.0.0 or higher
- Solana CLI (for development)
- A modern web browser with Solana wallet extension (Phantom, Solflare, etc.)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/luneshark.git
   cd luneshark
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env.local
   ```
   Update the `.env.local` file with your API keys and configurations.

4. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🔧 Configuration

### Environment Variables

Create a `.env.local` file in the root directory with the following variables:

```env
NEXT_PUBLIC_SOLANA_NETWORK=mainnet-beta # or devnet/testnet
NEXT_PUBLIC_RPC_URL=your_rpc_url_here
NEXT_PUBLIC_API_URL=your_api_url_here
# Add other required API keys
```

## 🌐 Deployment

### Vercel Deployment

1. Push your code to a GitHub/GitLab/Bitbucket repository
2. Import the project on Vercel
3. Add your environment variables
4. Deploy!

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=YOUR_REPO_URL)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

For support, email support@luneshark.com or join our [Discord](https://discord.gg/luneshark).

## 🔗 Links

- [Website](https://luneshark.com)
- [Documentation](https://docs.luneshark.com)
- [Twitter](https://twitter.com/luneshark)
- [Telegram](https://t.me/luneshark)

---

<p align="center">
  Made with ❤️ by the Luneshark Team
</p>

4. Run the development server:

   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Environment Variables

Create a `.env.local` file in the root directory with the following variables:

```env
NEXT_PUBLIC_SOLANA_NETWORK=mainnet-beta
NEXT_PUBLIC_RPC_URL=your_rpc_url_here
NEXT_PUBLIC_COINMARKETCAP_API_KEY=your_coinmarketcap_api_key
OPENAI_API_KEY=your_openai_api_key
```

## 🚀 Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fyourusername%2Fplio)

1. Click the "Deploy" button above
2. Connect your GitHub account
3. Add your environment variables in the Vercel dashboard
4. Click "Deploy"

## 🔑 Required API Keys

### OpenAI API Key

- Used for AI chat functionality
- Get your key from: [OpenAI API Keys](https://platform.openai.com/api-keys)
- Add to `.env.local` as `OPENAI_API_KEY`

### CoinMarketCap API Key (Free Tier)

- Used for cryptocurrency market data
- Get your key from: [CoinMarketCap API](https://coinmarketcap.com/api/)
- Add to `.env.local` as `NEXT_PUBLIC_COINMARKETCAP_API_KEY`

### RPC Endpoint (Optional but recommended)

- For better performance, use a dedicated RPC endpoint
- Options: [QuickNode](https://www.quicknode.com/), [Alchemy](https://www.alchemy.com/), or [Triton](https://triton.one/)
- Add to `.env.local` as `NEXT_PUBLIC_RPC_URL`

## 🏗️ Project Structure

```
plio/
├── app/                    # Next.js 13+ app directory
│   ├── api/                # API routes
│   ├── dashboard/          # Dashboard page and subpages
│   ├── globals.css         # Global styles
│   ├── layout.tsx          # Root layout
│   └── page.tsx            # Home page
├── components/             # Reusable components
│   ├── ui/                 # shadcn/ui components
│   ├── navigation.tsx      # Main navigation
│   ├── plio-bot.tsx        # AI chat interface
│   └── ...
├── lib/                   # Utility functions
├── public/                # Static assets
├── styles/                # Global styles
├── types/                 # TypeScript type definitions
└── ...config files
```

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run type-check` - Check TypeScript types
- `npm run format` - Format code with Prettier

## 🌟 Features Overview

### For Everyone

- AI-powered chat assistant
- Cryptocurrency market data
- Project information and roadmap
- Responsive design for all devices

<!-- ### For $Luneshark Holders (50k+)

- Advanced analytics dashboard
- AI image generation
- Premium support
- Early access to new features -->

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)
- UI Components by [shadcn/ui](https://ui.shadcn.com/)
- Icons by [Lucide](https://lucide.dev/)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Wallet Integration

- Connect Phantom wallet to view $LUNESHARK balance
- Automatic feature access based on token holdings
- Secure wallet connection with disconnect option

### PlioBot AI Assistant

- **Nice Mode**: Friendly, helpful responses with emojis
- **Crude Mode**: Direct, no-nonsense responses
- Real-time chat with conversation history
- Powered by OpenAI GPT-3.5-turbo

### Crypto Market Dashboard

- Live prices from CoinMarketCap API
- Large Cap cryptocurrencies (BTC, ETH, SOL, etc.)
- Popular meme coins (DOGE, SHIB, PEPE, etc.)
- Real-time price updates and 24h changes

## Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Add environment variables in Vercel dashboard
4. Deploy automatically

### Other Platforms

The app can be deployed to any platform that supports Next.js:

- Netlify
- Railway
- DigitalOcean App Platform
- AWS Amplify

## Environment Variables

| Variable                | Description                             | Required |
| ----------------------- | --------------------------------------- | -------- |
| `OPENAI_API_KEY`        | OpenAI API key for chat functionality   | Yes      |
| `COINMARKETCAP_API_KEY` | CoinMarketCap API key for crypto prices | Yes      |
| `NEXT_PUBLIC_APP_URL`   | Your app's URL                          | No       |

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is private and proprietary.

## Support

For support or questions, please contact the development team.

# IPFS Website Hosting Platform

🚀 Build & Deploy a Blockchain Website + File Hosting DApp | Code Hosting DApp using Next.js & Pinata IPFS

In this video, learn how to build and deploy a full-stack decentralized Website & File Hosting DApp powered by Next.js and Pinata IPFS. We’ll create a sleek, functional platform that lets users upload and host files or entire websites on the blockchain — forever and censorship-free.

🔥 What you’ll learn:

- How to integrate Pinata IPFS for decentralized file storage
- Creating a modern front-end with Next.js
- Building a Code Hosting DApp with upload, view, and deploy features
- Managing file metadata using IPFS CIDs
- Deploying the entire DApp to the web (e.g., Vercel or Netlify)
- Tips for a Web3-ready UI/UX

🎯 Perfect for Web3 developers, blockchain enthusiasts, and anyone looking to dive into decentralized hosting and IPFS file systems.

## Project Overview

![alt text](https://www.daulathussain.com/wp-content/uploads/2025/05/Build-Deploy-a-Blockchain-Website-File-Hosting-DApp-Code-Hosting-DApp-using-Next.js-Pinata-IPFS.jpg)

## Instruction

Kindly follow the following Instructions to run the project in your system and install the necessary requirements

- [Final Source Code](https://www.theblockchaincoders.com/sourceCode/build-and-deploy-a-blockchain-website-+-file-hosting-dapp-or-code-hosting-dapp-using-next.js-and-pinata-ipfs)

#### Setup Video

- [Final Code Setup video](https://youtu.be/xKVBtqLbHy0?si=77axe5u0_nXcfmNH)

#### Deploying Dapp

```
  WATCH: Hostinger
  Get : Discount 75%
  URL: https://www.hostg.xyz/aff_c?offer_id=6&aff_id=139422
```

### MULTI-CURRENCY ICO DAPP

```
  PROJECT: MULTI-CURRENCY ICO DAPP
  Code: https://www.theblockchaincoders.com/sourceCode/multi-currency-ico-dapp-using-next.js-solidity-and-wagmi
  VIDEO: https://youtu.be/j8NO8ea5zVo?si=jCmvfXmpmefwjhO5
```

#### Install Vs Code Editor

```
  GET: VsCode Editor
  URL: https://code.visualstudio.com/download
```

#### NodeJs & NPM Version

```
  NodeJs: v18.17.1 / LATEST
  NPM: 8.19.2
  URL: https://nodejs.org/en/download
  Video: https://youtu.be/PIR0oBVowXU?si=9eNdR29u37F2ujJJ
```

#### FINAL SOURCE CODE

```
  SETUP VIDEO: https://youtu.be/xKVBtqLbHy0?si=77axe5u0_nXcfmNH
  URL: https://www.theblockchaincoders.com/sourceCode/build-and-deploy-a-blockchain-website-+-file-hosting-dapp-or-code-hosting-dapp-using-next.js-and-pinata-ipfs
```

All you need to follow the complete project and follow the instructions which are explained in the tutorial by Daulat

## Final Code Instruction

If you download the final source code then you can follow the following instructions to run the Dapp successfully

#### PINATA IPFS

```
  OPEN: PINATA.CLOUD
  URL:https://pinata.cloud/
```

#### reown

```
  OPEN: WALLET CONNECT
  URL: https://docs.reown.com/cloud/relay
```

#### FORMSPREE

```
  OPEN: FORMSPREE
  URL: https://formspree.io/
```

#### ALCHEMY

```
  OPEN: ALCHEMY.COM
  URL: https://www.alchemy.com/
```

## Important Links

- [Get Pro Blockchain Developer Course](https://www.theblockchaincoders.com/pro-nft-marketplace)
- [Support Creator](https://bit.ly/Support-Creator)
- [All Projects Source Code](https://www.theblockchaincoders.com/SourceCode)

## Authors

- [@theblockchaincoders.com](https://www.theblockchaincoders.com/)
- [@consultancy](https://www.theblockchaincoders.com/consultancy)
- [@youtube](https://www.youtube.com/@daulathussain)

# IPFS Website Hosting Platform

A modern, decentralized website hosting platform built with Next.js, Tailwind CSS, and Pinata IPFS. Deploy your websites to the InterPlanetary File System (IPFS) with ease and get permanent, globally distributed hosting.

## 🌟 Features

- **Decentralized Hosting**: Deploy websites directly to IPFS for permanent, censorship-resistant hosting
- **Web3 Integration**: Connect with MetaMask and other Web3 wallets using RainbowKit
- **Instant Deployment**: Upload and deploy websites in seconds
- **Global Distribution**: Your content is distributed worldwide through IPFS nodes
- **Commission System**: Automated payment processing with 1 POL commission
- **Responsive Design**: Beautiful, dark-mode compatible UI that works on all devices
- **File Management**: Support for single files, multiple files, and entire folder uploads

## 🚀 Quick Start

### Prerequisites

- Node.js 16.8 or later
- npm or yarn
- A Pinata account and JWT token
- A WalletConnect project ID

### Installation

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd website-hosting-platform
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**

   Copy `.env.example` to `.env.local` and fill in your configuration:

   ```bash
   cp .env.example .env.local
   ```

   Required environment variables:

   ```env
   # WalletConnect Configuration
   NEXT_PUBLIC_WALLET_CONNECT_PROJECT_ID=your_wallet_connect_project_id

   # RPC Configuration
   NEXT_PUBLIC_RPC_URL=https://polygon-rpc.com

   # Pinata Configuration
   NEXT_PUBLIC_PINATA_JWT=your_pinata_jwt_token
   NEXT_PUBLIC_PINATA_GATEWAY_URL=https://gateway.pinata.cloud

   # Platform Configuration
   NEXT_PUBLIC_PLATFORM_NAME=IPFS Website Hosting
   NEXT_PUBLIC_PLATFORM_DESCRIPTION=Deploy your websites to IPFS with ease
   NEXT_PUBLIC_COMMISSION_AMOUNT=1
   NEXT_PUBLIC_COMMISSION_TOKEN=POL
   NEXT_PUBLIC_RECIPIENT_WALLET=0xb2c822A8f05Ed6d0aD8C62aaa952Cc8249733DB4
   ```

4. **Run the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser**

   Navigate to [http://localhost:3000](http://localhost:3000)

## 🛠️ Configuration

### Pinata Setup

1. Create an account at [Pinata](https://pinata.cloud)
2. Generate a new JWT token in your Pinata dashboard
3. Add the JWT token to your environment variables

### WalletConnect Setup

1. Create a project at [WalletConnect](https://cloud.walletconnect.com)
2. Get your project ID
3. Add the project ID to your environment variables

### Network Configuration

The platform is configured to work with Polygon by default. You can modify the network settings in `config/wagmi.js` by updating the environment variables:

- `NEXT_PUBLIC_CHAIN_ID`: Network chain ID (137 for Polygon)
- `NEXT_PUBLIC_CHAIN_NAME`: Display name for the network
- `NEXT_PUBLIC_CHAIN_SYMBOL`: Native token symbol
- `NEXT_PUBLIC_RPC_URL`: RPC endpoint URL
- `NEXT_PUBLIC_BLOCK_EXPLORER`: Block explorer URL

## 🏗️ Architecture

### Project Structure

```
├── components/
│   ├── icons/           # SVG icon components
│   ├── layout/          # Layout components (Header, Footer)
│   ├── pages/           # Page components
│   ├── providers/       # Context providers (Theme)
│   ├── result/          # Deployment result components
│   └── upload/          # File upload components
├── config/
│   └── wagmi.js         # Web3 configuration
├── pages/
│   ├── _app.js          # Next.js app component
│   └── index.js         # Homepage
├── services/
│   ├── pinata.js        # Pinata IPFS service
│   └── payment.js       # Payment processing service
├── styles/
│   └── globals.css      # Global styles and utilities
└── public/              # Static assets
```

### Key Components

- **MainPage**: Main application interface with upload and deployment logic
- **FileUpload**: Drag-and-drop file upload component with preview
- **UploadProgress**: Step-by-step deployment progress indicator
- **DeploymentResult**: Success page with deployment details and links
- **ThemeProvider**: Dark/light theme management

### Services

- **PinataService**: Handles all IPFS operations via Pinata API
- **PaymentService**: Manages commission payments on Polygon network

## 💰 Payment System

The platform charges a configurable commission (default: 1 POL) for each deployment. Payments are processed automatically when users deploy their websites.

### Commission Configuration

You can modify the commission settings via environment variables:

- `NEXT_PUBLIC_COMMISSION_AMOUNT`: Amount to charge (default: "1")
- `NEXT_PUBLIC_COMMISSION_TOKEN`: Token symbol (default: "POL")
- `NEXT_PUBLIC_RECIPIENT_WALLET`: Wallet address to receive payments

## 🎨 Customization

### Theming

The platform supports dark/light themes with smooth transitions. Theme preferences are automatically saved and restored.

### Styling

Built with Tailwind CSS for easy customization:

- Modify colors in `tailwind.config.js`
- Add custom styles in `styles/globals.css`
- Use environment variables for branding

### Environment-Based Configuration

Most platform settings can be configured via environment variables, making it easy to deploy different instances or update settings without code changes.

## 🚢 Deployment

### Vercel (Recommended)

1. Fork this repository
2. Connect your repository to Vercel
3. Add environment variables in Vercel dashboard
4. Deploy

### Other Platforms

The platform can be deployed to any hosting service that supports Next.js:

- Netlify
- AWS Amplify
- Railway
- Render

For static hosting, uncomment the static export configuration in `next.config.js`.

## 📱 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🔧 Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

### Adding New Features

1. Create new components in appropriate directories
2. Add necessary services in the `services/` directory
3. Update environment variables if needed
4. Test with both light and dark themes

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## 🆘 Support

For support and questions:

- Check the documentation
- Open an issue on GitHub
- Join our Discord community

## 🌟 Acknowledgments

- [IPFS](https://ipfs.io) - InterPlanetary File System
- [Pinata](https://pinata.cloud) - IPFS pinning service
- [RainbowKit](https://rainbowkit.com) - Web3 wallet connection
- [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS framework
- [Next.js](https://nextjs.org) - React framework

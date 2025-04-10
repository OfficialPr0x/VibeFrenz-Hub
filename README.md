# 🚀 Vibe Frenz AI

Welcome to **Vibe Frenz AI**, the cutting-edge platform where AI agents are created, evolved, and engaged in vibe-driven battles. This project combines AI development, community creativity, and Web3 mechanics, offering a unique digital experience for builders, battlers, strategists, and explorers.

## 🌐 Project Structure

The project is organized as follows:

```
vibe-frenz-ai
├── public
│   ├── favicon.svg          # Favicon for the application
│   └── robots.txt           # Controls how search engines index the site
├── src
│   ├── assets
│   │   ├── animations
│   │   │   └── lottie
│   │   │       └── mint-celebration.json  # Lottie animation data for mint celebration
│   │   └── images
│   │       └── logo.svg    # Logo image for the application
│   ├── components
│   │   ├── common
│   │   │   ├── Button.tsx   # Customizable button component
│   │   │   ├── Card.tsx     # Card component for displaying content
│   │   │   └── Layout.tsx   # Consistent layout structure component
│   │   ├── landing
│   │   │   ├── DevTimeline.tsx  # Timeline of development updates
│   │   │   ├── HeroLanding.tsx  # Animated landing section with CTA
│   │   │   ├── LivestreamSection.tsx  # Livestreams and upcoming schedules
│   │   │   └── StatsPanel.tsx  # Live statistics and progress bars
│   │   ├── mint
│   │   │   └── MintPassReveal.tsx  # Mint pass reveal with animations
│   │   └── scenes
│   │       └── AgentShowcaseScene.tsx  # 3D scene showcasing agents
│   ├── config
│   │   └── site.ts          # Configuration settings for the site
│   ├── constants
│   │   └── index.ts         # Constants used throughout the application
│   ├── hooks
│   │   ├── useAgent.ts      # Custom hook for managing agent-related state
│   │   ├── useMint.ts       # Custom hook for handling minting logic
│   │   └── useStream.ts     # Custom hook for managing livestream data
│   ├── lib
│   │   ├── api.ts           # Functions for making API calls
│   │   └── utils.ts         # Utility functions used throughout the application
│   ├── pages
│   │   ├── _app.tsx         # Custom App component for initializing pages
│   │   ├── _document.tsx     # Custom Document component for server-side rendering
│   │   ├── early-access.tsx  # Page component for early access section
│   │   ├── index.tsx        # Main landing page component
│   │   └── vibathons.tsx    # Page component for the Vibathons section
│   ├── store
│   │   ├── agentStore.ts    # Zustand store for managing agent state
│   │   └── uiStore.ts       # Zustand store for managing UI state
│   ├── styles
│   │   ├── animations.css    # CSS styles for animations
│   │   └── globals.css       # Global CSS styles for the application
│   ├── types
│   │   └── index.ts         # TypeScript types used throughout the application
│   └── utils
│       ├── animations.ts     # Utility functions for handling animations
│       └── helpers.ts        # Helper functions used throughout the application
├── .eslintrc.js             # ESLint configuration file
├── .gitignore                # Files and directories to be ignored by Git
├── next-env.d.ts            # TypeScript definitions for Next.js
├── next.config.js           # Configuration settings for Next.js application
├── package.json              # npm configuration file
├── postcss.config.js        # Configuration settings for PostCSS
├── README.md                 # Documentation for the project
├── tailwind.config.js        # Configuration settings for Tailwind CSS
└── tsconfig.json             # TypeScript configuration file
```

## ⚡️ Getting Started

To get started with the project, clone the repository and install the dependencies:

```bash
git clone <repository-url>
cd vibe-frenz-ai
npm install
```

## 🚀 Running the Application

To run the application in development mode, use:

```bash
npm run dev
```

Visit `http://localhost:3000` in your browser to see the application in action.

## 📚 Contributing

We welcome contributions! Please read our contributing guidelines before submitting a pull request.

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

For more information, visit our website at [vibefrenz.live](https://vibefrenz.live). Join the movement and be part of the future of AI-built worlds!

# bt1zar_superalgos

> **Note**: This repository uses `bt1zar_superalgos_main` as the default branch instead of `master` or `main`.

This is a streamlined version of Superalgos focused on the **Top 3 Unique Features** as identified in the SUPERALGOS_TOP_3_FEATURES_ANALYSIS.md:

## Core Features Preserved

### 1. **Visual Workspace-Based Strategy Design System**
- **Location**: `Projects/Workspaces/` and `Projects/Visual-Scripting/`
- **What it does**: Revolutionary visual programming approach for designing trading strategies through interactive workspaces
- **Key Features**: Node-based visual programming, drag-and-drop interface, schema-driven UI generation

### 2. **Decentralized P2P Social Trading Network**
- **Location**: `Projects/Social-Trading/` and `Projects/Network/`
- **What it does**: Peer-to-peer network where users can discover, clone, and synchronize trading strategies directly from other network participants
- **Key Features**: Real-time strategy sharing, automatic GitHub synchronization, decentralized strategy discovery

### 3. **Multi-Project Modular Architecture with Dynamic Schema Loading**
- **Location**: `MultiProject.js` and `Projects/ProjectsSchema.json`
- **What it does**: Sophisticated modular architecture where entire projects can be dynamically loaded, extended, and configured
- **Key Features**: Runtime project discovery, schema-driven module instantiation, hot-pluggable modules

## What Was Removed

All proprietary content and non-essential features were removed while retaining open-source knowledge:

- **Removed Projects**: Algorithmic-Trading, Bitcoin-Factory, Community-Plugins, Contributions, Data-Mining, Decentralized-Exchanges, Education, Ethereum, Governance, Local-Storage, Machine-Learning, Open-Storage, Portfolio-Management, Simulation, Social-Bots, TensorFlow, Trading-Signals, User-Apps
- **Removed Directories**: Build artifacts, installers, documentation exports, Docker files, translations, reports
- **Removed Files**: Installation scripts, utility scripts, platform-specific configs, bitcoin-factory HTTP routes and servers
- **Dead Links Removed**: All references to non-existent Bitcoin-Factory components, broken plugin references, and outdated documentation links

## Recent Cleanup (v1.6.1)

The following dead links and unused references were removed:
- Bitcoin-Factory HTTP routes and server implementations
- BitcoinFactoryView Vue component
- PATH_TO_BITCOIN_FACTORY environment variable
- Machine Learning Network Service (was part of removed Bitcoin-Factory)
- Streamlined plugin configuration to only include active projects

## Quick Start

```bash
# Install dependencies
npm install

# Start the platform (headless mode)
npm start

# Start with network features
npm run startNetwork

# Start social trading features  
npm run startSocialTrading
```

## License

Apache License 2.0 - Open Source

## Architecture

The system maintains its core modular architecture with only essential projects:

- **Foundations**: Core infrastructure and schemas
- **Visual-Scripting**: Visual programming interface
- **Workspaces**: Workspace management and templates
- **Social-Trading**: P2P social trading features
- **Network**: P2P networking infrastructure

This creates a unique ecosystem where both technical and non-technical users can participate in algorithmic trading while fostering community-driven innovation through decentralized collaboration.
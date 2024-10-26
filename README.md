# ZEX-Assets 🎨

Repository containing officially supported assets on ZEX, including token logos and metadata(soon). This repository serves as the primary source for token icons displayed across ZEX's platforms.

## Overview

This repository was initially forked from Trust Wallet's database and Uniswap's token list, and has been customized to meet ZEX's specific requirements. It maintains a standardized structure for organizing blockchain assets and their associated metadata.

## Directory Structure

```
blockchains/
├── bsc/
│   └── assets/
│       └── [tokenId]/
│           └── logo.png
├── eth/
│   └── assets/
└── [other-chains]/
```

## Adding Your Token Icon ✨

To get your token whitelisted for icon display and searchability on ZEX:

1. **Fork the Repository**

   - Click the 'Fork' button in the top right corner
   - Clone your forked repository locally

2. **Prepare Your Asset**

   - Prepare a PNG logo for your token
   - Requirements:
     - Format: PNG
     - Size: 100x100px recommended
     - Background: Transparent
     - File name: `logo.png`

3. **Add Your Asset**

   - Navigate to `blockchains/[chain-name]/assets/`
   - Create a new folder named after your token ID (e.g., `10`)
   - Place your `logo.png` file inside this folder

4. **Submit for Review**
   - Create a Pull Request (PR) to the main repository
   - Include the following information in your PR:
     - Token Id
     - Chain name

## Review Process

- PRs are reviewed by the ZEX team on a regular basis
- Review typically takes 2-3 business days
- Team may request additional information or changes
- Decisions are final and at the discretion of the ZEX team

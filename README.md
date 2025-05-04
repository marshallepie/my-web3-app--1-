# maiwill-wallet
A web3 wallet for the maiwill project

## Web3 Dev Container Starter

This is a fully isolated Web3 development environment designed for use with **GitHub Codespaces** or **VS Code Dev Containers**.

## 📦 What's Included

- **Node.js 18** (via Docker)
- **Hardhat** (for Ethereum smart contract dev)
- **Ethers.js** (Web3 interaction)
- **dotenv** (for managing secrets)
- Pre-configured `.devcontainer` setup for Codespaces/VS Code

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/my-web3-app.git
cd my-web3-app
```

### 2. Open in Codespaces or VS Code

- **GitHub Codespaces:** Just click "Code" → "Open with Codespaces".
- **VS Code:** Use the "Dev Containers" extension and select "Reopen in Container".

### 3. Add Environment Variables

Create a `.env` file with:
```
ALCHEMY_API_KEY=your-alchemy-api-key
PRIVATE_KEY=your-private-key
```

### 4. Install Packages

This runs automatically in container startup:
```bash
npm install
```

### 5. Start Building

Use Hardhat to compile, test, and deploy smart contracts.

```bash
npx hardhat compile
```

---

## 🧱 File Structure

```
my-web3-app/
├── .devcontainer/
│   ├── devcontainer.json
│   └── Dockerfile
├── .env
├── package.json
└── README.md
```

---

## 📘 Notes

- This environment is containerized — nothing is installed on your host.
- Ideal for building and testing dApps in a clean, portable space.


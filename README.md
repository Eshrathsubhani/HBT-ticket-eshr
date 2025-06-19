# `HBT Ticketing dApp`

🔗 Live Website: https://5g5ru-saaaa-aaaai-q3yga-cai.icp0.io/

📌 Overview

Welcome to the **HBT Ticketing System**, a decentralized application (dApp) deployed on the Internet Computer (IC) blockchain. This project allows event organizers and attendees to create, manage, and validate event tickets securely and transparently — powered by smart contracts.

🔗 This Project Integrates:

🎯 Internet Computer (ICP)
Backend canisters are written in Rust, deployed via dfx, and interact with the IC blockchain network.

⚙️ DFINITY SDK (dfx)
Used to build, deploy, and manage Rust-based canisters and frontend assets.

🦀 Rust + Motoko Interoperability (Candid)
Rust canisters define candid interfaces (.did) for seamless communication with frontend JavaScript/TypeScript.

⚛️ React + Vite
Fast and modern web frontend built using React with Vite for blazing-fast bundling and hot-reloading.

🧪 Vitest + React Testing Library
For unit testing key UI components and validating app logic during development.

🌐 Live Demo

Visit the deployed application: 👉 https://5g5ru-saaaa-aaaai-q3yga-cai.icp0.io/



## 🛠 Tech Stack

| Category                         | Technology / Tool                                                                             |
|----------------------------------|-----------------------------------------------------------------------------------------------|
| **Frontend**                     | [React](https://reactjs.org/) + [Vite](https://vitejs.dev/)                                   |
| **Testing**                      | [Vitest](https://vitest.dev/)                                                                 |
| **Backend**                      | [Rust](https://www.rust-lang.org/) with [ic-cdk](https://docs.rs/ic-cdk)                      |
| **IDL Interface**                | [Candid](https://internetcomputer.org/docs/current/developer-docs/backend/candid/)            |
| **Blockchain**                   | [Internet Computer (DFINITY)](https://internetcomputer.org/)                                  |
| **Package Managers**             | [npm](https://www.npmjs.com/) (frontend), [cargo](https://doc.rust-lang.org/cargo/) (backend) |
| **CLI & Deployment**             | [DFX CLI](https://internetcomputer.org/docs/current/developer-docs/setup/dfx-cli/)            |

📁 Folder Structure

HBT-ticket-eshr/
├── backend/                  # Rust canister logic (Internet Computer backend)
├── frontend/                 # React + Vite frontend app
├── src/                      # Holds original source layout (optional legacy)
├── dfx.json                  # DFX configuration for canisters
├── canister_ids.json         # Deployed canister IDs
├── Cargo.toml                # Rust workspace configuration
├── package.json              # Project metadata and frontend scripts
├── README.md                 # Project documentation


## 🚀 Getting Started

### 🔧 Prerequisites

- [Node.js & NPM](https://nodejs.org/)
- [DFX CLI](https://internetcomputer.org/docs/current/developer-docs/setup/install)
- Internet Computer SDK
- Rust (for backend canisters)

### 🛠️ Local Development

```bash
# Start the local Internet Computer replica
dfx start --background

# Install frontend dependencies
cd frontend
npm install

# Build the frontend
npm run build

# Go back to root and deploy canisters
cd ..
dfx deploy

## 🙋‍♂️ Author

Created and maintained by Eshrath Subhani

GitHub: https://github.com/Eshrathsubhani

## 📄 License

This project is licensed under the MIT License . 




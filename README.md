# React Crypto Dashboard

A cryptocurrency-themed dashboard interface built with React. This project focuses on component-based UI development, page routing, and organizing a multi-page dashboard experience.

**Live Demo:** https://react-crypto-dashboard-two.vercel.app/  
**Repository:** https://github.com/nirbhaycse/react_crypto_dashboard

## Overview

The application is organized into separate pages for the dashboard, transactions, and support. Shared layout and navigation components help keep the interface consistent across the application.

This is a frontend portfolio project using sample/static values in several dashboard cards and transaction rows. It is not connected to a live exchange or wallet service, and the displayed balances and transactions should be treated as demonstration data. Some visible controls (such as CSV export or Buy/Sell) are UI elements and may not perform real financial operations.

## Pages

- **Dashboard** — the main dashboard view.
- **Transactions** — a dedicated transactions page.
- **Support** — a support page.
- **Shared navigation/layout** — reusable components for the application structure.

## Tech Stack

- React 18
- JavaScript (ES modules)
- Vite
- React Router
- Chakra UI
- Emotion
- React Icons
- Framer Motion

## Run Locally

### Prerequisites

- Node.js
- npm

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/nirbhaycse/react_crypto_dashboard.git
cd react_crypto_dashboard
npm install
```

Start the development server:

```bash
npm run dev
```

Vite will print a local URL in the terminal.

### Production Build

Create an optimized production build:

```bash
npm run build
```

Preview the build locally:

```bash
npm run preview
```

Run the configured lint command:

```bash
npm run lint
```

## Project Structure

```text
src/
├── components/       # Shared layout and navigation components
├── pages/
│   ├── Dashboard/   # Dashboard page
│   ├── Transaction/ # Transactions page
│   └── Support/     # Support page
├── App.jsx           # Application routes
└── main.jsx          # Application entry point
```

Folder names and contents may evolve as the project develops.

## What I Practised

- Building reusable React components.
- Organizing a multi-page application with React Router.
- Using a component library to build UI layouts.
- Setting up a Vite development workflow.
- Preparing and deploying a frontend project.

## Possible Next Steps

- Connect the interface to a documented cryptocurrency market-data API.
- Implement and test search, filtering, CSV export, and action buttons rather than presenting them as functional if they are still placeholders.
- Add clear loading, empty, and error states for data-driven views.
- Improve responsive behaviour and accessibility.
- Add tests for key components and routes.
- Document data sources and any API configuration.

## Author

**Nirbhay Chandra Maurya**  
GitHub: https://github.com/nirbhaycse

---

This repository is a learning and portfolio project. Cryptocurrency information, if displayed, should not be treated as financial advice.

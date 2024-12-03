# 💳 Horizon -- Banking Platform

A financial SaaS platform built with Next.js that connects multiple bank accounts, displays transactions in real-time, facilitates secure fund transfers, and helps users manage their finances effectively.

---

## 🌟 Features

- **Secure Authentication**
  - Ultra-secure SSR authentication with comprehensive validations and authorization mechanisms.

- **Bank Integration**
  - Seamlessly integrates with Plaid for linking multiple bank accounts.

- **Dashboard Overview**
  - Displays a consolidated view of total balance, recent transactions, and categorized spending from all connected banks.

- **Bank Management**
  - Lists all connected banks with detailed account information and individual balances.

- **Transaction History**
  - Includes pagination and filtering options for a comprehensive transaction view.

- **Real-Time Updates**
  - Automatically reflects changes across the application when a new bank account is connected.

- **Fund Transfers**
  - Enables secure fund transfers between users using Dwolla, requiring essential recipient details and bank IDs.

- **Responsiveness**
  - Fully optimized for various screen sizes, offering a consistent user experience on desktops, tablets, and mobile devices.

---

## ⚙️ Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/), [TailwindCSS](https://tailwindcss.com/), [ShadCN](https://shadcn.dev/)
- **Backend**: [Appwrite](https://appwrite.io/), [Plaid](https://plaid.com/), [Dwolla](https://www.dwolla.com/)
- **Form Handling**: [React Hook Form](https://react-hook-form.com/), [Zod](https://zod.dev/)
- **Charts & Visualizations**: [Chart.js](https://www.chartjs.org/)
- **Programming Language**: TypeScript

---

## 🚀 Quick Start

Follow these steps to set up the project locally:

### Prerequisites

Ensure the following tools are installed:
- Node.js v16+ and npm/yarn
- Appwrite instance for backend setup
- Plaid account for bank integrations
- Dwolla account for fund transfers

### Clone the Repository
```bash
git clone https://github.com/asadsaves/banking-platform.git
cd banking-platform

# Multi-Store Stock Manager

A mobile-first inventory management platform for multi-unit retail operations. Built with Next.js, TypeScript, MongoDB, and CSS Modules.

## 🔥 Features

- 🔐 Role-based authentication (Admin and Employee)
- 📦 Store-specific stock management
- 📊 Consolidated inventory dashboard for admins
- 🛒 Smart purchase suggestions based on consumption
- 🚨 Alerts for low stock thresholds
- 📱 Mobile-friendly UI optimized for in-store use

## 🧰 Tech Stack

- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- [CSS Modules](https://nextjs.org/docs/basic-features/built-in-css-support)
- [Figma (UI/UX)](https://figma.com)

## 📁 Folder Structure

/pages
/components
/styles
/api
/models
/services
/lib
/hooks
/public

shell
Copiar
Editar

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Run development server
npm run dev
🔐 Environment Variables
Create a .env.local file in the root:

env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
❗ Never commit .env.local – it is ignored by Git for security.

You can use the .env.example provided in this repo to know which environment variables are required.

📦 Deployment
This project is ready for deployment with Vercel. Connect your GitHub repo and add environment variables directly in the dashboard.

👤 Author
Renan Janz Hargreaves Vieira
LinkedIn • Portfolio

📜 License
MIT

yaml
Copiar
Editar

---

## ✅ 2. `.env.example`

📌 Crie um arquivo chamado `.env.example` na raiz do seu projeto com:

```env
# Example environment configuration

MONGODB_URI=your_mongodb_connection_string_here
JWT_SECRET=your_jwt_secret_here
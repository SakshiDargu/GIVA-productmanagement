# GIVA-productmanagement 🍲

## Overview
Welcome to the **Recipe App**! This application allows users to explore, add, and manage their favorite recipes. Built with **React** for the frontend and **Node.js** with **Prisma** for the backend, it’s designed for cooking enthusiasts!

## 🚀 Getting Started

### Prerequisites
Before you start, ensure you have the following installed:
- **Node.js** and **npm** on your machine.
- An account on **ElephantSQL** for database hosting.
- A **Spoonacular API** key to access recipe data.

### Setup Instructions

#### 1. Clone the Repository
To get started, clone the repository to your local machine:
```bash
git clone https://github.com/SakshiDargu/giva-productmanagement.git
cd giva-productmanagement

GIVA-productmanagement 🍲
Overview
Welcome to the Recipe App! This application allows users to explore, add, and manage their favorite recipes. Built with React for the frontend and Node.js with Prisma for the backend, it's designed for cooking enthusiasts!
🚀 Getting Started
Prerequisites
Before you start, ensure you have the following installed:

Node.js and npm on your machine
An account on ElephantSQL for database hosting
A Spoonacular API key to access recipe data

Setup Instructions
1. Clone the Repository
bashCopygit clone https://github.com/SakshiDargu/giva-productmanagement.git
cd giva-productmanagement
2. Backend Setup 🔧
Navigate to the backend directory:
bashCopycd backend
Install dependencies:
bashCopynpm install
Environment Setup:

Create a .env file
Add your Spoonacular API key
Configure ElephantSQL connection:
envCopyAPI_KEY=your_spoonacular_api_key
DATABASE_URL=your_elephantsql_url


Database Configuration:
bashCopynpx prisma init
npx prisma generate
Start the backend server:
bashCopynpm start
3. Frontend Setup 💻
Navigate to the frontend directory:
bashCopycd frontend
Install dependencies:
bashCopynpm install
Start the development server:
bashCopynpm run dev

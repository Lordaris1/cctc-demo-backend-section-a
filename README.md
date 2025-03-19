# 🚀 Express.js App

A lightweight Express.js application designed for simplicity and ease of use. Follow the steps below to install, configure, and run the app locally.

---

## ✅ Prerequisites

Before starting, ensure the following are installed on your system:

- [Node.js](https://nodejs.org) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)

Verify your installations by running:

node -v
npm -v

🛠️ Setup Instructions

1. Clone the Repository
git clone <repository-url>

2. Navigate to the Project Directory
cd <project-folder>

3. Install Dependencies
npm install
# OR
yarn install

4. 🔑 Environment Variables
PORT=5000


5. 📦 Migrate the Data
npx sequelize-cli db:migrate

6. Run the Server
node server.js

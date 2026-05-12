# Flavour-Nest
A full-stack food recipe web app with mood-based discovery, built with React, Node.js, Express, Cloudinary and MongoDB.
# 🍽️ FlavorNest

FlavorNest is a full-stack food recipe web app that lets users discover, 
share, and explore recipes based on their mood, weather, and time of day.

## ✨ Features
- 🔐 User authentication (Login & Sign Up)
- 📖 Browse and search recipes
- ➕ Share your own recipes with photos
- 🎯 Mood-based recipe discovery
- 🌤️ Filter by weather and meal time
- ❤️ Save favourite recipes
- 📱 Fully responsive design

## 🛠️ Tech Stack
- **Frontend:** React, Vite, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT (JSON Web Tokens)

## 🚀 Getting Started

### Prerequisites
- Node.js v20+
- MongoDB

### Installation
1. Clone the repo
2. Set up backend: `cd flavournest-backend && npm install`
3. Set up frontend: `cd flavournest-frontend && npm install`
4. Create `.env` file in backend with:
   - PORT=3000
   - CONNECTION_STRING=mongodb://127.0.0.1:27017/flavourNestDB
   - JWT_SECRET=mysecretkey
   - CLIENT_URL=http://localhost:5173
5. Run backend: `npm run dev`
6. Run frontend: `npm run dev`
7. Open http://localhost:5173

## 📄 License
MIT

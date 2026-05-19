# VoyageVerse — Travel Storytelling Platform

**VoyageVerse** is a full-stack travel storytelling platform where explorers share their journeys, discover stories from around the world, and connect through authentic travel experiences.

## ✨ Features
- 🔐 Authentication using Clerk
- 📖 Share travel stories with title, description, pros, cons & images
- 🗺️ Country + State filtering
- 🔍 Search stories by location
- 🖼️ Image uploads via Cloudinary
- 📄 Dynamic story detail pages
- 💬 Toast notifications
- 📱 Responsive UI with TailwindCSS

## 🛠️ Tech Stack
**Frontend:** React 19 (Vite), Tailwind CSS, React Router v7, Clerk, Axios, Framer Motion  
**Backend:** Express.js 5, MongoDB + Mongoose, Cloudinary, Multer

## 🚀 Getting Started

### Frontend Setup (`voyageverse-fr/`)
```bash
cd voyageverse-fr
npm install
```
Create `.env`:
```
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_API_URL=http://localhost:5000/api
```
```bash
npm run dev
```

### Backend Setup (`voyageverse-back/`)
```bash
cd voyageverse-back
npm install
```
Create `.env`:
```
MONGO_URI=your_mongodb_connection_string
PORT=5000
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```
```bash
npm run dev
```

## 📁 Folder Structure
VoyageVerse/
├── voyageverse-fr/     # React frontend
├── voyageverse-back/   # Express backend
└── README.md

## 👩‍💻 Author
**B G P SPOORTHI**  
GitHub: [@bgpspoorthi567](https://github.com/bgpspoorthi567)  
Email: spoorthigoud08@gmail.com
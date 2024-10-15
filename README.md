
# 🎥 Netflix Clone (MERN Stack)

This is a Netflix clone built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). It provides a movie-browsing and streaming experience, complete with user authentication and personalized dashboards.

---

## 🛠️ Key Features

- **User Authentication**: Login and Signup with JWT-based authentication.
- **Browse Movies & TV Shows**: Display content with descriptions and genres.
- **Search Functionality**: Find movies using keywords.
- **Responsive Design**: Works across all devices (mobile and desktop).
- **Protected Routes**: Only authenticated users can access specific pages.
- **Admin Dashboard (Optional)**: Manage movies, users, or content.
- **Video Streaming**: Embed video player for streaming movies or shows.

---

## 🚀 Live Demo
- **Frontend**: [Live Frontend Link](#)
- **Backend**: [Live Backend Link](#)

---

## 📦 Dependencies

### Frontend Dependencies
- **React.js**: Frontend library.
- **React Router DOM**: For routing between pages.
- **Axios**: For HTTP requests.
- **Tailwind CSS**: Styling framework.
- **dotenv**: Load environment variables into React.

### Backend Dependencies
- **Express.js**: Node.js framework for backend.
- **Mongoose**: ODM library to connect with MongoDB.
- **bcryptjs**: For hashing passwords.
- **jsonwebtoken (JWT)**: For user authentication.
- **Cors**: Enable cross-origin requests.
- **dotenv**: Manage environment variables.
- **Nodemon**: Development utility for auto-reloading.

---

## 📖 Installation Instructions

### Step 1: Clone the Repository
```bash
https://github.com/MaulikPatel63/Netflix-Clone.git
cd netflix-clone
```

### Step 2: Install Dependencies

#### Backend Setup
Navigate to the backend directory and install the dependencies:
```bash
npm install
```

#### Frontend Setup
Navigate to the frontend directory and install the dependencies:
```bash
cd ../frontend
npm install
```

### Step 3: Setup `.env` File

#### `.env`
```bash
PORT=5000
MONGO_URI=your_mongo_uri
NODE_ENV=development
JWT_SECRET=your_jwt_secre
TMDB_API_KEY=your_tmdb_api_key
```
---

## 🎬 Usage

### Start Backend Server
```bash
npm run dev
```

### Start Frontend Server
```bash
cd frontend
npm run start
```
---

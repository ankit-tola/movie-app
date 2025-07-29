# 🎬 Movie App

A modern React-based movie browsing app that lets users search and discover trending movies using the TMDB API. Styled with Tailwind CSS and built with Vite for fast development.

---

## 🚀 Features

- 🔍 Search for movies with live debounce
- 📈 View trending movies
- 🧠 Search term tracking with Appwrite
- 💅 Clean, responsive UI with Tailwind CSS
- ⚡ Powered by Vite for lightning-fast builds

---

## 🛠️ Tech Stack

- **React** (with hooks)
- **Tailwind CSS** for styling
- **Vite** as build tool
- **Appwrite** for backend services
- **TMDB API** for movie data
- **react-use** for debounced search

---

## 📸 Screenshots

> Add screenshots of the app here (e.g., home page, search results, movie cards)

---

## 🔧 Setup Instructions

### 1. Clone the repository

git clone https://github.com/ankit-tola/movie-app.git
cd movie-app
### 2. Install dependencies
bash
Copy
Edit
npm install
### 3. Set up environment variables
Create a .env file and add:

env
Copy
Edit
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
VITE_APPWRITE_DATABASE_ID=your_db_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
VITE_TMDB_API_KEY=your_tmdb_api_key
Replace placeholders with your actual keys.

### 4. Run the app
bash
Copy
Edit
npm run dev
Visit http://localhost:5173 to explore the app.

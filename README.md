# 🍿 usePopcorn

**usePopcorn** is a React-based movie browser and watchlist app. 🎬
Search for movies via the OMDb API, read details, and track the ones you’ve watched — complete with your own ⭐ personal rating.

---

## 🔍 Features

- 🔎 **Live search** with debounced queries to the OMDb API
- 📝 View detailed movie info (poster, plot, genre, director, etc.)
- 🎯 Add movies to a **custom watchlist** and rate them
- 📊 Automatically calculates:

  - Average IMDb rating
  - Your average rating
  - Total runtime of watched movies

- 🧩 Clean component structure with toggleable UI sections
- ⚡ Responsive UX with real-time state updates

---

## 💡 What I Learned

This project helped solidify my understanding of **React hooks** and **state management**, including:

- 🧠 `useState`, `useEffect`, `useRef`
- 🧪 Custom hooks (`useMovies`, `useKey`, `useLocalStorageState`)
- 🏗 Thinking in component trees & lifting state smartly
- ⏳ Handling async requests with loading and error states
- 🎹 DOM interaction via refs and keyboard listeners
- 🎨 Clean UI rendering with proper conditional logic

---

## 🧠 Tech Stack

- ⚛️ React (Vite)
- 🎥 OMDb API
- 💾 LocalStorage
- 🛠️ Custom Hooks
- 🎨 Vanilla CSS

---

## 🚀 Getting Started

Wanna run it locally? Here's how:

```bash
git clone https://github.com/YOUR_USERNAME/usePopcorn.git
cd usePopcorn
npm install
npm run dev
```

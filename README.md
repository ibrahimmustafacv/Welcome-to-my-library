# 🎬 My Cinema | Personal Movie & Series Collection

<div align="center">

**A sleek, interactive personal media library for tracking movies and TV series**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

---

## 📖 Overview

**My Cinema** is a personal, single-page web app for organizing and browsing a private collection of movies and TV series — Netflix-style. It features a searchable, filterable library with detailed pop-up info for every title, a "Watching Now" tracker, and an age-gated adult content section.

---

## ✨ Features

- 🎨 **Modern dark UI** with a cinematic hero section and smooth card animations
- 🔎 **Live search** across the entire collection by title
- 🧭 **Category filters** — All Content, Watching Now, Movies, TV Series, Adults 18+, and genre filters (Action, Drama, Crime, Sci-Fi, Romance)
- 👀 **"Watching Now" section** to track titles currently in progress
- 🪟 **Detailed modal view** for each title showing poster, year, duration, rating, genres, director, and status
- 🔞 **Age-gated Adults 18+ section** with an entry warning banner and explicit confirmation before content is revealed
- 📊 **Live statistics footer** showing total titles, movie/series counts, and more
- 🔗 **Social links** in the footer (GitHub, portfolio, Instagram)
- 📱 **Fully responsive design** — works smoothly on mobile, tablet, and desktop

---

## 🗂️ Content Sections

| Section | Description |
|---|---|
| 🏠 Home (Hero) | Welcome banner introducing the personal collection |
| 👀 Watching Now | Titles currently being watched |
| 🎥 Movies | Full movie catalog |
| 📺 TV Series | Full series catalog |
| 🔞 Adults 18+ | Age-restricted content, hidden behind a confirmation gate |
| 📚 All Content | Combined view of the entire library |

---

## 🛠️ Tech Stack

- **HTML5** for page structure
- **CSS3** (Custom Properties, Flexbox, Grid, Animations, Media Queries) for styling and responsiveness
- **JavaScript (Vanilla)** for search, filtering, modals, and the age-gate logic
- **Font Awesome** for icons
- **Data-driven content** — all titles are stored in a JavaScript data object, making it easy to add or edit entries

---

## 📂 Project Structure

```
📁 My Cinema
│
└── index.html    # Single file containing all HTML, CSS, and JS
```

> 💡 Poster images are loaded from external URLs and can be swapped for local assets if needed.

---

## 🚀 Getting Started

1. Download or clone the project
2. Open `index.html` directly in any web browser

```bash
open index.html      # macOS
start index.html     # Windows
```

No server or build step required — it's a fully static site.

---

## 🎯 How to Use

1. Use the **search bar** to quickly find a movie or series by title
2. Use the **filter bar** to browse by category (Movies, TV Series, Watching Now) or genre
3. Click any poster to open a **detailed modal** with full information
4. To access the **Adults 18+** section, confirm the age warning first
5. Check the footer for **live library statistics** (total titles, movies, series, etc.)

---

## ✏️ Adding New Titles

To add a new movie or series, add an entry to the relevant array in the data object using this structure:

```javascript
{
    id: 84,
    title: "Movie or Series Title",
    type: "movie", // or "series"
    genres: ["Action", "Drama"],
    // additional fields: year, duration, rating, image, description, director, status
}
```

---

## 📌 Notes

- This is a personal collection built for entertainment/organizational purposes only
- All movie/series posters remain the property of their respective owners
- Adult content is restricted and gated behind an 18+ confirmation

---

<div align="center">

**Built with ❤️ for movie & series lovers**

© 2024 My Personal Cinema — All rights reserved

</div>

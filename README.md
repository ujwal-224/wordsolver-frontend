# wordsolver-frontend
# Word Puzzle Solver

A simple and interactive web application that allows users to create a grid of letters and find meaningful words using a custom dictionary.

---

##  Live Demo

 https://ujwal-224.github.io/wordsolver-frontend/

---

##  Project Overview

This project is a **Word Puzzle Solver** where users can:

* Create a custom grid (3x3 to 20x20)
* Enter alphabets freely
* Add their own dictionary words
* Automatically find valid words from the grid

The frontend communicates with a backend API to process and return results efficiently.

---

##  Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Java (Spring Boot)
* **API Communication:** REST API
* **Deployment:**

  * Frontend → GitHub Pages
  * Backend → Render

---

##  How It Works

1. User creates a grid and inputs letters
2. User adds words to the dictionary
3. Clicking **Find Words** sends data to backend
4. Backend scans grid in all 8 directions
5. Matching words are returned and displayed

---

##  Input Format

```json
{
  "grid": [["C","A","T"],["D","O","G"]],
  "dictionary": ["CAT","DOG"]
}
```

---

##  Output Format

```json
{
  "words": ["CAT","DOG"],
  "count": 2
}
```

---

##  Features

* Dynamic grid creation
* Custom dictionary input
* Real-time word detection
* Clean and responsive UI
* Supports multiple directions (horizontal, vertical, diagonal)

---

##  Backend API

 https://wordsolver.onrender.com/solve

---

##  How to Run Locally

1. Clone the repository

```bash
git clone https://github.com/ujwal-224/wordsolver-frontend.git
```

2. Open `index.html` in your browser

---

##  Future Improvements

* Highlight words inside the grid
* Add animations for better UI
* Support larger datasets
* Improve performance for bigger grids

---

##  Author

**Mallarapu Ujwal**





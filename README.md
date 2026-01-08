# 2025 Kjt Patch 🎮

An interactive connections puzzle game inspired by [thomaswc.com's 2025 puzzle](https://thomaswc.com/2025.html), created to commemorate the year 2025 = 45×45.

## 📋 Description

2025 Kjt Patch is a large-scale puzzle game where you must organize 2025 items into 45 categories of 45 elements each. The challenge is to find connections between items and group them by combining two matching cells at a time, similar to NYT Connections but on a much grander scale.

## ✨ Features

- **45 diverse categories** spanning multiple domains: Chemical elements, African countries, dog breeds, musical instruments, Tom Hanks movies, programming languages, and more
- **Real-time scoring system** tracking your progress toward the maximum 1980 points
- **Error counter** to monitor incorrect combinations
- **Dark/Light mode toggle** with dark mode as default
- **Auto-save functionality** using browser LocalStorage
- **Visual animations** including shake effects on errors and fireworks upon completion
- **Responsive design** adapting to various screen sizes
- **Collective solving encouraged** - share your progress with friends

## 🎯 How to Play

1. Click on a cell to select it
2. Click on a second cell from the same category
3. If both cells belong to the same category, they merge
4. Continue until you complete all categories (maximum score: 1980)
5. Use the "Deselect" button to cancel your selection
6. Use the "New Game" button to restart

**Rules**: You can use Google or any external sources for help . The puzzle is designed to be solved over time, somewhat akin to a 2000-piece jigsaw puzzle.

## 🛠️ Technologies Used

- **HTML5**: Document structure
- **CSS3**: Styling and animations (CSS variables, transitions, keyframes)
- **Vanilla JavaScript**: Game logic
  - State management
  - LocalStorage for persistence
  - Canvas API for fireworks animations

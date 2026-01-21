# Klondike Solitaire 🃏

## 🚀 Overview

A fully interactive, browser-based implementation of the classic Klondike Solitaire card game. Built with vanilla JavaScript and modern CSS, this project delivers a smooth, drag-and-drop gameplay experience with undo functionality and win detection.  Perfect for learning game logic, DOM manipulation, and object-oriented JavaScript.

**🎮 [Play Live Demo](https://ahmedikram05.github.io/klondike-solitaire/)**

## 🧠 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6 Modules)
- **Architecture**: Object-Oriented Programming (OOP)
- **Features**: Drag-and-drop API, Event-driven programming
- **Deployment**: GitHub Pages

## 📊 Features

- ✅ **Classic Klondike Rules**: Standard 7-tableau layout with stock and foundation piles
- 🎯 **Drag-and-Drop Interface**:  Intuitive card movement with visual feedback
- ↩️ **Undo Functionality**: Revert moves to correct mistakes
- 🎉 **Win Detection**: Automatic game-over modal when you complete the game
- 🔄 **New Game**:  Shuffle and restart anytime
- 📱 **Responsive Design**: Clean, card-game aesthetic with proper spacing
- 🎨 **Visual Feedback**: Color-coded suits (red/black) with proper card symbols (♥♠♣♦)

## 🎮 How to Play

1. **Objective**: Move all cards to the four foundation piles (one per suit) in ascending order from Ace to King
2. **Stock Pile**: Click to draw cards from the deck
3. **Tableau**:  Build down in alternating colors (red-black-red)
4. **Foundations**: Build up by suit starting with Ace
5. **Empty Tableau Spaces**: Only Kings can fill empty columns
6. **Controls**:
   - 🆕 **New Game** - Shuffle and start fresh
   - ⏮️ **Undo** - Reverse your last move

## 📁 Project Structure

```text
klondike-solitaire/
├── css/
│   └── styles.css          # Game styling and card design
├── js/
│   ├── card.js             # Card class (rank, suit, flip logic)
│   ├── solitaire.js        # Game engine (rules, validation, state)
│   └── main.js             # Entry point and initialization
├── index.html              # Main game interface
└── README.md               # You are here! 
```

## 🛠️ How to Run

1. **Clone the repository**:

   ```bash
   git clone https://github.com/AhmedIkram05/klondike-solitaire.git
   cd klondike-solitaire
   ```

2. **Open in browser**:

   ```bash
   # Start Local server
   python3 -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. **Start playing!** 🎮

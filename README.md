# Sudoku Master 🎮

A beautiful, interactive Sudoku game with multiple difficulty levels and grid sizes. Built with vanilla HTML, CSS, and JavaScript - no dependencies required!

![Sudoku Master](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## ✨ Features

- **Multiple Difficulty Levels**
  - Easy (45 clues) - Perfect for beginners
  - Intermediate (35 clues) - Moderate challenge
  - Difficult (30 clues) - Expert level
  - Extreme (25 clues) - Master level
  - Legend (22 clues) - Ultimate test

- **Multiple Grid Sizes**
  - Classic 9×9 Sudoku
  - Mega 16×16 Sudoku with hexadecimal notation (1-9, A-G)

- **Sudoku-X Variant**
  - Includes diagonal constraints for an extra challenge
  - Both main diagonals must contain unique numbers

- **Interactive UI**
  - Smooth animations and transitions
  - Responsive design for mobile and desktop
  - Visual feedback for selected cells
  - Error highlighting for invalid placements
  - Victory modal on puzzle completion

- **Game Controls**
  - Intuitive number pad for input
  - Clear cell functionality
  - Check solution validation
  - Reset puzzle option
  - Easy navigation back to level selection

## 🎯 How to Play

1. **Select a Difficulty Level** - Choose from Easy to Legend, or try the massive 16×16 grid
2. **Click a Cell** - Select an empty cell to place a number
3. **Enter a Number** - Use the number pad to fill in your answer
4. **Check Your Work** - Use the "CHECK" button to validate your placements
5. **Complete the Puzzle** - Fill all cells correctly to win!

### Sudoku-X Rules

In addition to standard Sudoku rules:
- Each row must contain unique numbers (1-9 or 1-G for 16×16)
- Each column must contain unique numbers
- Each box must contain unique numbers (3×3 for 9×9, 4×4 for 16×16)
- **Both main diagonals must also contain unique numbers**

## 🚀 Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/sudoku-master.git
```

2. Open `index.html` in your web browser

That's it! No build process or dependencies required.

## 🎨 Design Highlights

- **Modern Gradient UI** - Eye-catching purple gradient theme
- **Smooth Animations** - Fade-ins, hover effects, and transitions
- **Responsive Layout** - Adapts to different screen sizes
- **Visual Feedback** - Clear indication of fixed cells, selections, and errors
- **Professional Typography** - Clean, readable font choices

## 🛠️ Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with gradients, animations, and flexbox/grid
- **Vanilla JavaScript** - Pure JS with no frameworks or libraries

## 📱 Browser Compatibility

Works on all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge

Mobile friendly and touch-enabled.

## 🎮 Game Mechanics

### Puzzle Generation

- **9×9 Grids**: Uses a pattern-based algorithm with shuffled rows, columns, and numbers
- **16×16 Grids**: Similar algorithm scaled to 4×4 box structure
- **Random Variation**: Each game generates a unique puzzle
- **Guaranteed Solvability**: All puzzles are generated from valid solutions

### Validation

- Real-time checking available via "CHECK" button
- Diagonal constraint validation (Sudoku-X)
- Visual error highlighting with shake animation
- Automatic victory detection on completion

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 💡 Future Enhancements

Potential features for future versions:
- Timer functionality
- Hints system
- Save/load game state
- Statistics tracking
- Multiple puzzle variants (Killer Sudoku, Samurai Sudoku)
- Dark mode toggle
- Pencil marks/notes feature


## 🙏 Acknowledgments

- Inspired by classic Sudoku puzzles
- Sudoku-X variant adds diagonal constraints for extra challenge

---
Project Link: https://sudokku.netlify.app/
**Enjoy the game! Happy solving! 🎉**

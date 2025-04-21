# Advanced Tic Tac Toe

![Tic Tac Toe Game](https://github.com/user-attachments/assets/d4b98503-0295-465f-a714-3d46a035659d)


## 🎮 [Live Demo](https://tic-tac-toe-flux30s-projects.vercel.app/)

An elegant implementation of the classic Tic Tac Toe game with two variants: a traditional version and an advanced version with unique rules. Both games feature an intelligent AI opponent powered by the minimax algorithm.

## ✨ Features

- **Two Game Variants:**
  - **Classic Tic Tac Toe**: The traditional 3x3 grid game
  - **Advanced Tic Tac Toe**: A variant limiting each player to three pieces on the board
  
- **Intelligent AI Opponent:**
  - Powered by the minimax algorithm with alpha-beta pruning
  - Optimized for challenging but fair gameplay
  
- **Modern UI/UX:**
  - Responsive design for all devices
  - Smooth animations using GSAP
  - Dark theme with elegant visual elements
  
- **Mathematical Analysis:**
  - Detailed visualization of game complexity
  - Analysis of optimal strategies
  - Data-driven insights on game states

## 🧠 Game Rules

### Classic Tic Tac Toe
- Players take turns placing X or O on a 3x3 grid
- First player to align three of their symbols in a row, column, or diagonal wins
- The game ends in a draw if the board is filled without a winner

### Advanced Tic Tac Toe
- Each player is limited to three pieces on the board
- When placing a fourth piece, the player's oldest piece is removed
- This creates a more dynamic gameplay experience with shifting strategies

## 🛠️ Technologies Used

- HTML5 for structure
- CSS3 for styling and animations
- JavaScript for game logic and interactivity
- GSAP for advanced animations
- Chart.js for data visualization

## 🔍 Implementation Details

The AI implementation uses the minimax algorithm with alpha-beta pruning to evaluate possible moves:

```javascript
function minimax(board, depth, isMaximizing, alpha, beta) {
    // Recursive evaluation of game states
    // Returns optimal score for current player
    // ...
}
```

The game includes several key optimizations:
- Board state caching to avoid redundant calculations
- Symmetry detection to reduce the search space
- Progressive depth search based on game stage
- Performance optimizations for mobile devices

## 📊 Mathematical Analysis

The repository includes a detailed mathematical analysis page that explores:
- Game theory aspects of Tic Tac Toe
- State space complexity for both game variants
- Proof of optimal play resulting in draws
- Visualization of the decision tree

## 🚀 Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/flux30/tic-tac-toe.git
   ```

2. Open index.html in your browser to start playing

3. No build process or dependencies required for basic usage

## 👨‍💻 Author

Built with ❤️ by [Abhinav](https://github.com/flux30)

## 🔗 Links

- [GitHub Repository](https://github.com/flux30/tic-tac-toe)
- [Live Demo](https://tic-tac-toe-flux30s-projects.vercel.app/)

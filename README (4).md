# Educational Chess - AI Learning Tool

An interactive chess game with detailed AI analysis designed for learning chess strategy and understanding how chess engines think.

![Chess Game Screenshot](screenshot.png)

## Features

### 🤖 AI Analysis
- **Real-time position evaluation** - Visual bar showing who's winning
- **Move explanations** - Understand why each move is good or bad
- **Candidate moves** - See the top 5 moves the AI considered
- **Strategic reasoning** - Learn chess concepts like center control, development, and tactics
- **Depth analysis** - See how many moves ahead the AI calculated

### 🎓 Learning Tools
- **💡 Hint System** - Get AI suggestions when stuck
- **Move History** - Review all moves with notation
- **Position Scores** - Understand material and positional advantage
- **Educational Explanations** - Every move includes strategic context

### ♟️ Game Features
- **Multiple AI Levels**
  - Easy (Depth 1) - Beginner friendly
  - Medium (Depth 2) - Intermediate challenge
  - Hard (Depth 3) - Advanced opponent
- **Human vs AI** or **AI vs AI** modes
- **Standard chess rules** including castling and en passant
- **Save/Load games** to continue later
- **Download game logs** with full AI analysis
- **Undo moves** to try different strategies

### 📊 AI Engine Details
- Minimax algorithm with alpha-beta pruning
- Position evaluation using:
  - Material counting
  - Piece-square tables
  - Mobility scoring
  - King safety
  - Center control
- Standard algebraic notation (e.g., Nf3, exd5)

## How to Use

1. **Open the file** - Just open `chess_educational.html` in any modern web browser
2. **Choose players** - Select Human or AI for White and Black
3. **Start playing** - Click squares to move pieces
4. **Watch AI analysis** - See detailed explanations in the left panel
5. **Get hints** - Click the 💡 button for suggestions

## Understanding the Interface

### Evaluation Bar
- **White side** (left) = White's advantage
- **Black side** (right) = Black's advantage  
- **Number** = Position score in pawn units
  - `+2.0` = White is up ~2 pawns
  - `-1.5` = Black is up ~1.5 pawns
  - `0.0` = Equal position

### Coordinate Labels
- **Letters (a-h)** on bottom = columns
- **Numbers (1-8)** on left = rows
- Example: `e4` means column e, row 4

### AI Analysis Panel
- **Position Evaluation** - Overall assessment
- **Candidate Moves** - Top moves considered with scores
- **Strategy Explanation** - What the AI is planning
- **Depth Info** - How many moves ahead it looked

## Educational Value

This tool helps you:
- **Learn chess strategy** - Understand positional concepts
- **Improve calculation** - See how to evaluate positions
- **Study AI thinking** - Understand computer chess algorithms
- **Practice tactics** - Find the best moves with hints
- **Track progress** - Review games with detailed analysis

## Technical Details

- **Pure HTML/CSS/JavaScript** - No dependencies
- **Works offline** - No internet required after downloading
- **LocalStorage** - Save games in your browser
- **Responsive design** - Works on desktop and tablet

## Game Controls

| Button | Function |
|--------|----------|
| 💡 Get Hint | Show best move suggestion |
| ↩️ Undo Move | Take back last move |
| 💾 Save Game | Save current position |
| 📂 Load Game | Load saved game |
| 📥 Download Log | Export game with analysis |
| New Game | Start fresh game |

## For Educators

Perfect for:
- Teaching chess fundamentals
- Demonstrating computer science concepts (algorithms, tree search)
- Showing AI decision-making processes
- Interactive classroom demonstrations
- Self-paced learning

## License

Free to use and modify for educational purposes.

## Contributing

Feel free to fork and improve! Potential enhancements:
- Opening book database
- Endgame tablebases
- Puzzle mode
- Multiple board themes
- Sound effects
- Animation for moves
- PGN import/export

---

Made with ♟️ for chess learners everywhere


# ❌⭕ AI-Powered Tic-Tac-Toe Game  

A **Python-based Tic-Tac-Toe game** where you play against an unbeatable AI 🤖 using the **Minimax Algorithm**!  

## 🚀 Features  
✅ **Classic 3x3 Tic-Tac-Toe Board** 🎲  
✅ **AI Opponent with Minimax Algorithm** 🧠  
✅ **User vs AI Gameplay** – You play as 'X', AI plays as 'O' 🎮  
✅ **Handles Invalid Moves & Input Errors** 🚫  
✅ **Automatically Detects Winners & Draws** 🏆  

## 📌 How It Works  
1. **User starts** by entering row & column numbers (0-2) ✍️  
2. **AI calculates** the best move using the Minimax algorithm 🔢  
3. **Game updates** the board and displays results after each turn ⚡  
4. **Ends when there's a winner** or no moves left 🚀  

## 🏆 Minimax Algorithm Explained  
- **Recursively evaluates** all possible game outcomes 🤓  
- **AI chooses moves** that maximize its chance of winning 🏅  
- **Guaranteed Unbeatable** – AI will always win or force a draw! 💪  

## 🛠️ Code Overview  
```python
# AI calculates the best move using Minimax
best_move(board)  

# User inputs a move
row, col = map(int, input("Enter row and column (0-2): ").split())  

# Game checks for a winner
winner = check_winner(board)  
```

## 🎯 Example Game  
```
 X | O | X 
-----------
 O | X | O 
-----------
 O | X | X 
```
**Result:** It's a draw! 🤝  

## 📢 Future Enhancements  
🔹 Add a **GUI version** with Tkinter or Pygame 🎨  
🔹 Support for **multiplayer mode** (Player vs Player) 👥  
🔹 Difficulty levels (Easy, Medium, Hard) ⚙️  

---

### 🎯 Get Started  
🔹 Clone the repository  
🔹 Run the Python script  
🔹 Play against the AI & try to win! 🚀  

---

👨‍💻 Developed as part of **CodSoft Internship – Task 2** 🎓  
Feel free to contribute & improve the game! 💡  

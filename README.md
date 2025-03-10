# **Noughts and Crosses with Alpha-Beta Pruning**

## **Problem Statement**
Noughts and Crosses (also known as Tic-Tac-Toe) is a classic two-player game where players take turns marking 'X' or 'O' on a 3x3 grid. The objective is to form a straight line (horizontally, vertically, or diagonally) before the opponent does. 

This project implements an **AI-powered Noughts and Crosses agent** using the **Minimax algorithm with Alpha-Beta Pruning**. The AI plays optimally, ensuring that it always selects the best possible move while reducing unnecessary calculations.

---

## **How It Works**
### **1. Game Representation:**
- The board is a 3x3 grid represented using a **NumPy array**.
- Values used:
  - `-1` → Human player ('X')
  - `1` → AI player ('O')
  - `0` → Empty spaces

### **2. AI Decision-Making:**
- The **Minimax Algorithm** is used to evaluate possible moves and determine the best one.
- **Alpha-Beta Pruning** improves efficiency by cutting off unnecessary game state evaluations.

### **3. Player Moves:**
- The **human player** makes the first move by entering row and column indices.
- The **AI then calculates the best move** and plays optimally.
- The game continues until there is a winner or a draw.

### **4. Winning Conditions:**
- A player wins if they align three of their symbols ('X' or 'O') in a row, column, or diagonal.
- The game results in a draw if all spaces are filled without a winner.

---

## **Technologies Used**
- **Python** (for implementation)
- **NumPy** (for matrix representation and operations)
- **Google Colab** (for execution)

---

## **How to Run the Code**
1. Open **Google Colab** or any Python environment.
2. Copy and paste the provided Python code.
3. Run the script and follow the instructions for entering moves.
4. The AI will play optimally, and the result will be displayed.

---

## **Example Output**
```
Tic-Tac-Toe with AI (Alpha-Beta Pruning)
- - -
- - -
- - -
Enter row and column (0-2): 0 0
X - -
- - -
- - -
AI is thinking...
X - O
- - -
- - -
...
AI Wins!
```

---

## **Conclusion**
This project successfully implements an AI-driven Tic-Tac-Toe game where the AI uses **Minimax with Alpha-Beta Pruning** to play optimally. The result is an intelligent system that never loses and always finds the best possible move.

---

## **References**
- [Minimax Algorithm - Wikipedia](https://en.wikipedia.org/wiki/Minimax)
- [Alpha-Beta Pruning - GeeksforGeeks](https://www.geeksforgeeks.org/alpha-beta-pruning/)

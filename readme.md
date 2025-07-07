# 🧩 Crossword Puzzle Generator

Welcome to the **Crossword Puzzle Generator**!  
Unleash the power of Artificial Intelligence and Constraint Satisfaction Problems (CSP) to create, solve, and visualize crosswords with elegance and efficiency.  
Crafted with Python, this project is a testament to algorithmic finesse and software craftsmanship.

---

## ✨ Features

- **Automated Crossword Generation**: Input your structure and word list, and let the CSP engine do the magic!
- **Smart Solving**: Employs node and arc consistency, backtracking, and heuristics for optimal solutions.
- **Beautiful Visualization**: Save your crossword as a high-resolution image for sharing or printing.
- **Terminal Output**: Instantly preview your crossword in the terminal.
- **Customizable**: Easily adapt the structure and vocabulary to your needs.

---

## 🚀 Getting Started

### 1. Clone the Repository

```sh
git clone https://github.com/yourusername/crossword.git
cd crossword
```

### 2. Install Dependencies

- Python 3.7+
- [Pillow](https://python-pillow.org/) for image generation

```sh
pip install pillow
```

### 3. Prepare Your Files

- **Structure File**: Use `_` for open cells and any other character for blocks.
- **Words File**: One word per line, uppercase recommended.

### 4. Generate a Crossword

```sh
python generate.py structure.txt words.txt [output.png]
```

- `structure.txt`: Your crossword grid structure
- `words.txt`: List of words to use
- `output.png` (optional): Save the crossword as an image

---

## 🛠️ Project Structure

```
crossword.py      # Core logic for crossword structure and variables
generate.py       # CSP solver, image generation, and CLI
```

---

## 🧠 How It Works

This project models the crossword as a **Constraint Satisfaction Problem**:
- **Variables**: Each word slot in the grid
- **Domains**: Possible words that fit each slot
- **Constraints**: Overlapping letters must match, and words must not repeat

The solver enforces **node consistency** (word length), **arc consistency** (overlapping letters), and uses **backtracking search** with heuristics for efficient solving.

---

## 📸 Example Output

![Crossword Example](assets/example.png)

---

## 👨‍💻 Author

- **Your Name**  
  [LinkedIn](https://linkedin.com/in/yourprofile) | [GitHub](https://github.com/yourusername)

---

## ⭐️ Why This Project?

- Demonstrates advanced Python and AI concepts
- Showcases clean, modular, and extensible code
- Perfect for your portfolio or resume!

---

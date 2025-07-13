# 🧮 NumPy Mini Projects

This repository contains two beginner-friendly NumPy mini projects designed to strengthen your fundamental understanding of array operations, reshaping, slicing, and real-world data manipulation using NumPy.

## 📌 Projects Included

### ✅ 1. Student Marks Analyzer

Analyze and process the performance of students using randomly generated marks data.

#### 🔍 Key Concepts Used:
- 2D array creation using `np.random.randint`
- Axis-based aggregation using `np.mean`, `np.sum`, `np.argmax`
- Boolean masking (e.g., students scoring above 80 in all subjects)
- Reshaping and flattening arrays (`reshape`, `flatten`, `ravel`)

#### 📊 Features:
- Calculate average marks per student
- Identify top scorers in each subject
- Filter high-achieving students
- Reshape data for model-style input

---

### ✅ 2. Sales Tracker for a Store

Simulates weekly sales data for products and performs business analysis.

#### 🔍 Key Concepts Used:
- Matrix operations and summarization (`sum`, `mean`, `argmax`)
- Weekly and product-wise analysis
- `hstack`, `vstack` for adding bonus columns and summary rows
- Reshaping data for ML or reporting formats (`reshape(1, -1)`, `flatten`)

#### 📊 Features:
- Calculate weekly and product-level sales totals and averages
- Identify best/worst performing weeks and products
- Add special event sales using `hstack`
- Prepare data for ML pipelines by reshaping

---
# ✅ 3.🧩 Matrix Puzzle – Grid Operator (NumPy Mini Project)

A logic-based puzzle simulator using NumPy arrays. This mini project helps strengthen concepts like slicing, indexing, reshaping, Boolean masking, flipping, and more.

---

## 🧠 Objective

To create and manipulate a 5×5 grid (game board) using various NumPy techniques, simulating logical operations used in puzzles, board games, and grid-based computations.

---

## 🔧 Features & Concepts Used

### ✅ Step-by-step operations:
1. **Create a 5×5 Matrix** using `np.arange` and `reshape`
2. **Pattern Extraction:**
   - Center 2×2 and 3×3 blocks
   - Corners
   - Both diagonals
   - Outer border (flat & frame style)
3. **Flipping the Matrix:**
   - Horizontally (Left ↔ Right) using `np.fliplr`
   - Vertically (Top ↕ Bottom) using `np.flipud`
   - Rotate 180° using `np.rot90` or double flip
4. **Conditional Logic with Boolean Masking:**
   - Replace even/odd values
   - Extract values greater than a threshold
   - Use `np.where` for conditional replacement
5. **Flattening & Reshaping:**
   - Convert grid to 1D, 1×25, and 25×1
   - Pad and reshape to 3×8 matrix
   - Reverse using slicing

---

## 💻 Code Structure



## 🛠️ Tools Used

- Python 🐍
- NumPy 🧮
- Jupyter Notebook (for exploration)

---



🙌 Author
Om S. Mishra
Aspiring Data Scientist | Python & NumPy Enthusiast
🔗 LinkedIn | 🌐 Portfolio (coming soon)

⭐ Show your support
If you find this helpful, feel free to star ⭐ this repo and share it with your fellow learners!



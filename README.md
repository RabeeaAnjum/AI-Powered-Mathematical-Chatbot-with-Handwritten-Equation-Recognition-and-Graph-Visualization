# 🤖 AI-Powered Mathematical Chatbot with Handwritten Equation Recognition and Graph Visualization

An intelligent AI-based mathematical assistant that can solve symbolic mathematical problems, recognize handwritten equations using Optical Character Recognition (OCR), and visualize mathematical functions through graph plotting.

This project integrates **Artificial Intelligence (AI)**, **Natural Language Processing (NLP)**, **Optical Character Recognition (OCR)**, **Symbolic Mathematics**, and **Data Visualization** into a single educational platform.

---

# 📌 Features

✅ Solve algebraic equations

✅ Differentiate mathematical expressions

✅ Integrate mathematical functions

✅ Simplify and factorize equations

✅ Recognize handwritten equations from uploaded images

✅ Plot graphs of mathematical functions

✅ Interactive command-line chatbot

---

# 📖 Project Overview

Traditional calculators only provide numerical answers and lack conversational interaction, symbolic computation, handwritten equation recognition, and graph visualization.

This project overcomes these limitations by combining multiple AI technologies into one intelligent educational assistant capable of:

- Understanding mathematical expressions
- Performing symbolic computations
- Reading handwritten equations
- Plotting mathematical graphs
- Providing accurate mathematical solutions

---

# 🛠 Technologies Used

- Python 3.10+
- Google Colab
- SymPy
- EasyOCR
- OpenCV
- NumPy
- Matplotlib
- Pillow

---

# 📂 Project Structure

```
AI-Mathematics-Chatbot/
│
├── AI_Math_Chatbot.ipynb
├── README.md
├── requirements.txt
├── sample_images/
│   ├── equation1.png
│   ├── equation2.png
│
├── screenshots/
│   ├── chatbot_menu.png
│   ├── graph_output.png
│   ├── ocr_output.png
│
└── LICENSE
```

---

# ⚙ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/AI-Mathematics-Chatbot.git
```

Move into the project folder:

```bash
cd AI-Mathematics-Chatbot
```

Install the required libraries:

```bash
pip install sympy
pip install easyocr
pip install opencv-python
pip install matplotlib
pip install pillow
```

Or install all dependencies using:

```bash
pip install -r requirements.txt
```

---

# ▶ Running the Project

Launch the notebook in Google Colab or Jupyter Notebook and execute all cells.

The chatbot menu will appear:

```
==========================
AI Mathematics Chatbot
==========================

1. Solve Equation
2. Differentiate
3. Integrate
4. Plot Graph
5. Handwritten Equation Recognition
6. Exit
```

---

# 🧠 Supported Operations

### 1. Solve Equations

Example:

Input

```
x^2-5*x+6=0
```

Output

```
Solution:
[2, 3]

Factorized Form:
(x-2)(x-3)
```

---

### 2. Differentiation

Input

```
x^2-5*x+6
```

Output

```
2*x - 5
```

---

### 3. Integration

Input

```
x^2-5*x+6
```

Output

```
x^3/3 - 5*x^2/2 + 6*x + C
```

---

### 4. Graph Plotting

Input

```
x^2-5*x+6
```

Output

- Displays the graph of the function using Matplotlib.

---

### 5. Handwritten Equation Recognition

Upload an image containing a handwritten mathematical equation.

Example:

Image:

```
x² + 5x + 6 = 0
```

OCR Output:

```
x^2+5*x+6=0
```

The chatbot automatically solves the extracted equation.

---

# 📊 Workflow

```
User Input
     │
     ▼
Text / Image
     │
     ▼
EasyOCR (if image)
     │
     ▼
Equation Extraction
     │
     ▼
NLP Processing
     │
     ▼
SymPy Engine
     │
     ├──────── Solve
     ├──────── Differentiate
     ├──────── Integrate
     └──────── Simplify
               │
               ▼
Graph Visualization (Optional)
               │
               ▼
Results Displayed
```

---

# 📚 Libraries Used

## SymPy

Used for symbolic mathematics.

Functions:

- solve()
- diff()
- integrate()
- factor()
- sympify()

---

## EasyOCR

Used for recognizing handwritten mathematical expressions from uploaded images.

---

## Matplotlib

Used for graph plotting and visualization.

---

## NumPy

Used for numerical array generation and plotting support.

---

## OpenCV

Used for image processing before OCR extraction.

---

# 🧪 Test Cases

## Test Case 1

Input

```
x^2-5*x+6=0
```

Expected Output

```
[2,3]
```

---

## Test Case 2

Input

```
Differentiate x^2-5*x+6
```

Expected Output

```
2*x-5
```

---

## Test Case 3

Input

```
Integrate x^2-5*x+6
```

Expected Output

```
x^3/3-5*x^2/2+6*x+C
```

---

## Test Case 4

Input

```
Plot x^2-5*x+6
```

Expected Output

Graph of the quadratic function.

---

## Test Case 5

Input

Handwritten equation image.

Expected Output

OCR extracts the equation and displays the correct symbolic solution.

---

# ✅ Advantages

- User-friendly interface
- Supports symbolic mathematics
- Reads handwritten equations
- Generates mathematical graphs
- Easy to use for students
- Low computational requirements
- Cloud-compatible with Google Colab
- Modular and extensible design

---

# ⚠ Limitations

- OCR accuracy depends on handwriting quality.
- Supports only single-variable mathematical expressions.
- Complex mathematical notation may not always be recognized correctly.
- No support for advanced theorem proving.

---

# 🚀 Future Enhancements

- Deep Learning-based OCR
- Voice-controlled chatbot
- Multi-language support
- Real-time camera scanning
- Matrix and vector operations
- Differential equation solver
- AI-generated mathematical explanations
- Mobile application
- Integration with Large Language Models (LLMs)

---

# 🎯 Applications

- Intelligent tutoring systems
- Mathematics education
- E-learning platforms
- Homework assistance
- Engineering calculations
- Research and symbolic computation

---

# 📈 Learning Outcomes

This project demonstrates practical implementation of:

- Artificial Intelligence
- Natural Language Processing
- Optical Character Recognition
- Symbolic Mathematics
- Computer Vision
- Data Visualization
- Educational Technology

---

# 👩‍💻 Author

**Rabeea Anjum**

Bachelor of Science in Computer Engineering

---

# 📄 License

This project is intended for educational and academic purposes.

---

# ⭐ If you find this project useful, consider giving it a star on GitHub!

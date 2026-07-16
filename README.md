# ❤️ Heart Drawing using Python Turtle

A simple Python project that uses the built-in **Turtle Graphics** module to draw a heart shape and display custom text inside it. This project is ideal for beginners who want to learn graphical programming in Python.

>![alt text](image.png)
---

## Overview

Python's **Turtle Graphics** module provides a simple way to create drawings and shapes using a virtual pen (called a *turtle*) that moves across the screen.

In this project, the turtle is used to:

- Draw a heart shape using smooth curves
- Fill the heart with color
- Display text inside the heart
- Demonstrate basic Turtle Graphics concepts such as movement, rotation, loops, colors, and writing text

---

## Requirements

- Python 3.x
- Turtle module (built into Python)

> **Note:** The Turtle module comes pre-installed with Python, so no additional installation is usually required.

If needed, you can install it using:

```bash
pip install PythonTurtle
```

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/Md-faisal78/heart-drawing-python.git
```

Navigate to the project directory:

```bash
cd heart-drawing-python
```

Run the program:

```bash
python heart.py
```

---

## Project Structure

```
heart-drawing-python/
│
├── main.py
├── README.md
├── LICENSE
└── screenshots/
    └── output.png
```

---

## Step-by-Step Approach

1. Import the Turtle module.
2. Create a Turtle object to act as the drawing pen.
3. Define a function to draw smooth curves.
4. Draw the heart by combining straight lines and curves.
5. Fill the heart with a color.
6. Display text inside the heart.
7. Hide the turtle cursor after the drawing is complete.

---

## Drawing Logic

### Left Side
- Rotate the turtle **140° left**.
- Move forward to create the left edge of the heart.

### Left Curve
- Repeat **200** times:
  - Move forward by **1** unit.
  - Turn **1° right**.

### Right Curve
- Turn **120° left**.
- Repeat the same curve function to form the right half of the heart.

### Right Side
- Move forward to complete the heart shape.

### Fill Color
- Begin filling before drawing.
- End filling after the heart is complete.

### Add Text
- Lift the pen using `pen.up()`.
- Move to the desired position.
- Display text using `pen.write()`.

### Hide Turtle
- Hide the turtle cursor using:

```python
pen.ht()
```


## Concepts Used

- Functions
- Loops
- Turtle Graphics
- Pen Movement
- Coordinates
- Colors
- Text Rendering
- Basic Computer Graphics

---

## Output

Example:

```
Screenshots/op1.png
```

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for more information.
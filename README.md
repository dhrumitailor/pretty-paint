# 🎨 Pretty Paint

Pretty Paint is a classic Paint-style graphics application developed in **C/C++ using the Turbo C++ BGI Graphics Library**. It provides an interactive drawing environment where users can create basic graphics using a mouse-driven interface, select colors, draw shapes, and save or load their artwork.

## ✨ Features

- 🖱️ Mouse-based drawing interface
- 🎨 Color palette with multiple color options
- ✏️ Freehand drawing tool
- 📏 Line drawing tool
- 📍 Pixel plotting tool
- ⚪ Ellipse/Circle drawing tool
- ▭ Rectangle drawing tool
- 🟪 Filled Rectangle (Bar) tool
- 🧹 Clear canvas option
- 💾 Save drawings to a file
- 📂 Load previously saved drawings
- ⌨️ Keyboard shortcuts for quick operations

## 🛠 Technologies Used

- C/C++
- Turbo C++
- BGI Graphics Library
- DOS Mouse Interrupts (INT 33h)
- File Handling

## 🚀 How It Works

The application provides:

- A drawing canvas for creating graphics
- A side panel containing drawing tools
- A color palette for selecting drawing colors
- Save and load functionality for preserving artwork

Users can select a drawing tool, choose a color, and interact with the canvas using the mouse.

## 🎯 Available Tools

| Tool | Function |
|--------|----------|
| Bar | Draw filled rectangles |
| Line | Draw straight lines |
| Pixel | Plot individual pixels |
| Ellipse | Draw circles and ellipses |
| Freehand | Freehand sketching |
| Rectangle | Draw rectangles |
| Clear | Clear the canvas |
| Save | Save drawing to file |
| Load | Load saved drawing |

## ⌨️ Controls

| Key | Action |
|------|--------|
| ESC | Exit application |
| Ctrl + S | Save drawing |
| Ctrl + O | Load drawing |

## 📂 File Storage

Drawings are stored in a binary file named:

drawing.dat


The application saves pixel color information from the drawing area and restores it when loading.

## 📚 Concepts Demonstrated

This project demonstrates:

- Computer Graphics Programming
- Event-Driven Programming
- Mouse Handling
- Graphics Primitives
- File I/O Operations
- User Interface Design
- DOS Interrupt Programming

## ▶️ Running the Project

1. Install Turbo C++.
2. Configure the BGI graphics library.
3. Open the source code in Turbo C++.
4. Compile the project.
5. Run the executable.
6. Use the mouse to draw and interact with the tools.

## 🎓 Educational Purpose

Pretty Paint is a beginner-friendly graphics project that helps students understand:

- Graphics programming fundamentals
- Drawing algorithms
- User interaction through mouse events
- Legacy DOS graphics development
- File management in C/C++

## 👨‍💻 Author

**Dhrumi**

---

A simple and educational Paint application built with Turbo C++ to explore the fundamentals of graphics programming and interactive software development.

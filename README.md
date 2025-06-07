# 🧱 Tetris in x86 Assembly

**Tetris** is a complete Tetris clone developed in **x86 Assembly language (8088)** using low-level hardware control, designed to run in a DOS environment. It features custom video rendering, score tracking, real-time timer, and shape rotations—all from scratch.

>  This project was developed as part of a university coursework project on low-level programming and systems architecture.

---

##  Features

- Tetromino shapes: Square, L-shape, Line, Plus
- Time tracking via BIOS timer interrupt (`int 08h`)
- Real-time key detection for movement (A, D), rotation (W/S)
- Manual memory boundary checks
- Row-clearing logic with base memory update
- Custom animated splash and end screens using pixel graphics
- Runs in real mode using BIOS & DOS interrupts

---

## 🛠 Tools Used

| Tool      | Purpose                          |
|-----------|----------------------------------|
| **NASM**  | Assembler to compile `.asm` code |
| **AFD**   | Debugger for DOS programs        |
| **DOSBox**| Emulator for running `.COM` file |

---
## 👥 Contributors

This project was made possible through collaborative effort, creativity, and persistence during our coursework.
Special thanks to these who contributed their time, ideas, and support throughout the development process:
-  **Romana**  @romana-12
-  **Marusha** @marooshamalik05


# 🪓 Hangman Game in Assembly (MASM + Irvine32)

Welcome to the classic **Hangman** game — reimagined at the hardware-near level using x86 Assembly Language! This is not your average scripting project. It’s a deep dive into bits, bytes, and bare-metal fun, with the help of **MASM** and **Kip Irvine's Irvine32 library**.

## 🎮 About the Game

The goal is simple: guess the secret word before the gallows are fully drawn. The twist? You’ll be experiencing every step the CPU takes to make that happen.

Features:
- Randomly selected words from a built-in list
- ASCII-art gallows that update as you guess
- Letter-by-letter input with case-insensitive checks
- Dynamic message boxes for win/loss prompts
- Replay functionality — because revenge is sweet!

---

## 🛠️ Requirements

To build and run this project, you'll need:

- **Microsoft Visual Studio** (any version supporting MASM)
- **Irvine32 Library**  
  Download from: [kipirvine.com](http://www.kipirvine.com/asm/)
- MASM Assembler properly configured with:
  - `Irvine32.inc`
  - `Irvine32.lib`
  - `kernel32.lib`, `user32.lib`

Ensure your linker settings include these libraries and paths to the Irvine include/lib folders.

---

## 🚀 How to Run

1. Clone this repo or download the source files.

2. Open Visual Studio and create a new **MASM Assembly project** or use the provided `.asm` file.

3. Add the following to your **project settings**:
   - `Include Directories`: Path to Irvine32's `include/`
   - `Library Directories`: Path to Irvine32's `lib/`

4. Add `Irvine32.lib`, `kernel32.lib`, and `user32.lib` to the **Linker > Input > Additional Dependencies**.

5. Build and run!




## 🤓 Learning Objectives

This project is perfect for:
- Students learning Assembly and x86 architecture
- Understanding low-level string handling
- Practicing loops, conditionals, and memory access
- Getting familiar with the Irvine32 library
- Reinforcing hardware-software interaction concepts



## 📚 References

- Kip Irvine, *Assembly Language for Intel-Based Computers*, 6th Edition
- [Irvine32 Library](http://www.kipirvine.com/asm/)
- Stefan Tešanović & Predrag Mitrović, *Development of the Game Hangman in Assembly Programming Language*, Telfor Journal 2018

## ❤️ Credits

Developed by [Shehzeen Tasawar].  
Inspired by the challenge of creating a full game in Assembly.  
ASCII art crafted with love and ANSI escape codes.



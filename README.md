# Speed Typing Test 

A terminal-based typing speed test game built with **Python** and the **curses** library.  
The game challenges you to type a randomly selected text snippet as quickly and accurately as possible while tracking your **Words Per Minute (WPM)**.

---

## Features
- Random text selection from a `text.txt` file.  
- Real-time WPM calculation.  
- Color-coded typing feedback:
  - ✅ Green = Correct character  
  - ❌ Red = Incorrect character  
- Backspace support to fix mistakes.  
- Option to exit anytime with **ESC**.  

---

## Requirements
- Python 3.6+  
- curses (already included with Python on Linux/macOS; use `windows-curses` for Windows)

Install on Windows:
```bash
pip install windows-curses

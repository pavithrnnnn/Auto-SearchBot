# 🔍 Edge Search Automation Bot  
A simple but powerful Windows automation bot that performs random Bing/Edge searches using **PyAutoGUI** and **keyboard** libraries.  
The script generates natural random sentences and performs real human-like searches in Microsoft Edge.

---

## ⚙️ Features
- 🖱️ OS-level mouse + keyboard automation  
- 🔤 Random word-based sentence generator  
- ⏳ Human-like random delays between searches  
- 🧠 Failsafe: Move mouse to top-left corner to stop  
- ❌ Press `q` anytime to instantly quit the script  
- 🛑 No browser drivers required — works with your real Edge installation  

---

## 📦 Requirements

Install dependencies:

```bash
pip install pyautogui 
pip install pillow pygetwindow pymsgbox mouseinfo
pip install keyboard

---
##🚀 How It Works

- Opens Microsoft Edge
- Generates a random 3–7 word sentence
- Focuses the address bar
- Types the query slowly
- Presses Enter
- Waits a random delay
- Repeats for N searches

---
## 🛑 Failsafe System

- Move your mouse to top-left corner → script stops instantly
- Press Q → quits safely
- You will never get stuck in automation loops.

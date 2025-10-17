# 👾 Retro Terminal Simulator

> A web-based retro terminal simulator that turns your browser into a glowing green command-line interface

---

## 🧩 Overview

**Retro Terminal Simulator** is a fully self-contained, web-based command shell emulator.  
It includes a virtual file system (VFS), modal applications, and interactive commands.

---

## ✨ Key Features

### 📂 Virtual File System (VFS)
Supports core shell-like commands:

| Command | Description |
|----------|--------------|
| `ls` | List files and directories |
| `cd` | Change directory |
| `mkdir` | Create directory |
| `touch` | Create file |
| `cat` | Display file contents |
| `rm` | Remove file or directory |

### 🧠 Modal Session Control
Some commands enter **exclusive interactive modes** that must be exited using `.` (dot) or **ESC**:
- `edit` → In-memory text editor  
- `script` → Command scripting tool  
- `guess` → Number guessing mini-game  

### 🧰 Custom Commands
| Command | Function |
|----------|-----------|
| `script` | Create and execute multi-line command scripts within VFS |
| `guess` | Simple number guessing game (1–100) |
| `colorcycle` | Cycles the terminal color scheme (ESC to stop) |
| `autocode` | Simulates automated typing of code |

### 📱 Responsive Design 
- Retro CRT-style green-on-black interface  
- Optional animated color effects

---


## 🧱 Technology Stack

| Layer | Technology | Notes |
|-------|-------------|-------|
| Structure | **HTML5** | Provides markup and layout |
| Styling | **Inline CSS** | Handles color cycling and retro glow effects |
| Logic | **Vanilla JavaScript** | Implements VFS, command handling, and modal sessions |

---

**Enjoy** 🕹️💾

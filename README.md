# 🐧 My Bash Shell Setup – Learning Shell Scripting

Hey there! 👋  

This repository is a part of my journey into learning Shell Scripting 🧠⚙️. I'm using it to understand how the terminal works, how to customize it, and how to write effective and clean Bash scripts. It includes the configuration files I'm working with as I learn more about the shell.

## 📂 What's Inside?

This repo includes important shell startup files that control how the terminal behaves when opened, used, and closed:

- `.bashrc` – Runs every time a new terminal window is opened. Used for aliases, color settings, prompt customization, and more.  
- `.profile` – Used for setting environment variables and paths during login sessions.  
- `.bash_logout` – Runs when I close the terminal. Useful for clearing the screen or cleaning up.  

## 💡 Why I Made This

I'm currently learning:  
- How the Bash shell works  
- How to automate tasks with scripts  
- How to personalize my terminal  
- How history, aliases, and environment variables function  

So I made this repository to track my learning and experiment with real configurations. It's my little lab 🧪  

## 🧰 Features I’ve Added So Far

### ✅ Terminal Improvements  
- Prevents duplicate history entries  
- Automatically adjusts terminal size on resize  
- Appends to history instead of overwriting it  

### 🎨 Prompt Customization  
- Colorful and useful prompt showing:  
  `user@hostname:~/current-folder$`  

### 📁 Helpful Aliases  
To speed up common commands:  

| Command | Action                     |
|---------|----------------------------|
| `ll`    | List all files in detail   |
| `la`    | List all files (even hidden) |
| `l`     | Compact file listing       |

### 🔍 Search Helpers  
Color-enhanced search using:  
`grep`, `fgrep`, `egrep` (with `--color=auto`)  

### 🔔 Notification on Long Commands  
`sleep 5; alert`  
I get a desktop notification when a long-running command finishes.  

## 🌱 Still Learning...  
This is a work-in-progress!  
I'll keep updating it as I learn new shell scripting tricks and terminal tips.  
Feel free to clone, explore, or suggest improvements!  

Thanks for checking out my learning project! 🙌  
Happy hacking! 🐧💻  

# Section 1: Introduction & Terminal Basics

🎯 **Scenario:**  
Imagine you’ve just boarded a **Linux spaceship** 🚀. The terminal is your **cockpit control panel**.  
Before we start flying, let’s learn how to check who you are, where you are, and how to keep your cockpit tidy.

---

## ✅ Learning Objectives / Use Cases
By the end of this section, you’ll be able to:
1. Identify which **shell** (cockpit) you are using.  
2. Check your **username** (pilot name).  
3. Find your **current location** in the system (like a map).  
4. Clear your terminal screen when it looks messy.  

---

## 🖥️ Step-by-Step Instructions with Commands

### 1. Check your shell type (what cockpit you’re in):
```bash
echo $SHELL
```
- This prints the shell you are using.  
- Common shells:  
  - `/bin/bash` → Bash shell (most common)  
  - `/bin/zsh` → Z shell  
- Think of it like knowing whether your cockpit controls are **digital** or **analog**.

---

### 2. Find out your username (who’s flying the ship):
```bash
whoami
```
- This prints your **login name**.  
- Example: `labuser`  
- Just like a spaceship needs an **authorized pilot**, Linux wants to know who’s in control.

---

### 3. Check your current working directory (where in the galaxy you are):
```bash
pwd
```
- `pwd` means **print working directory**.  
- Example output: `/home/labuser`  
- Think of this as your **GPS location** inside Linux.  

---

### 4. Clear your cockpit screen (make it tidy):
```bash
clear
```
- Removes all clutter from the terminal window.  
- Just like cleaning your control panel so you can focus.  

---

## 🏆 Mini-Challenge
Now let’s test what you’ve learned:

1. Run:
```bash
pwd
```
→ Note your current location.  

2. Go back to your **home base** with:
```bash
cd ~
```
→ `~` always means *your home directory*.  

3. Confirm:
```bash
pwd
```
- Did the path return to `/home/your-username`?  
- If yes, you successfully navigated back home! 🎉  

---

## 🚀 Real-World Use Case
- When logging into a **remote server**, the first thing an engineer does is check:  
  - **Who they are logged in as** (`whoami`)  
  - **Where they are in the system** (`pwd`)  
- This prevents mistakes like deleting files in the wrong directory or using the wrong user account.  

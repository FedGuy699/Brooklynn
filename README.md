# Brooklynn

**Brooklynn** is a simple, lightweight window manager primarily built for personal use to resolve DisplayLink-related issues.

Brooklynn uses about **200 KB of memory** from my testing, making it good for lightweight setups.

# Feel free to make commits!

**Brooklynn** is not just mine it is for everyone, so if you have a commit you would like to make, feel free.

---

## ✨ Features

- 🧠 Simple and easy to use
- 🪟 Floating window layouts
- ⚡ Fast startup and low memory usage (~200 KB)
- 🛠️ Custom keybindings via `~/.config/brooklynn/config`

---

## 📸 Screenshot

![Brooklynn Screenshot](screenshot.png)

---

## 📦 Install

please if you are reading this dont use tiling its broken

    yay -S brooklynn-git

or for none arch users clone the repo compile the c++ file and move the binary to /usr/local/bin and move the .desktop file to /usr/share/xsessions

## Compile 

    g++ -o brooklynn brooklynn.cpp config.cpp launch.cpp monitor.cpp window.cpp lock.cpp paper.cpp -lX11 -lXrandr -lXft -I/usr/include/freetype2 -lpam



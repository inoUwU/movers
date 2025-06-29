<div align="center">
<img src="https://emoji2svg.deno.dev/api/🏹" alt="eyecatch" height="100">

# Movers

</div>  

## 💡 Concept

**Movers** is a lightweight tool written in Rust that lets you control your mouse cursor using only the keyboard.
The goal is simple: **"Don't touch the mouse anymore."** That's it.
> **move + rs = movers**

---

## 🧱 Status

| Item       | Details                                          |
| ---------- | ------------------------------------------------ |
| OS Support | Windows (planned)                                |
| Language   | Rust                                             |
| Stage      | 🧠 Concept Design                                |
| Control    | Keyboard mappings for cursor movement and clicks |

---

## 🎮 Operation Preview (Planned)

| Key Combo            | Action            |
| -------------------- | ----------------- |
| `Ctrl + Alt + H`     | Move cursor left  |
| `Ctrl + Alt + L`     | Move cursor right |
| `Ctrl + Alt + J`     | Move down         |
| `Ctrl + Alt + K`     | Move up           |
| `Ctrl + Alt + Space` | Left click        |
| `Ctrl + Alt + Enter` | Right click       |

> Key mappings will be configurable (e.g. via `.toml` files).

---

## 🚧 Planned Features

* [x] Windows support
* [ ] Fast, low-latency cursor movement
* [ ] Customizable key mappings
* [ ] System tray integration
* [ ] Run on startup with minimal resource usage
* [ ] Temporary disable via hotkey toggle

---

## 🦀 Built With

* Rust + `windows-rs` or `winapi` for low-level Windows APIs
* Input libraries under consideration: `device_query`, `inputbot`, `enigo`, etc.

---

## 📜 License
[MIT License](https://github.com/inoUwU/movers/blob/main/LICENSE)

---

## 🧠 Motivation

You don’t need a mouse anymore.
**Movers** is built for developers and power users who want full control using only the keyboard.

---

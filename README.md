<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=4682B4&height=200&section=header&text=FluentQuest&fontSize=50&fontColor=fff&animation=twinkling&fontAlignY=40&desc=Terminal%20Game%20|%20Language%20Learning%20|%20Interactive%20Practice&descAlignY=60&descSize=18">

<p align="center">
  <i>A fun and interactive terminal game to level up your language skills — one quest at a time.</i>
</p>

[![Swift](https://img.shields.io/badge/Swift-5.5+-FA7343?style=for-the-badge&logo=swift&logoColor=white)](https://swift.org)
[![Platform](https://img.shields.io/badge/Platform-macOS%20Terminal-000000?style=for-the-badge&logo=apple&logoColor=white)](https://developer.apple.com/macos/)
[![Xcode](https://img.shields.io/badge/Xcode-14+-1575F9?style=for-the-badge&logo=xcode&logoColor=white)](https://developer.apple.com/xcode/)
[![License](https://img.shields.io/badge/License-MIT-3DA639?style=for-the-badge)](LICENSE)

</div>

---

## 📑 Table of Contents

- [About](#-about)
- [Screens](#-screens)
- [Features](#-features)
- [Exercises & Study Modes](#-exercises--study-modes)
- [User Flow](#-user-flow)
- [Project Structure](#-project-structure)
- [Dependencies](#-dependencies)
- [Getting Started](#-getting-started)
- [Team](#-team)
- [License](#-license)

---

## ✨ About

**FluentQuest** is a fully interactive **terminal game** built in Swift that turns
language practice into a quest. Navigate hand-crafted ASCII-art menus, pick a
study topic, and sharpen your vocabulary through bite-sized minigames — listening
challenges, word puzzles, matching games and reading comprehension — all without
ever leaving your terminal.

> Built as a collaborative project to explore game design, terminal UX and
> text-to-speech entirely in Swift.

---

## 🖥️ Screens

<div align="center">

| Home | Main Menu | Language Select |
|:---:|:---:|:---:|
| <img src="docs/screens/home.png" width="260"/> | <img src="docs/screens/menu.png" width="260"/> | <img src="docs/screens/languages.png" width="260"/> |

| Exercise Type | Study Menu | Dictionary |
|:---:|:---:|:---:|
| <img src="docs/screens/exercise-type.png" width="260"/> | <img src="docs/screens/study.png" width="260"/> | <img src="docs/screens/dictionary.png" width="260"/> |

</div>

---

## 🚀 Features

<div align="center">

|  Feature  | Description |
|:---------:|:------------|
| 🎮 Engaging minigames | Interactive challenges that make vocabulary stick |
| 🔊 Audio translation | Listen to a word or phrase and type the translation (text-to-speech) |
| 🧩 Hidden word puzzles | Guess the missing word inside a sentence |
| 📖 Reading comprehension | Read short passages and answer questions |
| 📚 Interactive dictionary | Look up and review every word you've learned |
| 🏆 Progress & rewards | Earn rewards as you advance through quests |
| 🎨 ASCII-art interface | Polished, hand-crafted terminal screens |

</div>

---

## 🧠 Exercises & Study Modes

<div align="center">

| Mode | What you do |
|:------:|:---------|
| 🗣️ **Terminal Falante** | The terminal *speaks* a word; you listen and translate |
| 🔗 **Ligue-Ligue** | Match words with their correct translation |
| 🔤 **Palavreco** | Word-guessing puzzle to test your vocabulary |
| 📚 **Dicionário** | Review all the words you have learned so far |

**Reading topics** (story-driven comprehension):
`🌍 Viagem pelo Mundo` · `🛒 Compras no Mercado` · `🌅 Rotina Diária`

</div>

---

## 🔀 User Flow

<div align="center">
<img src="UserFlow/UserFlow.png" width="90%" alt="FluentQuest user flow"/>
</div>

---

## 📂 Project Structure

<div align="center">

| Module | Purpose |
|:-----:|:--------|
| `main.swift` | Entry point & main game loop (home navigation, SIGINT handling) |
| `Menu/` | Menus & navigation: language select, study topics, exercise and game-mode pickers, dictionary |
| `Exercícios/` | Core exercises: Palavreco, LigueLigue, TerminalFalante |
| `Historia/` | Reading-comprehension stories: ViagemMundo, RotinaDiaria, ComprasMercado |
| `PrintDosExs/` | ASCII-art rendering for each exercise |
| `Utils/` | Helpers: input validation, text-to-speech, terminal clearing, questions |

</div>

---

## 📦 Dependencies

```bash
Swift: >= 5.5
Xcode: >= 14 (command-line tool target)
```

---

## 🎯 Getting Started

```bash
# Clone the repository
git clone https://github.com/EnzoFerroni/FluentQuest.git

# Open the Xcode project
cd FluentQuest
open FluentQuest/FluentQuest.xcodeproj

# Build & run the command-line game in Xcode with ⌘R
```

> 💡 Best played in a terminal with a monospaced font and a dark background, so
> the ASCII-art screens line up perfectly.

---

## 👥 Team

<div align="center">
  <table>
    <tr>
      <td align="center" width="33%">
        <a href="https://github.com/EnzoFerroni" target="_blank"><img src="https://github.com/EnzoFerroni.png" width="100" alt="Enzo Ferroni"/></a>
        <br/><sub><b>Enzo Ferroni</b></sub><br/><br/>
        <a href="https://github.com/EnzoFerroni" target="_blank"><img src="https://skillicons.dev/icons?i=github" alt="GitHub"/></a>
        <a href="https://www.linkedin.com/in/enzoferroni/" target="_blank"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/></a>
      </td>
      <td align="center" width="33%">
        <a href="https://github.com/Kleber-gadelha" target="_blank"><img src="https://github.com/Kleber-gadelha.png" width="100" alt="Kleber Gadelha"/></a>
        <br/><sub><b>Kleber Gadelha</b></sub><br/><br/>
        <a href="https://github.com/Kleber-gadelha" target="_blank"><img src="https://skillicons.dev/icons?i=github" alt="GitHub"/></a>
        <a href="https://www.linkedin.com/in/kleber-gadelha-917a6228b/" target="_blank"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/></a>
      </td>
      <td align="center" width="33%">
        <a href="https://github.com/matheussricardoo" target="_blank"><img src="https://github.com/matheussricardoo.png" width="100" alt="Matheus Ricardo"/></a>
        <br/><sub><b>Matheus Ricardo</b></sub><br/><br/>
        <a href="https://github.com/matheussricardoo" target="_blank"><img src="https://skillicons.dev/icons?i=github" alt="GitHub"/></a>
        <a href="https://www.linkedin.com/in/matheus-ricardo-426452266/" target="_blank"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/></a>
      </td>
    </tr>
  </table>
</div>

---

## 📄 License

Released under the [MIT License](LICENSE). © 2025 Enzo Ferroni, Kleber Gadelha and Matheus Ricardo.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=4682B4&height=120&section=footer"/>

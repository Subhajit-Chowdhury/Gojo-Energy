# Gojo Energy - Cursed Technique Visualizer

A cursed technique visualizer based on **Jujutsu Kaisen** (呪術廻戦). Combines MediaPipe hand tracking with Three.js particles to recreate iconic cursed techniques from the anime.

## Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Subhajit-Chowdhury/Gojo-Energy.git
   cd Gojo-Energy
   ```

2. **Run the project:**
   - **VS Code:** Install "Live Server" extension → Right-click `index.html` → "Open with Live Server"
   - **Python:** Run `python -m http.server 8000` → Open `http://localhost:8000`

3. **Open in browser** and allow webcam access to start using hand gestures!

**🌐 Live Demo:** [https://gojo-energy.netlify.app/](https://gojo-energy.netlify.app/){:target="_blank"}

![Demo](https://github.com/user-attachments/assets/8ad2b871-02c0-4b97-95f3-34682e745be0)

---

## ✨ Features

### Hand Gesture Controls

| Technique | Gesture | Visual Description |
|-----------|---------|---------------------|
| **Hollow Purple** | 🤏 Pinch | Chaotic singularity with attraction & repulsion |
| **Infinite Void** | ✌️ Cross | Multi-layered celestial domain with bright event horizon ring |
| **Cursed Technique Reversal: Red** | ☝️ Index Up | Blinding white-hot core with violent repulsive sphere |
| **Malevolent Shrine** | 🤲 Flat Hand | Dark ominous aura - The King of Curses |

### Gesture Reference

```
┌─────────────────────────────────────────────────────────────────┐
│                    HAND GESTURE GUIDE                           │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  PURPLE (Pinch)              VOID (Cross)                       │
│  ┌──────┐                    ┌──────┐                          │
│  │ 👌   │  ← Thumb touches   │ ✌️   │  ← Index & Middle        │
│  └──────┘    Index finger      └──────┘    fingers crossed      │
│                                                                 │
│  RED (Index Up)              SHRINE (Flat Hand)                 │
│  ┌──────┐                    ┌──────┐                          │
│  │ ☝️   │  ← Index finger    │ 🖐️   │  ← All fingers flat      │
│  └──────┘    pointing up       └──────┘    (prayer position)   │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Edge, Firefox recommended)
- Webcam required for hand tracking

### Installation

```bash
git clone https://github.com/Subhajit-Chowdhury/Gojo-Energy.git
cd Gojo-Energy
```

### Run the Project

**Using VS Code:**
1. Install "Live Server" extension
2. Right-click `index.html` → "Open with Live Server"

**Using Python:**
```bash
python -m http.server 8000
# Open http://localhost:8000 in browser
```

---

## 🔧 Technical Details

- **Three.js** - 3D particle rendering with bloom post-processing
- **MediaPipe** - Real-time hand landmark detection
- **20,000 Particles** - Volume-based cursed technique visualization

---

## 📝 License

This project is for educational and entertainment purposes. Jujutsu Kaisen content belongs to Gege Akutami and Shueisha.

---

*Built with ❤️ by Subhajit Chowdhury*
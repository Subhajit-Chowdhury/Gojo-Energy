# Gojo Energy - Cursed Technique Visualizer

A cursed technique visualizer based on **Jujutsu Kaisen** (呪術廻戦). It uses MediaPipe hand tracking with Three.js particles to recreate iconic cursed techniques from the anime.

**🌐 Live Demo:** [https://gojo-energy.netlify.app/](https://gojo-energy.netlify.app/){:target="_blank"}

![Demo](https://github.com/user-attachments/assets/8ad2b871-02c0-4b97-95f3-34682e745be0)

---

## Step-by-Step Setup Guide

### Step 1: Clone the Repository

```bash
git clone https://github.com/Subhajit-Chowdhury/Gojo-Energy.git
cd Gojo-Energy
```

### Step 2: Run the Project

Choose one of the following methods:

**Option A - VS Code:**
1. Install the "Live Server" extension
2. Right-click `index.html`
3. Select "Open with Live Server"

**Option B - Python:**
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

### Step 3: Allow Camera Access

Open the project in your browser and allow webcam access when prompted. You are now ready to use hand gestures to trigger cursed techniques!

---

## Hand Gesture Controls

| Technique | Gesture | Description |
|-----------|---------|-------------|
| **Hollow Purple** | 🤏 Pinch | Chaotic singularity with attraction and repulsion |
| **Infinite Void** | ✌️ Cross | Multi-layered celestial domain with bright event horizon ring |
| **Cursed Technique Reversal: Red** | ☝️ Index Up | Blinding white-hot core with violent repulsive sphere |
| **Malevolent Shrine** | 🤲 Flat Hand | Dark ominous aura - The King of Curses |

### Gesture Reference Guide

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

## Requirements

- A modern web browser (Chrome, Edge, or Firefox recommended)
- A webcam for hand tracking

---

## Technical Details

- **Three.js** - 3D particle rendering with bloom post-processing
- **MediaPipe** - Real-time hand landmark detection
- **20,000 Particles** - Volume-based cursed technique visualization

---

## License

This project is for educational and entertainment purposes. Jujutsu Kaisen content belongs to Gege Akutami and Shueisha.

---

*Built with ❤️ by Subhajit Chowdhury*
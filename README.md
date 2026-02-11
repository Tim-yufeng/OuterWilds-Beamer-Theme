# Outer Wilds Beamer Theme | Nomai Archival Edition

> "The Universe is, and we are."

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![LaTeX](https://img.shields.io/badge/language-LaTeX-red.svg) ![Outer Wilds](https://img.shields.io/badge/tribute-Outer%20Wilds-orange)

An elegant, academic, and immersive LaTeX Beamer theme inspired by the video game **Outer Wilds**. 

Unlike typical gaming themes that clutter slides with heavy artwork, this theme adopts the **Nomai Archival Aesthetic**: minimalist, geometric, and strictly organized. It is designed for researchers, students, and explorers who want to present their findings with the clarity of a Nomai scroll and the beauty of the Eye.

---

## 🌌 Visual Features

### 1. The "Observer" Title Page
Features a **floating HUD-style framing** reminiscent of the Signalscope or Nomai shuttle interfaces, with a deep space background.

### 2. Cinematic Transition Pages
Each `\section{...}` command automatically triggers a **decentralized, cinematic transition slide** featuring:
- A massive, semi-transparent section number watermark.
- A glowing "Eye of the Universe" ambient background.
- A dynamic progress bar indicating the journey's completion.

### 3. "Time Loop" Progress Indicators
- **Title Bar**: A subtle, circular progress ring in the top-left corner that fills up as you advance.
- **Section Page**: A linear timeline bar showing the current section relative to the total expedition.

### 4. Academic-Ready Content Slides
- **Clean Background**: A very faint, slowly rotating **Hourglass Twins** watermark (opacity 0.04) that adds depth without affecting text readability.
- **Nomai Geometry**: Custom TikZ-drawn **Hexagons** and **Diamonds** for itemize lists.
- **Minimalist Blocks**: Transparent-feel content blocks defined by bold Nomai-blue accent lines.

### 5. "Signal Lost" Ending
A custom `\thankframe` command that mimics the end of a transmission or the loop reset, featuring quantum fluctuation lines.

---

## 🛠️ Installation & Usage

### Prerequisites
- **XeLaTeX** compiler (Recommended for best font and TikZ performance).
- Standard LaTeX packages: `tikz`, `xcolor`, `graphicx`, `totcount`.

### Directory Structure
Ensure your project folder looks like this:

```text
.
├── main.tex                    # Your presentation file
├── beamerthemeOuterWilds.sty   # Layout & Geometry definitions
├── beamercolorthemeOuterWilds.sty # Color palette definitions
└── figures/                    # Required assets folder
    ├── hourglass.png           # Rotated background for content pages
    ├── eye.png                # Eye of the Universe (for transitions)
    ├── nomai_words.png       # Nomai script watermarks
    └── timber_hearth.png          # Thankframe background
```

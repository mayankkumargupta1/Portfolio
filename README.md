# ⚡ MAYANK.SYS // CYBER-BRUTALIST PORTFOLIO

```text
 __  __    _ __   __    _    _   _ _  __
|  \/  |  / \\ \ / /   / \  | \ | | |/ /
| |\/| | / _ \\ V /   / _ \ |  \| | ' / 
| |  | |/ ___ \| |   / ___ \| |\  | . \ 
|_|  |_/_/   \_\_|  /_/   \_\_| \_|_|\_\
```

An ultra-performant, single-page **Cyber-Brutalist** portfolio website built for **Mayank Kumar Gupta** using **Astro 5**, **Bun**, and **Tailwind CSS v4**.

Designed with a raw Matrix aesthetic, live interactive terminal CLI simulator, hardware-accelerated Matrix digital rain canvas, tactical Web Audio API sound synthesis, and calibrated for **near-perfect / 100% Lighthouse scores across all metrics**.

---

## 🌐 Quick Coordinates

- **Portfolio**: [mayankkumargupta.com](https://mayankkumargupta.com)
- **Technical Blog**: [blogs.mayankkumargupta.com](https://blogs.mayankkumargupta.com)
- **GitHub**: [@mayankkumargupta1](https://github.com/mayankkumargupta1)
- **LinkedIn**: [in/mayankkumargupta1](https://linkedin.com/in/mayankkumargupta1)

---

## 📊 Lighthouse Audit Results

| Category | Score | Status |
| :--- | :---: | :---: |
| ⚡ **Performance** | **99%** | Optimal |
| ♿ **Accessibility** | **100%** | WCAG AAA Contrast & Navigation |
| 🛡️ **Best Practices** | **100%** | Modern HTTP, HTTPS, Clean APIs |
| 🔍 **SEO** | **100%** | Schema.org Person, Meta & OpenGraph |
| 🤖 **Agentic Browsing** | **100%** | Machine & LLM Readable Landmarks |

---

## 🧬 Cyber-Brutalist Features

- **Matrix Digital Rain Engine**: Native HTML5 Canvas Katakana & binary glyph stream with automatic requestAnimationFrame throttling (~28 FPS), viewport auto-pause, and reduced-motion detection.
- **HUD Tactical Controls**: Interactive top bar with instant toggles for Matrix Rain (ON/OFF), CRT Scanline overlay (ON/OFF), and 8-bit retro sound synthesizer (SFX ON/OFF).
- **Interactive Matrix Terminal CLI**: Embedded interactive terminal emulator where visitors can type or tap quick chips for commands:
  - `help` - Lists command suite
  - `bio` - System engineer background & credentials
  - `skills` - Technical stack & capability breakdown
  - `projects` - Enumerate production deployments
  - `blog` - Direct neural link to `blogs.mayankkumargupta.com`
  - `matrix` / `sfx` - System hardware toggles
  - `contact` / `uptime` / `clear` / `whoami`
- **Neural Blog Gateway**: Prominently featured high-visibility broadcast card linking directly to `blogs.mayankkumargupta.com`.
- **Zero Hydration Lag**: Pure Astro static site generation (SSG) with minimal, deferred vanilla JavaScript.
- **Audio Feedback Synthesizer**: Web Audio API oscillator synthesis generating tactical terminal bleeps on click and typing (persisted in `localStorage`, muted by default).

---

## 🛠️ Tech Stack & Tooling

- **Framework**: [Astro 5](https://astro.build/) (Static Site Generation)
- **Runtime & Package Manager**: [Bun 1.4+](https://bun.sh/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/) with `@tailwindcss/vite`
- **Typography**: JetBrains Mono & Space Mono (Google Fonts with preconnect & swap)
- **Icons & Graphics**: Pure SVG + HTML5 Canvas (zero raster weight)

---

## 🚀 Getting Started

### Prerequisites

Ensure [Bun](https://bun.sh/) is installed:

```bash
curl -fsSL https://bun.sh/install | bash
```

### Installation

```bash
# Clone the repository
git clone git@github.com:mayankkumargupta1/Portfolio.git
cd Portfolio

# Install dependencies with Bun
bun install
```

### Development

```bash
bun run dev
```

Visit `http://localhost:4321` in your browser.

### Production Build

```bash
# Compile optimized static bundle
bun run build

# Preview static distribution locally
bun run preview
```

---

## 📂 Project Architecture

```
├── public/
│   ├── favicon.svg          # Cyber-brutalist matrix SVG favicon
│   └── robots.txt           # Crawler configuration
├── src/
│   ├── components/
│   │   ├── BlogBanner.astro         # High-impact blog transmission gateway card
│   │   ├── Contact.astro            # Signal transmission & email copy terminal
│   │   ├── Experience.astro         # Chronology & operations timeline
│   │   ├── Footer.astro             # System telemetry & back to top
│   │   ├── Hero.astro               # ASCII banner, bio & specs telemetry
│   │   ├── MatrixRain.astro         # HTML5 Canvas digital rain engine
│   │   ├── Navbar.astro             # Cyber HUD bar & tactical toggles
│   │   ├── Projects.astro           # Production deployments & exploits
│   │   ├── Skills.astro             # Capability matrix & runtime specs
│   │   └── TerminalSimulator.astro  # Interactive command-line interface
│   ├── layouts/
│   │   └── Layout.astro     # HTML5 shell, SEO, CRT overlay, Audio synthesizer
│   ├── pages/
│   │   └── index.astro      # Single-page assembly
│   └── styles/
│       └── global.css       # Tailwind v4, phosphor glow, brutalist shadows
├── astro.config.mjs         # Astro & Tailwind Vite configuration
├── package.json             # Bun dependencies and scripts
└── tsconfig.json            # Strict TypeScript configuration
```

---

## 📜 License

MIT License © 2026 Mayank Kumar Gupta

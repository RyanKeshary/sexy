<div align="center">
  <img src="assets/logo.jpg" alt="Sexy Logo" width="160" style="border-radius: 28px; box-shadow: 0 24px 48px -12px rgba(0,0,0,0.35);" />

  # sexy

  **The unified design intelligence skill for AI agents that refuses to look AI-generated.**

  *Orchestrating 6 world-class design frameworks into a single seamless, high-craft creative pipeline.*

  [![Antigravity Plugin](https://img.shields.io/badge/Antigravity-Plugin-black?style=flat-square&logo=google)](https://antigravity.google)
  [![Skills Count](https://img.shields.io/badge/skills-13%20bundled-blueviolet?style=flat-square)](#skills-suite)
  [![Agent Portability](https://img.shields.io/badge/agents-Antigravity%20%7C%20Claude%20Code%20%7C%20Cursor%20%7C%20Codex-3b82f6?style=flat-square)](#quick-install)
  [![License](https://img.shields.io/badge/licence-MIT-emerald?style=flat-square)](LICENSE)

</div>

---

Most AI website and frontend output fails in one of two directions:
1. **The generic template**: Well-behaved, sterile, and forgettable. Floating 1px borders, random purple/cyan gradients on every card, tracked-capital badges, and an email newsletter form tacked onto the bottom of every page.
2. **The broken flash**: A flashy scroll animation with unreadable 2.1:1 low-contrast body text, headlines that wrap to 6 lines on a phone, and zero responsive testing.

**sexy** is built to fail neither way. It treats **interaction, aesthetic soul, and production craft as one discipline**. 

Instead of dumping conflicting instructions into your prompt, **sexy** unifies 6 powerhouse design engines into an orchestrated 5-stage synthesis where each engine owns the exact phase it was engineered for.

---

## ✦ The 5-Stage Collective Pipeline

When you call `/sexy` or ask your assistant to design or polish a screen, the engines curate together without conflict:

```
┌────────────────────────────────────────────────────────────────────────┐
│  Stage 1: Foundation & Design DNA                                      │
│  ► awesome-design-md + ui-ux-pro-max                                  │
│  Pulls proven tokens, typography ladders, and surface hierarchies      │
│  (Apple, Linear, Stripe, Vercel) instead of guessing random hex codes. │
└───────────────────────────────────┬────────────────────────────────────┘
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│  Stage 2: Creative Direction & Anti-AI Filter                          │
│  ► hallmark                                                            │
│  Strips AI slop: no decorative purple blobs, no meaningless icons.     │
│  Injects intentional editorial tension, human hierarchy & personality. │
└───────────────────────────────────┬────────────────────────────────────┘
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│  Stage 3: Spatial Architecture & Motion Journey                        │
│  ► scroll-craft                                                        │
│  Orchestrates independent depth planes (background, midground, hero),  │
│  scroll kinetics, and entrance states with reduced-motion care.        │
└───────────────────────────────────┬────────────────────────────────────┘
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│  Stage 4: Micro-Interactions & Sensory Details                         │
│  ► make-interfaces-feel-better                                         │
│  Applies concentric border radii (R_inner = R_outer - padding),        │
│  tabular numerals, text-wrap balance, button active scales & springs.  │
└───────────────────────────────────┬────────────────────────────────────┘
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│  Stage 5: Design Director Audit & Craft Floor                          │
│  ► impeccable                                                          │
│  Holds an uncompromising craft floor: checks mobile wraps, empty       │
│  states, loading skeletons, truncation, and accessibility standards.   │
└────────────────────────────────────────────────────────────────────────┘
```

---

## ✦ What the 6 Engines Bring

| Engine | Origin | What It Brings to Your UI |
| :--- | :--- | :--- |
| **`awesome-design-md`** | VoltAgent | **80+ Brand Design Specs:** Production-grade `DESIGN.md` specs from Apple, Stripe, Linear, Figma, Vercel, Airbnb, and more. |
| **`ui-ux-pro-max`** | NextLevelBuilder | **System Architecture:** 3-layer design tokens (primitive → semantic → component), palette reasoning, and multi-stack UI guidelines. |
| **`hallmark`** | Nutlope | **Anti-AI Aesthetic Filter:** Rejects the tells that read as machine-generated; builds the page around what the visitor came to do. |
| **`scroll-craft`** | Nate Herk | **Spatial Depth & Motion:** Dimensional heroes, independent visual layers, smooth scroll transitions, and mobile art direction. |
| **`make-interfaces-feel-better`** | Jakub Krehel | **Design Engineering Polish:** Concentric radii, subpixel font smoothing, hit area ergonomics, and snappy spring curves (150–250ms). |
| **`impeccable`** | Paul Bakaus | **Design Director Review:** Non-negotiable quality floor, zero-compromise finish, and rigorous verification across viewports. |

---

## ✦ Bundled Skills Suite

The plugin ships **13 modular skills** loaded progressively on demand:

```
skills/
├── sexy/                        # Master 5-stage orchestrator (/sexy)
├── design-md/                   # 80+ real-world DESIGN.md references
├── hallmark/                    # Anti-AI creative direction & theme catalog
├── scroll-craft/                # Scroll-driven kinetics & layered heroes
├── make-interfaces-feel-better/ # Micro-interaction physics & surface polish
├── impeccable/                  # Design director audit & craft-floor rules
├── ui-ux-pro-max/               # UI/UX intelligence across web & mobile
├── design/                      # Component generation & design patterns
├── design-system/               # 3-layer token management
├── ui-styling/                  # Tailwind, CSS primitives & layout tokens
├── brand/                       # Visual identity, voice & asset guidelines
├── banner-design/               # Social banners, OG cards & hero graphics
└── slides/                      # Pitch decks & presentation layouts
```

---

## ✦ Quick Install

### In Antigravity CLI (`agy`)

Install globally in one command:
```bash
agy plugin install https://github.com/RyanKeshary/sexy.git
```

Or clone into your local plugin registry:
```bash
git clone https://github.com/RyanKeshary/sexy.git ~/.gemini/config/plugins/sexy
agy plugin enable sexy
```

### In Claude Code, Cursor, Codex, or OpenCode

Clone or link the skills folder into your agent's customization directory:
```bash
# Workspace level
cp -r skills/* .agents/skills/

# Or global Claude Code / Codex
cp -r skills/* ~/.claude/skills/
```

---

## ✦ Usage

Just prompt your assistant with `/sexy` or ask for high-craft UI. The agent automatically runs through the 5 stages:

```text
/sexy build a landing page for an autonomous robotics studio
```

```text
/sexy overhaul our dashboard settings to make it feel tactile, responsive, and distinct
```

```text
Make this modal feel sexy: concentric radii, spring physics, and linear-style dark surfaces
```

---

## ✦ License & Credits

Released under the [MIT License](LICENSE) © [Ryan Keshary](https://github.com/RyanKeshary).

Built on top of groundbreaking work by the community:
- [awesome-design-md](https://github.com/VoltAgent/awesome-design-md) by **VoltAgent**
- [hallmark](https://github.com/Nutlope/hallmark) by **Nutlope (Together AI)**
- [scroll-craft](https://github.com/nateherkai/scroll-craft) by **Nate Herk**
- [make-interfaces-feel-better](https://github.com/jakubkrehel/make-interfaces-feel-better) by **Jakub Krehel**
- [impeccable](https://github.com/pbakaus/impeccable) by **Paul Bakaus**
- [ui-ux-pro-max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) by **NextLevelBuilder**

# Colosseum — Secure360 2026

**Talk:** *Colosseum: An Agent Control Plane for the Post-LLM Era*
**Conference:** Secure360 2026 · May 13–14, 2026 · Mystic Lake Event Center, Prior Lake, MN
**Speaker:** Abhi Devireddy, Director of Technology Services · Essentia Health

---

## 🎯 Talk Abstract

The agent wave is already here — but most security teams are judging threats they have never produced and defending systems they do not fully understand. This talk introduces **Colosseum**, an open-source AI agent control plane built around the principle that *you cannot secure what you cannot observe*.

We walk through:
- Why agents are fundamentally different from traditional automation
- The three failure modes that keep recurring in real-world deployments
- How an operator control plane (identity, least-privilege tooling, policy gates, sandboxed environments, and forensic replay) closes the calibration gap
- A live demo of Colosseum in action

---

## 📊 Slide Deck

26 slides · Reveal.js · [View live](https://s360-26.apps.0x509.com)

### Outline

| Act | Slides | Theme |
|-----|--------|-------|
| **Act 1 — The Problem** | 1–8 | The agent wave, why it breaks existing security models, and where defenders are falling behind |
| **Act 2 — Colosseum** | 9–18 | Architecture, agent profiles, tool allowlists, credential vaults, Docker sandboxes, policy/approvals, output contracts, planning mode, replay and forensics |
| **Act 3 — So What** | 19–26 | Confident deployment, incident response rebuilt for agents, platform leverage, open-source model, what is next |

### Keyboard Navigation

| Key | Action |
|-----|--------|
| `Space` or `→` | Next slide |
| `←` | Previous slide |
| `F` | Fullscreen |
| `S` | Speaker notes |
| `O` | Slide overview |
| `Esc` | Exit fullscreen/overview |

---

## 🗂 Repo Structure

```
s360-2026/
├── index.html          # Main presentation (26 slides, self-contained)
├── css/
│   └── theme.css       # Colosseum brand overrides on top of Reveal.js black theme
├── js/
│   └── config.js       # Reveal.js init + plugin config
├── assets/
│   ├── architecture.svg   # System architecture diagram
│   ├── threat-model.svg   # Agent threat model diagram
│   └── logo.png / logo.svg
└── README.md
```

Reveal.js is loaded from CDN — no npm install needed to view locally.

---

## 🚀 Running Locally

```bash
git clone https://github.com/abhid/s360-2026.git
cd s360-2026
python3 -m http.server 8080
```

Open http://localhost:8080

---

## 🔗 Links

- **Live slides:** https://s360-26.apps.0x509.com
- **Colosseum source:** https://github.com/abhid/colosseum-go
- **Secure360:** https://secure360.org

---

## 📄 License

Slide content © 2026 Abhi Devireddy. Reveal.js is MIT licensed.

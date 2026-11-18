# Prashant Intelligence — Portfolio

A runnable front-end portfolio prototype following the approved design direction: OLED-black cybersecurity/AI styling, animated mint loading intro, typing hero and macOS terminal, four expandable skill cards, nine tightly overlapping 3D project cards, six overlapping diamond achievement slots, tracking-style rotating Earth with social icons, a particle-dissolve contact transition, and a full-screen amber/golden particle MONDAY AI interface.

## Run

Open `index.html` in a browser, or from this folder run:

```bash
py -3.11 -m http.server 5500
```

Then open http://localhost:5500 . No Node.js, npm or dependencies required. Google Fonts is optional; the browser falls back to Arial if offline.

## Customize before publishing

1. In `script.js`, fill the `CONFIG` links with your real social accounts, email, resume and contact URLs.
2. Replace project placeholder descriptions, dashboard mockups and demo buttons with your own **actual** screenshots, tested features and repository/demo URLs. The last two projects are intentionally unnamed placeholders.
3. Replace the six achievement placeholders with earned certificates, CTFs, hackathons and other verifiable evidence. Do not claim unearned credentials.
4. The MONDAY assistant is a **local keyword-response demo**, not a real LLM. To implement actual AI, connect a secured server-side backend; never put API keys in browser JavaScript. Speech recognition depends on browser support and microphone permission.
5. The dust effect is a stylized particle dissolve, not a literal replication of any copyrighted film sequence.

## Files

- `index.html` — semantic page layout
- `styles.css` — design, hover effects and responsive layouts
- `script.js` — content, interaction, canvas Earth and MONDAY particles

## Accessibility / performance

Includes keyboard-accessible project and achievement selectors, semantic controls, responsive layout and reduced-motion preference support. The particle canvas can be further optimized for low-power devices.

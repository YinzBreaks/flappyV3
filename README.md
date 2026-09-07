# 🎮 Flappy 2026: The Satirical Flying Odyssey

A fast-paced, satirical arcade browser game built with pure vanilla HTML5 Canvas, Web Audio API, and CSS. 100% dependency-free, mobile-optimized, and ready to deploy with zero configuration.

![Flappy 2026 Preview](assets/portly_jd.png)

---

## 🦅 Playable Characters

- **Portly JD Vance**: Dodges plush velvet recliners and collects Mountain Dew cans. Gains invulnerability from the *"Love, Erika K."* shield note.
- **Bobby Kennedy Jr. & Brain Worm**: Biohacks power racks and pharmaceutical syringes. Catches autism from Extra-Strength Tylenol bottles to trigger **AUTISM SMASH** immunity.
- **Diaper Don**: Takes to the skies in his golden diaper, collecting gold bars and smashing obstacles with the **FRESH PAMPERS SHIELD**.

---

## ✨ Features

- **Zero-Dependency Vanilla Architecture**: Ultra-lightweight (~2.8 MB total assets) for instant page loads.
- **Dedicated Pixel Sprites**: Calibrated sub-pixel frame bounds eliminating visual artifacts and sprite clipping.
- **Dynamic Cartoon Showcase Gallery**: Interactive inspectable gallery featuring character lore, powerup tags, and dynamic stats.
- **Synthesized Retro Web Audio**: Dynamic 8-bit jump sound effects, powerup jingles, and satisfying ground-thud collision SFX synthesized in real-time via Web Audio API (no external MP3/WAV assets needed).
- **Viral Social Sharing**: Native mobile Web Share API (`navigator.share`) with character-specific viral brag copy and Twitter/X fallback.
- **Mobile First & Responsive**: Touch action manipulation, orientation adaptation, and seamless viewport scaling.
- **Strict Security & CSP Compliance**: Clean domain allowlists for Cloudflare Pages, Vercel, and local development.

---

## 🚀 Instant Deployment

### Cloudflare Pages
1. Push this repository to GitHub.
2. Log into the Cloudflare Dashboard -> **Workers & Pages** -> **Create application** -> **Pages**.
3. Connect your `YinzBreaks/flappyV3` repository.
4. Set Build command to empty and Output directory to `.`.
5. Deploy!

### Vercel
1. Import `YinzBreaks/flappyV3` on [Vercel](https://vercel.com).
2. Framework Preset: **Other**.
3. Deploy!

### Local Development
Open `index.html` directly in any modern browser, or run a lightweight local server:
```bash
npx serve .
# or
python -m http.server 8080
```
*(Tip: Add `?dev=1` to the URL for offline development).*

---

## 📜 License
MIT License. Created for satirical and entertainment purposes.

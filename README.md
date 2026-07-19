# 🚀 Starhop

A fast, juicy **one-tap browser arcade game**. Fly your little rocket through the neon gates for as long as you can. Runs on any phone or computer — no install, no app store, just a web page.

**Controls:** Tap the screen (mobile) or press **Space / ↑ / W** (desktop). That's the whole game.

## ▶️ Play it

**Right now, no setup:** download `index.html` and open it in any browser (double-click it). On your iPhone you can open it in Safari too.

**As a shareable link (GitHub Pages — free):**
1. Push this project to a GitHub repo.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**, pick your branch and the `/root` (or `/starhop-game`) folder, and Save.
4. Wait ~1 minute — GitHub gives you a public URL like `https://<your-username>.github.io/<repo>/`. Open that on your iPhone and add it to your Home Screen for a full-screen, app-like experience.

> Tip: on iPhone Safari, tap the **Share** button → **Add to Home Screen**. Starhop then launches full-screen like a real app.

## ✨ What's inside

- Single self-contained `index.html` — no build step, no dependencies.
- Responsive full-screen canvas (retina-aware), works portrait on phones.
- Touch + keyboard/mouse controls.
- Sound effects generated in-browser (WebAudio) — no audio files needed.
- Particle bursts, thruster flame, parallax starfield, and screen shake for "juice".
- High score saved locally (`localStorage`).

## 🛠️ Tweak it

Open `index.html` and look at the **Game constants** block near the top:

| Constant | What it does |
|---|---|
| `GRAVITY` | How hard the rocket falls |
| `FLAP` | Hop strength (more negative = bigger hop) |
| `GATE_GAP` | How big the opening is (bigger = easier) |
| `GATE_SPACING` | Distance between gates |
| `SPEED` | How fast the world scrolls |

Change a number, save, refresh. That's the fastest way to start learning game feel.

## 📱 Turning this into a real App Store app later

This game can be wrapped into a native iOS app with a tool like [Capacitor](https://capacitorjs.com/) — but that step needs a **Mac with Xcode** and an Apple Developer account ($99/yr). The browser version above is the recommended starting point; wrap it once you're happy with the game.

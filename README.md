# 🥁 Dilla Beat Lab

An interactive, open-source lesson in **J Dilla's** drum-programming feel — with an always-on **MPC-style pad grid** that stays beside every lesson.

Created by **@tonyInteractive** of **@park8.io**

No samples, no dependencies, no build step. It's a single `index.html` that synthesizes every drum in your browser with the Web Audio API.

**[▶ Live demo](#)** · MIT licensed · runs offline

---

## What's inside

Six lessons, each its own tab, all sharing the same live beat machine and pad grid:

1. **Grid vs Feel** — quantize on vs off, the core idea
2. **Drunk Drums** — micro-timing: nudging a hit a few ms off the grid
3. **Loose Hi-Hats** — swing + humanize, ghost hats
4. **Ghost Notes & Velocity** — the quiet hits that make it human
5. **Dilla Swing vs MPC Swing** — uniform machine swing vs hand-placed feel
6. **Build-a-Beat** — free play: program the grid, finger-drum the pads, record

**Always-on MPC pads** (16, playable with `1 2 3 4 / Q W E R / A S D F / Z X C V`), a shared 6-track step sequencer with per-row micro-timing sliders, tempo / swing / humanize / quantize / vinyl-dust controls, and a live playhead.

## Run it locally

It's static — just open the file:

```bash
open index.html            # macOS
# or serve it:
npx serve .                # then visit the printed URL
python3 -m http.server     # then http://localhost:8000
```

## Deploy to Vercel (public)

**Easiest — drag & drop:** go to [vercel.com/new](https://vercel.com/new) → drop this folder → **Deploy**. Done.

**From GitHub (one click):** push this folder to a public GitHub repo, then use the button below (replace the URL with your repo):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USER/dilla-beat-lab)

**From the CLI:**

```bash
npm i -g vercel
vercel --prod
```

## License

MIT — do anything, keep the notice. See [LICENSE](LICENSE).

Made with love for the feel. RIP James Dewitt Yancey (1974–2006).

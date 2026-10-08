# GIN AI Research Lab — Official Portal (`gin.info.vn`)

Official open-source research and engineering portal for **GIN AI Research** ([gin.info.vn](https://gin.info.vn)).

## Portfolio Overview

1. **[AI Live Sensei Classroom](https://github.com/trituenguyen97/ai-live-sensei-classroom)** — Autonomous Full-Duplex Multimodal Tutoring Classroom (Kana → N1).
2. **[Bit-Translate](https://github.com/trituenguyen97/Bit-Translate)** — Extreme Edge AI: 1.58-Bit Ternary Neural Machine Translation at ~350 tok/s on CPU in 77.56 MB.
3. **[KS-Dashboard](https://github.com/trituenguyen97/KS-Dashboard)** — Enterprise AI FinOps, Prompt Caching ROI & Observability for Claude Code.
4. **[TransX](https://github.com/trituenguyen97/TransX)** — 100% Offline Sovereign Edge Speech Translation & Subtitle Overlay.
5. **[GinBaby](https://github.com/trituenguyen97/ginbaby)** — Evidence-informed, Offline-First Maternal & Pediatric Companion (Flutter 3.47 PWA).

---

## 🚀 Quick Deployment to `gin.info.vn`

### Option 1: Vercel (Recommended)
1. Push this folder to GitHub: `trituenguyen97/gin-landing-page`.
2. Connect to [Vercel](https://vercel.com) → Import Git Repository.
3. In Project Settings → Domains: add `gin.info.vn` and configure DNS CNAME/A records.

### Option 2: Cloudflare Pages (Fast & Free)
1. Go to Cloudflare Dashboard → Workers & Pages → Create application → Pages.
2. Connect GitHub repository → Deploy.
3. In Custom Domains: attach `gin.info.vn`.

### Option 3: Local Preview
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

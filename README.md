# InteractX — Frontend Integration Framework

A live demo showcasing 9 third-party frontend libraries working together in one page.

**Libraries used:** Three.js · GSAP · Lottie · Particles.js · Chart.js · Typed.js · Swiper.js · AOS · Vanilla Tilt · Lenis

---

## Deploy to GitHub + Vercel (step by step)

### Step 1 — Push to GitHub

1. Go to **github.com** → click **New repository**
2. Name it `interactx-demo` → set to **Public** → click **Create repository**
3. Run these commands in your terminal (replace YOUR_USERNAME):

```bash
git remote add origin https://github.com/YOUR_USERNAME/interactx-demo.git
git branch -M main
git push -u origin main
```

### Step 2 — Deploy on Vercel

1. Go to **vercel.com** → sign in with GitHub
2. Click **Add New → Project**
3. Find `interactx-demo` in your repo list → click **Import**
4. Leave all settings as default (Vercel auto-detects static HTML)
5. Click **Deploy**

Your site goes live at: `https://interactx-demo.vercel.app`

### Step 3 — Auto-deploy on every push

After initial setup, every `git push` to `main` automatically redeploys:

```bash
git add .
git commit -m "update: new feature"
git push
```

Vercel picks it up in ~15 seconds.

---

## Local development

Just open `index.html` in any browser — no build step needed.

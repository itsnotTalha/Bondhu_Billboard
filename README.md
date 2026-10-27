# BONDHU — Animated Billboard & Showcase

Interactive, daylight-visible animated billboard and product showcase for **BONDHU (বন্ধু)** — Your Family Robot Companion.

## Features
- **Real-Time Human Tracking Video**: Integrated camera tracking demonstration synced with Scene 05.
- **Bilingual Interface**: One-click instant language toggle between Bengali (`বাং`) and English (`EN`) with speech synthesis.
- **Responsive Layout**: Zero element collisions across desktops, laptops, tablets, and mobile screens.
- **Daylight-Soothing Aesthetics**: High-contrast, soft organic palette inspired by clean healthcare modernism.

## Quick Deploy to Vercel

### Option 1: Vercel CLI (Fastest)
From this directory:
```bash
npx vercel
```
Follow the on-screen prompts (accept defaults). Your site will be live within seconds!

For production deployment:
```bash
npx vercel --prod
```

### Option 2: GitHub + Vercel Web Dashboard
1. Initialize a git repository in this folder and push to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit for Bondhu billboard"
   git branch -M main
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```
2. Go to [vercel.com/new](https://vercel.com/new) and import the repository.
3. Framework Preset: Leave as **Other**.
4. Click **Deploy**.

## Local Preview
To preview locally:
```bash
npx serve .
```
or open `index.html` directly in any modern browser.


# Sebastian Abraham — Personal Developer Portfolio

Modern, high-performance developer portfolio website for **Sebastian Abraham** (Full-Stack Developer, 2X Hackathon Winner).

Built with semantic **HTML5**, modern **CSS3** (custom responsive design system, dark-mode-first glassmorphism), and vanilla **JavaScript**. Zero heavy build steps, lightning-fast 100/100 Lighthouse performance, and ready for instant deployment to [Vercel](https://vercel.com).

---

## 🚀 Features

- **Developer Aesthetic**: Ambient aurora glows, glassmorphism cards, glowing badges, and modern typography (`Plus Jakarta Sans`, `Space Grotesk`, `JetBrains Mono`).
- **Interactive Project Filtering**: Filter projects by *All*, *🏆 Hackathon Winners*, *AI / Computer Vision*, and *Full-Stack & Go*.
- **Comprehensive Resume Showcase**:
  - **Hero**: Quick introduction, contact metadata, social links, and key stats.
  - **About & Quick Facts**: Background, strengths, and terminal-style profile card.
  - **Skills Matrix**: Categorized into Backend & APIs, Frontend & Mobile, Databases, AI/ML & Computer Vision, and DevOps/Systems.
  - **Featured Projects**: FrameWise, Savr (1st Place Eneriya), CommunityQuest (1st Place Samvidhi), NavKode, FoodShare, Stremium.
  - **Experience**: Full Stack Developer at HULT InfoTech.
  - **Education**: B.Tech in CSE at Saintgits College of Engineering ('27).
  - **Interactive Contact**: One-click email copy with instant toast alert, social links, and direct mail message form.
- **Vercel Pre-Configured**: `vercel.json` included with clean URLs and security headers.

---

## 🌐 Deploy to Vercel

### Method 1: Via Vercel Dashboard (Recommended)

1. Push this repository to your GitHub account:
   ```bash
   git add .
   git commit -m "feat: initial portfolio build ready for vercel"
   git branch -M main
   git remote add origin https://github.com/sebastian-abraham/myportfolio.git
   git push -u origin main
   ```
2. Go to [vercel.com](https://vercel.com) and log in.
3. Click **"Add New..."** > **"Project"**.
4. Select your `myportfolio` repository and click **Deploy**.
5. Vercel will automatically detect the static project and host it in seconds!

### Method 2: Via Vercel CLI

1. Install the Vercel CLI if you haven't already:
   ```bash
   npm i -g vercel
   ```
2. From the project directory, run:
   ```bash
   vercel
   ```
3. To deploy to production:
   ```bash
   vercel --prod
   ```

---

## 💻 Local Preview

You can preview the site locally using any simple HTTP server:

```bash
# Using Python 3:
python3 -m http.server 3000

# Or using Node npx:
npx serve .
```

Then visit [http://localhost:3000](http://localhost:3000) in your browser.

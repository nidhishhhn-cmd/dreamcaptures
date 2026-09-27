<div align="center">

# 📷 Dream Capture Photography & Cinema

**Capturing Emotions, Creating Timeless Memories**

A modern, luxury, mobile-first website for high-end wedding, pre-wedding, traditional, model, and baby photography & videography.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Swiper.js](https://img.shields.io/badge/Swiper-6332F6?style=for-the-badge&logo=swiper&logoColor=white)](https://swiperjs.com/)
[![Git LFS](https://img.shields.io/badge/Git_LFS-Enabled-orange?style=for-the-badge&logo=git-lfs&logoColor=white)](https://git-lfs.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-gold.svg?style=for-the-badge)](LICENSE)

</div>

---

## ✨ Features

- 🌟 **Luxury Dark Aesthetic**: Designed with deep obsidian backgrounds, gold gradient accents, and glassmorphic cards.
- 🖼️ **Interactive Portfolio Gallery**: Dynamic category filtering (Wedding, Pre-Wedding, Traditional, Baby Shoot, Model) with high-res album modals and adaptive hover/tap center previews.
- 🎬 **4K Cinematic Video Gallery**: On-demand video showcase with custom play overlays and full-screen modal player.
- 💬 **Direct WhatsApp & Social Integration**: Instant booking inquiry triggers connecting directly with clients via WhatsApp.
- 🎠 **Testimonials Slider**: Interactive carousel powered by Swiper.js with touch-swipe support and pagination.
- 📱 **Mobile & Tablet Optimized**: Responsive navigation menu, touch-aware preview interactions, and smooth animations.
- ♾️ **Infinite Instagram Marquee**: Animated photo reel linking to official social profiles.
- ⚡ **Zero Build Step Required**: Works right out of the box using pure HTML, Tailwind CSS (via CDN), and Vanilla JavaScript.

---

## 📁 Project Structure

```text
├── index.html                  # Main website landing page and application logic
├── hero.jpg                    # Hero background banner image
├── iso.png                     # Lead photographer featured portrait
├── .gitignore                  # Git ignore rules for OS, IDE, and build caches
├── .gitattributes              # Git attributes and Git LFS tracking rules
├── README.md                   # Project documentation and push guide
├── LICENSE                     # MIT open-source license
│
├── wedding/                    # Wedding gallery images (01.jpg - 13.jpeg)
├── prewedding/                 # Pre-wedding destination shoot photos
├── traditional/                # Traditional & ceremonial event photography
├── babyshoot/                  # Baby and milestone portraiture
├── beachwedding/               # Destination beach vow photography
├── model/                      # Editorial and model portfolio images
├── marquee/                    # Instagram reel showcase images
└── videos/                     # 4K Cinematic video files (*.mp4)
    ├── destination-wedding.mp4
    └── royal-palace.mp4        # High-res video (tracked via Git LFS)
```

---

## 🚀 Getting Started (Run Locally)

You can view the project locally using any of the following methods:

### Option 1: VS Code Live Server (Recommended)
1. Open the project folder in VS Code.
2. Install the **Live Server** extension (by *Ritwick Dey*).
3. Right-click [`index.html`](index.html) and select **"Open with Live Server"**.

### Option 2: Python HTTP Server
Run from inside the project directory:
```bash
# Python 3
python -m http.server 3000
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### Option 3: Node.js Serve / NPX
```bash
npx serve .
```

---

## 📤 How to Push to GitHub

Follow these steps to initialize and push this repository to GitHub:

> [!IMPORTANT]
> **Large File Notice (Git LFS)**:
> The video file `videos/royal-palace.mp4` is **~214 MB**, which exceeds GitHub's default 100 MB single-file limit.
> We have pre-configured `.gitattributes` to handle video files via **Git LFS (Large File Storage)**.

### Step 1: Open Terminal in the Project Folder
Ensure your terminal is in the folder containing [`index.html`](index.html).

### Step 2: Initialize Git & Enable Git LFS
```bash
git init
git lfs install
git lfs track "*.mp4" "*.MP4"
```

### Step 3: Stage Files & Check Status
```bash
git add .gitattributes
git add .
git status
```

### Step 4: Commit Changes
```bash
git commit -m "feat: initial commit for Dream Capture Photography website"
```

### Step 5: Link to Your GitHub Repository & Push
1. Create a new repository on [GitHub](https://github.com/new) (e.g. `dream-capture-photography`).
2. Run the commands below (replace `<YOUR-USERNAME>` and `<YOUR-REPO>`):

```bash
git branch -M main
git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO>.git
git push -u origin main
```

---

## 🌐 Deploying to GitHub Pages

To make the website live on GitHub Pages for free:

1. Push the code to GitHub following the steps above.
2. Go to your repository on GitHub → **Settings** → **Pages** (in the left sidebar).
3. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`
   - **Branch**: Select `main` and folder `/ (root)`
4. Click **Save**.
5. After 1-2 minutes, your website will be live at `https://<YOUR-USERNAME>.github.io/<YOUR-REPO>/`.

---

## 🛠️ Tech Stack & Libraries

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic structure and SEO metadata |
| **Tailwind CSS (CDN)** | Utility-first styling with custom gold/dark theme extensions |
| **Vanilla JavaScript** | Album modals, hover previews, FAQ toggles, video modals, scroll counters |
| **Lucide Icons** | Clean vector iconography |
| **Swiper.js** | Touch-friendly testimonial slider |
| **Google Fonts** | *Cormorant Garamond* (Serif headings) & *Montserrat* (Clean body text) |

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) - feel free to use and adapt it for personal and commercial projects.

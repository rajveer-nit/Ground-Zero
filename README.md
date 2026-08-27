# Rajveer Singh — Resume Site

A personal resume/portfolio site, built as a single-page static site with a
computer-vision-inspired visual theme (corner brackets, detection tags,
coordinate readouts) — a nod to the camera calibration, IR feature
extraction, and ROI-tracking work in the Projects section.

🔗 **Live site:** _add your deployed URL here_

## ✨ Sections

- **Hero** — name, role, and current status
- **Focus** — short bio + a "currently learning" card tracking progress
  through the DeepLearning.AI Machine Learning Specialization
- **Timeline** — education → civil services prep → current upskilling
- **Projects** — 3D Object Reconstruction, Finger Vein Recognition,
  Automatic Headlight Controller (ADAS)
- **Skills** — languages, CS foundations, and skills currently being learned
- **Competitive Programming** — HackerRank and LeetCode stats
- **Contact** — email, GitHub, LinkedIn

## 🛠️ Built With

Plain HTML, CSS, and vanilla JavaScript — no build step, no framework.

- `index.html` — page structure and content
- `style.css` — design system (CSS custom properties for color/type/spacing)
- `script.js` — mobile nav toggle, scroll-reveal, footer year

Fonts: [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) and
[IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans) via Google Fonts.

## 🚀 Getting Started

No install required — it's static HTML/CSS/JS.

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# open directly in a browser
open index.html

# or serve it locally
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## 📁 Project Structure

```
├── index.html
├── style.css
├── script.js
├── Resume_Rajveer_Singh.pdf   # add your resume PDF here for the download button
└── README.md
```

## 📝 To customize / finish setup

1. Drop your latest resume PDF into the repo root as
   `Resume_Rajveer_Singh.pdf` (or update the filename in the download link
   in `index.html`).
2. Replace the placeholder GitHub/LinkedIn URLs in the **Contact** section
   of `index.html` with your real profiles.
3. Update the "currently learning" progress card in the **Focus** section
   as you complete more of the ML Specialization (or swap it for whatever
   you're studying next).
4. As you gain work experience, add a **Experience** section between
   Timeline and Projects following the same card/timeline patterns already
   in the CSS.

## 📦 Deployment

Static files, so any static host works:

- **GitHub Pages** — Settings → Pages → deploy from the `main` branch
- **Vercel** / **Netlify** — import the repo, no build command needed

## 📄 License

MIT — feel free to fork and adapt.

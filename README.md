# Portfolio — Yash Raghuwanshi

A single-page portfolio site (plain HTML/CSS/JS, zero build step) covering background,
projects, skills, certifications, and contact info.

## ⚠️ Before you deploy — fix the project links

I only had `https://github.com/yashraghuwa-prog/demo` confirmed, so the four project
links in `index.html` are **placeholder guesses** based on likely repo names:

```
https://github.com/yashraghuwa-prog/reelpredict
https://github.com/yashraghuwa-prog/student-grade-management-system
https://github.com/yashraghuwa-prog/realtime-chat-app
https://github.com/yashraghuwa-prog/unit-currency-converter
```

Open `index.html`, search for `card-link`, and swap each `href` for the real repo URL
(or push your existing project code to repos with these exact names and the links will
already work). The GitHub profile link in the nav/contact section
(`https://github.com/yashraghuwa-prog`) is correct as given.

## What's included

- **Hero** — name, role, short intro
- **About** — bio + quick facts (education, CGPA, focus area, location)
- **Projects** — ReelPredict, Student Grade & Performance Management System, Real-Time
  Chat Application, Unit & Currency Converter
- **Skills** — languages, ML & data, web, tools
- **Certifications** — IBM ML Professional Certificate, Microsoft Azure AI Fundamentals (AI-900)
- **Contact** — email + GitHub

Kept purely technical/professional since the goal is SDE/ML roles — no unrelated content
sections. Easy to add a "Content" or "Other work" section later the same way the
Projects section is structured, if you ever want to include the reels work too.

## Run locally

```bash
npx serve .
```

## Deploy for free (GitHub + Vercel)

1. **GitHub** — create a new public repo (e.g. `portfolio`), then:
   ```bash
   git init
   git add .
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/yashraghuwa-prog/<repo-name>.git
   git push -u origin main
   ```

2. **Vercel** — sign in at [vercel.com](https://vercel.com) with GitHub (free, no card),
   **Add New → Project**, select the repo, framework preset **Other** (no build/install
   command needed — it's static files), click **Deploy**.

You'll have a live `*.vercel.app` URL in under a minute, completely free.

## Optional next steps

- Add a LinkedIn link next to the GitHub button in `index.html` once you have the URL
  (same pattern as the existing `.btn-ghost` link).
- Add a downloadable resume PDF: drop the file in this folder and link it from the hero
  or contact section, e.g. `<a class="btn btn-ghost" href="resume.pdf" download>Resume</a>`.
- Once the Unit & Currency Converter is live on Vercel, you could add a second "Live demo"
  link next to its GitHub link on the project card.

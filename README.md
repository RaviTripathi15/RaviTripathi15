<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:6366f1,50:8b5cf6,100:ec4899&text=Hi,%20I'm%20Ravi%20Tripathi%20👋&fontColor=ffffff&fontSize=44&animation=fadeIn&desc=Aspiring%20Software%20Engineer%20%7C%20DSA%20%2B%20Full%20Stack&descAlignY=68&descSize=17"/>

<a href="https://github.com/RaviTripathi15"><img src="https://img.shields.io/badge/GitHub-RaviTripathi15-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/ravi-tripathi-2b9690376"><img src="https://img.shields.io/badge/LinkedIn-Ravi%20Tripathi-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:tripathiravi5500@gmail.com"><img src="https://img.shields.io/badge/Email-tripathiravi5500%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=RaviTripathi15&style=for-the-badge&color=6366f1&label=PROFILE+VIEWS"/>

</div>

<br/>

## 🧑‍💻 About Me

I'm a **B.Tech CSE student** building the two things every strong SDE candidate needs in parallel: **rock-solid problem-solving (DSA)** and **real, deployed full-stack products**.

```text
🎯 Goal        →  Software Engineer role at a top product company
📚 Focus       →  Java DSA · System Design fundamentals · REST APIs
🛠️ Building    →  Production-grade MERN applications, end to end
🌱 Philosophy  →  Understand deeply → build cleanly → ship confidently
```

I'm not optimizing for shortcuts — I'm optimizing for the kind of fundamentals that hold up in a real interview loop and a real production system.

---

## 🎯 Roadmap

```text
 ✅  Java Core & OOP fundamentals
 ✅  Full-stack MERN apps (auth, DB, deployment)
 🔄  Data Structures & Algorithms — arrays, hashmaps, strings (Java)
 🔄  SQL — joins, indexing, query optimization
 🔜  Trees, Graphs & Dynamic Programming
 🔜  System Design fundamentals (caching, load balancing, scaling)
 🔜  Open source contributions
 🔜  SDE / Full-Stack internship
```

---

## 🛠️ Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=java,js,react,html,css,tailwind&theme=light" />
</p>
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,python,mysql,mongodb&theme=light" />
</p>
<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman,vercel&theme=light" />
</p>

---

## 🚀 Featured Projects

| Project | Stack | What it does |
|---|---|---|
| 🏥 **[Hospital Management System](https://github.com/RaviTripathi15/hospital-management-system)** | React · Node.js · Express · MongoDB Atlas | Full-stack app for managing patients, appointments, and hospital records with a REST API backend. |
| 🎓 **[Student Management System](https://github.com/RaviTripathi15/student-management-system)** | React · Node.js · Express · MongoDB Atlas | CRUD-based platform for managing student records, built on the MERN stack. |
| 🚦 **[Train Traffic Control](https://github.com/RaviTripathi15/train-traffic-control)** | React (Vercel) · Node.js (Render) | Deployed full-stack system for simulating and managing train traffic, with a separately hosted frontend and backend. |

> ⚠️ Swap the slugs above (`hospital-management-system`, etc.) for your actual repo names — links currently pointing at just `github.com/RaviTripathi15` will 404 on click since that's your profile, not a repo.

---

## 🧠 DSA Progress (Java)

```text
Arrays & HashMaps        ██████████░░  Solid — rank transforms, prefix problems
Strings                  █████████░░░  Strong
Linked Lists              ████████░░░░  In Progress
Stacks & Queues           ███████░░░░░  In Progress
Trees & Graphs            █████░░░░░░░  Learning
Recursion & Backtracking  ██████░░░░░░  Building
Dynamic Programming       ████░░░░░░░░  Upcoming
```

---

## 📊 GitHub Stats

<div align="center">

<img height="175em" src="https://github-stats-extended.vercel.app/api?username=RaviTripathi15&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=6366f1&icon_color=8b5cf6&text_color=c9d1d9"/>
<img height="175em" src="https://github-stats-extended.vercel.app/api/top-langs/?username=RaviTripathi15&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=6366f1&text_color=c9d1d9"/>

<br/>

<img src="https://streak-stats.demolab.com?user=RaviTripathi15&theme=tokyonight&hide_border=true&background=0d1117&ring=6366f1&fire=8b5cf6&currStreakLabel=6366f1"/>

</div>

> **Verified working:** I tested all three card URLs directly and they render correctly. `github-stats-extended.vercel.app` is the actively-maintained successor to the old `github-readme-stats.vercel.app` (that one is now community-flagged as unstable), so no changes needed here. `streak-stats.demolab.com` is also fine as-is.
>
> One thing to know: `count_private=true` only shows real numbers if you enable **"Include private contributions"** on your GitHub profile (Settings → Profile → Contributions & activity). Otherwise it'll just show your public count even though the parameter is present.

---

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RaviTripathi15/RaviTripathi15/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/RaviTripathi15/RaviTripathi15/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/RaviTripathi15/RaviTripathi15/output/github-contribution-grid-snake.svg">
  </picture>
</p>

<details>
<summary>⚙️ Snake Workflow Setup (fixed — see change below)</summary>

Create `.github/workflows/snake.yml` **in your special `RaviTripathi15/RaviTripathi15` repo**:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: Generate snake SVG
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: RaviTripathi15
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push snake SVG to the output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

**What was actually broken and why your snake image was a 404:**
1. **Missing `permissions: contents: write`** — this is the real fix. GitHub changed the default `GITHUB_TOKEN` permissions to read-only for newer repos. Without this block, the `output` branch push fails silently and the workflow shows green even though nothing got pushed.
2. Added an explicit `actions/checkout@v4` step so the action runs against a clean checkout.
3. Hardcoded `github_user_name: RaviTripathi15` instead of relying on `github.repository_owner` — safer if you ever rename the repo.

**After committing this file:**
- Go to your `RaviTripathi15/RaviTripathi15` repo → **Actions** tab → select "Generate Snake" → **Run workflow** manually the first time.
- Check that an `output` branch now exists in the repo with the SVG files in it.
- The image URLs in this README don't need to change — they'll start resolving once that branch exists.

</details>

---

## 💭 How I Think About Code

```text
Understand the problem before writing line one.
Get it working, then make it clean.
A slow query will quietly kill a fast app.
Readable code is a gift to your future self — and your reviewer.
Depth compounds. Consistency compounds faster.
```

---

## 📚 Currently Learning

- ☕ **Java** — DSA patterns: hashmaps, trees, graphs, DP
- 🗃️ **SQL** — indexing, joins, query optimization
- 🔗 **REST API design** — auth, error handling, rate limiting
- 🏗️ **System Design fundamentals** — caching, load balancing, scaling
- 📊 **Data Analytics** — pandas, PACE framework (Google Advanced Data Analytics Certificate)

---

<div align="center">

### 🌱 Building today. Interviewing tomorrow. Improving always.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=120&color=0:6366f1,50:8b5cf6,100:ec4899"/>

</div>

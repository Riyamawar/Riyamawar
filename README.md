<h1 align="center">Hi 👋, I'm Riya Mawar</h1>
<h3 align="center">A Data Analyst & Machine Learning Enthusiast from India</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/riyamawar" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://www.kaggle.com/riyamawar" target="_blank">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" />
  </a>
  <a href="mailto:riyamawar8@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/Riyamawar" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

### 🚀 About Me

- 🌱 Currently learning **Machine Learning, Data Science, Advanced SQL & Statistics**
- 💼 All of my projects are available at **[github.com/Riyamawar](https://github.com/Riyamawar)**
- 💬 Ask me about **Python, SQL, Excel, Power BI, Tableau, Data Analysis & Data Visualization**
- 📫 Reach me at **riyamawar8@gmail.com**
- ⚡ Fun fact — I enjoy turning messy, real-world data into clear business insights, and I'm always exploring new tools and technologies 📊

---

### 🛠️ Languages & Tools

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Riyamawar&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Riyamawar&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Riyamawar&theme=tokyonight&hide_border=true" />
</p>

---

### 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/Riyamawar/Riyamawar/output/github-contribution-grid-snake.svg" alt="contribution snake animation" />
</p>

<p align="center"><i>⚠️ This animates automatically once the GitHub Action below is set up (one-time, 2 minutes) — see setup note at the bottom.</i></p>

---

### 📌 Featured Projects

| Project | Description | Tools |
|---|---|---|
| [Customer Churn Analysis (Python + SQL)](https://github.com/Riyamawar/customer-churn-analysis-python-sql) | End-to-end churn analysis — Python for data cleaning & EDA, SQL for business insights and customer ranking with window functions. | Python, Pandas, Seaborn, SQL |
| [Swiggy Sales Analysis](https://github.com/Riyamawar/swiggy-sales-analysis-python) | Analyzed food-delivery sales data to uncover ordering trends and performance patterns. | Python, Pandas |
| [Coffee Shop Sales Dashboard](https://github.com/Riyamawar/Coffee-Shop-sales-dashboard) | Interactive dashboard tracking coffee shop sales performance and trends. | Excel |
| [Spotify Power BI Dashboard](https://github.com/Riyamawar/Spotify_PowerBI-Dashboard) | Visualized Spotify listening/streaming data to surface trends and insights. | Power BI |
| [Retail Sales SQL Analysis](https://github.com/Riyamawar/Retail-Sales-SQL-Analysis) | Queried retail sales data with SQL to answer key business questions on revenue and performance. | SQL |
| [Airbnb Business Intelligence Dashboard](https://github.com/Riyamawar/Airbnb-Business-Intelligence-Dashboard) | Built a BI dashboard analyzing Airbnb listings and booking trends. | Power BI |
| [Sales Data Analysis](https://github.com/Riyamawar/sales-data-analysis) | Explored and analyzed sales data to identify key business trends. | Python |

<p align="center"><i>🔗 See all repositories at <a href="https://github.com/Riyamawar?tab=repositories">github.com/Riyamawar</a></i></p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Riyamawar&style=flat-square&color=blue" alt="profile views" />
</p>

<p align="center"><i>Thanks for visiting my profile — let's connect and build something with data! 🚀</i></p>

---

<details>
<summary>⚙️ One-time setup: activating the contribution snake</summary>

The snake animation above needs a small GitHub Action to generate it. Do this once in your `Riyamawar/Riyamawar` repo:

1. In your repo, go to **Add file → Create new file**.
2. Name it: `.github/workflows/snake.yml`
3. Paste this content:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"   # runs daily
  workflow_dispatch: {}
  push:
    branches: [ "main" ]

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        id: snake-gif
        with:
          github_user_name: Riyamawar
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

4. Commit the file. Go to the **Actions** tab, and manually run the "Generate Snake" workflow once (click "Run workflow").
5. Wait ~1 minute — it will create an `output` branch with your snake SVG, and the image in your README will start working automatically.

</details>

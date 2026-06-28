<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Russo+One&size=42&pause=1200&color=EF4444&center=true&vCenter=true&width=640&height=72&lines=MMA+STATUS;UFC+stats+%2B+ML+fight+predictions" alt="MMA STATUS" />

</div>

### 👋 Hey

I build and run **MMA STATUS**, a live UFC stats site with a machine-learning fight predictor that is up and serving predictions in production. The project lives across two repos:

- **[mma-app](https://github.com/chocitagaming-art/mma-app)** — the web app in Next.js and TypeScript.
- **[mma-ingesta](https://github.com/chocitagaming-art/mma-ingesta)** — the scrapers, the XGBoost model and the FastAPI service that powers the predictions.

The model reaches about 63% accuracy with a Brier score of 0.2266, trained on a dataset of ~2,838 fighters and ~8,750 fights. It uses 20 features, all of them statistical: betting odds are never an input, so I can put the market line and the model side by side and compare them, which is uncommon in similar projects.

🔴 **[Live demo](https://mma-app-ruby.vercel.app)** &nbsp;·&nbsp; 🇪🇸 Hablo español

### 🛠️ Stack

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5E28?style=for-the-badge&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

### 🥊 Featured

<a href="https://github.com/chocitagaming-art/mma-app">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=chocitagaming-art&repo=mma-app&theme=github_dark&title_color=ef4444&icon_color=ef4444&hide_border=true" alt="mma-app" />
</a>
<a href="https://github.com/chocitagaming-art/mma-ingesta">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=chocitagaming-art&repo=mma-ingesta&theme=github_dark&title_color=ef4444&icon_color=ef4444&hide_border=true" alt="mma-ingesta" />
</a>

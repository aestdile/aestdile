# Welcome, I'm Mukhtor Eshboyev!

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aestdile&show_icons=true&theme=radical&include_all_commits=true&count_private=true" alt="GitHub Stats" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=aestdile&theme=radical" alt="GitHub Streak" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aestdile&layout=compact&theme=radical" alt="Top Languages" />
</div>

## 🛠️ Mening texnologiyalarim

<div align="center">
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
</div>

## 📊 GitHub statistikasi

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=aestdile&theme=radical&no-frame=true&row=1" alt="Trophy" />
</div>

## 🔍 Meni toping

<div align="center">
  <a href="https://twitter.com/aestdile">
    <img src="https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/aestdile">
    <img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=aestdile&color=blueviolet&style=for-the-badge" alt="Profile views" />
</div>

<!-- GitHub Activity Graph -->
<img src="https://activity-graph.herokuapp.com/graph?username=aestdile&theme=radical" width="100%" />

<!-- SVG Animation  -->

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200">
  <!-- Background gradient -->
  <defs>
    <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#3a1c71;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#d76d77;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#ffaf7b;stop-opacity:1" />
    </linearGradient>
  </defs>
  
  <!-- Background Rectangle -->
  <rect width="800" height="200" rx="10" ry="10" fill="url(#grad)" />
  
  <!-- Decorative Elements -->
  <circle cx="100" cy="50" r="20" fill="#ffffff" fill-opacity="0.1" />
  <circle cx="700" cy="150" r="30" fill="#ffffff" fill-opacity="0.1" />
  <circle cx="200" cy="170" r="15" fill="#ffffff" fill-opacity="0.1" />
  <circle cx="600" cy="50" r="25" fill="#ffffff" fill-opacity="0.1" />
  
  <!-- Code-like decoration elements -->
  <text x="50" y="45" font-family="monospace" font-size="14" fill="#ffffff" fill-opacity="0.6">const developer = new Developer('aestdile');</text>
  <text x="50" y="65" font-family="monospace" font-size="14" fill="#ffffff" fill-opacity="0.6">developer.createAmazingThings();</text>
  
  <!-- Name -->
  <text x="400" y="100" font-family="Arial, sans-serif" font-size="48" font-weight="bold" text-anchor="middle" fill="#ffffff">Mukhtor Eshboyev</text>
  
  <!-- Subtitle -->
  <text x="400" y="140" font-family="Arial, sans-serif" font-size="24" text-anchor="middle" fill="#ffffff">Software Developer & Creator</text>
</svg>


name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: aestdile
          gif_out_path: dist/github-contribution-grid-snake.gif
          svg_out_path: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          ![Snake animation](https://github.com/aestdile/aestdile/blob/output/github-contribution-grid-snake.svg)



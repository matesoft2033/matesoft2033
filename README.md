<h1 align="center">Hi 👋, I'm Mate Sitchinava</h1>
<h3 align="center">A passionate Frontend Developer from Georgia</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=matesoft2033&label=Profile%20views&color=0e75b6&style=flat" alt="matesoft2033" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=matesoft2033" alt="matesoft2033" /></a> </p>

<p align="left"> <a href="https://twitter.com/https://x.com/matesichin11635" target="blank"><img src="https://img.shields.io/twitter/follow/https://x.com/matesichin11635?logo=twitter&style=for-the-badge" alt="https://x.com/matesichin11635" /></a> </p>

- 🌱 I’m currently learning **Javascript, VueJS and NodeJS**

- 👯 I’m looking to collaborate on **Front-end projects**

- 🤝 I’m looking for help with **Javascript**

- 💬 Ask me about **Front-end**

- 📫 How to reach me **matesichinava777@gmail.com**

- ⚡ Fun fact **I want to create youtube videos**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/https://x.com/matesichin11635" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="https://x.com/matesichin11635" height="30" width="40" /></a>
<a href="https://linkedin.com/in/mate sichinava" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="mate sichinava" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://jestjs.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="jest" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=matesoft2033&show_icons=true&locale=en&layout=compact" alt="matesoft2033" /></p>
name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - master

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg?palette=github-dark


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=matesoft2033&show_icons=true&locale=en" alt="matesoft2033" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=matesoft2033&" alt="matesoft2033" /></p>

## Olá! Eu sou o Marcelo Magalhães 🖐️😊

### <p>Sou um estudante de Programação, e durante essa minha jornada nos estudos acabei me apaixonando ainda mais pela profissão! </p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=whit)](https://linkedin.com/in/marcelo-cordeiro-848652333)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/celokomaga/)
[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/channels/@celokomemo)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](https://marcelinho.magalhaes.c@gmail.com)

![Marcelo GitHub stats](https://github-readme-stats.vercel.app/api?username=celokomaga&show_icons=true&theme=dracula)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=celokomaga&exclude_repo=github-readme-stats,anuraghazra.github.io)

## Tecnologias que eu uso no meu dia a dia 🤖👾

<picture›
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/celokomaga/celokomaga/output/github-contribution-grid-snake-dark.svg">
<source media=" (prefers-color-scheme: light) srset=https://raw.githubusercontent.com/celokomaga/celokomaga/output/github-contribution-grid-snake.svg">
<img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/mari4souza/mari4souza/output/github-contribution-grid-snake.svg">
</picture>
<br><br>

name: Generate Snake

on:
  schedule: # executa automaticamente a cada 24h
    - cron: "0 0 * * *"
  workflow_dispatch: # permite rodar manualmente

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v3

      - name: Generate the snake
        uses: Platane/snk@v3
        with:
          github_user_name: celokomaga  # coloque seu usuário aqui
          outputs: dist/github-contribution-grid-snake.svg
          # Cores personalizadas
          color_snake: "#00ff99"
          color_dots: "#1a1a1a,#333333,#66ffcc,#99ffcc,#ccfff0"
      
      - name: Push snake to the output branch
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<div style="display inline_block"><br/>
<img align="center" alt="html5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img align="center" alt="css" src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white" />
<img align="center" alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img align="center" alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0d1117&height=120&section=header&text=Daniel%20Walczak&fontSize=50&fontColor=4ade80&descAlignY=70&descAlign=50"/>
  
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=300&size=20&pause=1000&color=4ade80&center=true&vCenter=true&width=500&lines=Desenvolvedor+de+Software;Integração+de+APIs+%26+ETL;Automação+com+Python+%26+Selenium;Mentoria+em+TI" alt="Typing Animation" />
  </a>
</div>

<br/>

## 👨‍💻 Sobre mim

Desenvolvedor de software atuando em Bento Gonçalves, RS, com foco na construção de sistemas web robustos e arquiteturas orientadas a dados. Combino práticas de engenharia de software com análise de dados para otimizar processos de ponta a ponta.

- ⚙️ **Especialidades:** Desenvolvimento backend e frontend, processos de **ETL**, estruturação de bancos de dados e integração de **APIs REST**.
- 🤖 **Automação:** Experiência prática na criação de rotinas automatizadas e web scraping utilizando **Selenium**.
- 🤝 **Mentoria e Liderança:** Atuo como consultor e mentor de TI, auxiliando no desenvolvimento técnico de equipes, estruturação de soluções Microsoft 365 e planejamento de projetos.
- 🎯 **Foco:** Entregar código limpo, escalável e soluções que trazem impacto real para o negócio.

<br/>

## 🛠️ Tecnologias e Ferramentas

<div align="center">
  <img src="https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=4ade80" alt="Python" />
  <img src="https://img.shields.io/badge/PHP-0d1117?style=for-the-badge&logo=php&logoColor=4ade80" alt="PHP" />
  <img src="https://img.shields.io/badge/Laravel-0d1117?style=for-the-badge&logo=laravel&logoColor=4ade80" alt="Laravel" />
  <img src="https://img.shields.io/badge/SQL-0d1117?style=for-the-badge&logo=mysql&logoColor=4ade80" alt="SQL" />
  <img src="https://img.shields.io/badge/Vue.js-0d1117?style=for-the-badge&logo=vuedotjs&logoColor=4ade80" alt="Vue.js" />
  <img src="https://img.shields.io/badge/Selenium-0d1117?style=for-the-badge&logo=selenium&logoColor=4ade80" alt="Selenium" />
</div>

<br/>

## 📊 GitHub Analytics

<div align="center">
  <!-- Substitua "daniel-walczak01" pelo seu username exato do GitHub caso seja diferente -->
  <img src="https://github-readme-stats.vercel.app/api?username=daniel-walczak01&show_icons=true&bg_color=0d1117&text_color=a3a3a3&icon_color=4ade80&title_color=4ade80&hide_border=true&include_all_commits=true" height="195" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=daniel-walczak01&layout=compact&bg_color=0d1117&text_color=a3a3a3&title_color=4ade80&hide_border=true" height="195" alt="Top Languages" />
</div>

<div align="center">
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=daniel-walczak01&theme=dark&background=0d1117&border=00000000&stroke=00000000&ring=4ade80&fire=4ade80&currStreakNum=a3a3a3&sideNums=a3a3a3&currStreakLabel=4ade80&sideLabels=4ade80&dates=a3a3a3" alt="GitHub Streak" />
</div>

<div align="center">
  <br/>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=daniel-walczak01&bg_color=0D1117&color=4ade80&line=4ade80&point=FFFFFF&area=true&hide_border=true" alt="Activity Graph" />
</div>

<div align="center">
  <br/>
  <img src="https://github-profile-trophy.vercel.app/?username=daniel-walczak01&row=1&column=6&margin-w=15&margin-h=15&no-frame=true&no-bg=true&theme=nord" alt="GitHub Trophies" />
</div>

<br/>

## 🐍 Commits Snake Animation

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/daniel-walczak01/daniel-walczak01/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/daniel-walczak01/daniel-walczak01/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/daniel-walczak01/daniel-walczak01/output/github-contribution-grid-snake.svg">
  </picture>
</div>

<details>
<summary><b>Como ativar a Animação da Cobrinha (Snake)</b></summary>
<br/>
Para que a animação acima funcione, crie o arquivo <code>.github/workflows/snake.yml</code> no repositório do seu perfil com o seguinte código:

```yaml
name: Generate Snake
on:
  schedule: # Executa a cada 12 horas
    - cron: "0 */12 * * *"
  workflow_dispatch:
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

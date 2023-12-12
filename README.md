### Hi there 👋
I'm Youssef, a passionate developer from  Morocco. Here are some things you should know about me:

- 🚀 I'm currently studying in Youcode
- 🌱 I'm learning PHP JavaScript SQL 
- 💬 Ask me about HTML CSS CSS-TAILWIND
- 📫 How to reach me: youssefhihi@gmail.com

## My GitHub

- [Youssef Hihi](https://github.com/youssefhihi)
- ![Snake animation](https://github.com/thepiyushmalhotra/thepiyushmalhotra/blob/output/github-contribution-grid-snake.svg)
name: Generate Datas
on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:
jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
with:
          github_user_name: thepiyushmalhotra
          svg_out_path: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

## Let's Connect

- [LinkedIn](https://www.linkedin.com/in/youssef-hihi-566b5b2a4)

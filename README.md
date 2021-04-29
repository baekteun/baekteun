<!--
**baekteun/baekteun** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
![header](https://capsule-render.vercel.app/api?type=slice&color=auto&height=300&section=header&text=BAEKTEUN&fontSize=90)
![baekteun's github stats](https://github-readme-stats.vercel.app/api?username=baekteun&show_icons=true)
![TOP Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=baekteun&layout=compact&thema=dracula)
<!--START_SECTION:waka-->
name: Waka Readme

on:
  workflow_dispatch:
  schedule:
    # Runs at 12am UTC
    - cron: "0 0 * * *"

jobs:
  update-readme:
    name: Update this baekteun's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
<!--END_SECTION:waka-->

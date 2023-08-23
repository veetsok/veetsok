# 💫 About Me:
Hi there! 👋 Thanks for stopping by!<br>My name is Ivan, and  I'm a junior web developer.<br>Whether it's creating full stack applications, websites, or something new for the web, I combine stellar design, optimal UI/UX, and industry best practices for the tech stack.<br>How to reach me: Telegram - [@ivan_veetsok](https://t.me/ivan_veetsok).<br>Let's connect!


# 💻 Tech Stack:
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
# 📊 GitHub Stats:
[![codewars](https://www.codewars.com/users/veetsok/badges/large)](https://www.codewars.com/users/veetsok)</br>
![](https://github-readme-stats.vercel.app/api?username=veetsok&theme=dark&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=veetsok&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=veetsok&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)<br/>



---
[![](https://visitcount.itsvg.in/api?id=veetsok&icon=0&color=0)](https://visitcount.itsvg.in)
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ [github.repository_owner](https://github.com/veetsok) }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

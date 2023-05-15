<h1 dir ="auto" style="color: #137a7f;font-size: 40px;">你好，我是无雨</h1>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=3000&color=E12885&width=435&lines=%E4%BB%8A%E5%B9%B4%E5%92%B2%E3%81%84%E3%81%9F%E5%90%91%E6%97%A5%E8%91%B5(%E3%81%B2%E3%81%BE%E3%82%8F%E3%82%8A)+%E3%81%9D%E3%82%8C%E3%81%8C%E7%A7%81%E3%81%AA%E3%82%93%E3%81%A7%E3%81%99)](https://git.io/typing-svg)

<img src="mikuHead.png" alt="miku" style="display: block;" />

- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

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

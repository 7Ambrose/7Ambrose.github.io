site_name: 我的学习空间
site_description: 记录学习，整理笔记，分享资料
site_url: https://AmbrOse.github.io/

theme:
  name: material
  language: zh
  features:
    - navigation.tabs
    - navigation.top
    - search.highlight
    - content.code.copy
  palette:
    - scheme: default
      primary: indigo
      accent: indigo
      toggle:
        icon: material/brightness-7
        name: 切换到深色模式
    - scheme: slate
      primary: indigo
      accent: indigo
      toggle:
        icon: material/brightness-4
        name: 切换到浅色模式

plugins:
  - search

markdown_extensions:
  - admonition
  - pymdownx.details
  - pymdownx.superfences
  - toc:
      permalink: true

nav:
  - 首页: index.md
  - 学习笔记:
      - 数学:
          - 第一篇笔记: notes/math/first.md
  - 资料下载: resources.md
  - 关于我: about.md

<!--
  图片两类：① 外链服务 shields.io / readme-typing-svg.demolab.com / visitor-badge.laobi.icu
  （实测可直连）；② 本仓库 Action 生成，走 fastly.jsdelivr.net 镜像 raw.githubusercontent.com，
  push 后需到 Actions 页手动 Run 一次 snake 工作流，否则是裂图。
  本文件不写任何固定数字：star / fork / 贡献者数一律由 shields.io 实时渲染。
  统计图只留一张 snake：它渲染的是贡献日历（含跨仓库提交），且做了亮/暗双主题。
  已删：5 张 profile-summary-cards（数据源是"自己名下的仓库"，与本人贡献结构相反）、
  3D 贡献图（与 snake 同一份数据、固定深色主题、全篇最高）、
  streak-stats（同为贡献日历的另一种呈现，且固定深色主题）。
  本文件刻意保持纯 BMP（不写 emoji）：edit 工具与 ReadAllLines+join 都会静默吞掉非 BMP 字符，
  与其每次验收不如不写；改写一律走 ReadAllText -> Replace -> WriteAllText(UTF8Encoding($false))。
  名言靠左、署名靠右：用 <p align="left"> / <p align="right">——GitHub 剥掉 style，但保留 align 属性。
  头像亮/暗双主题：image/+1.jpeg（亮）与 image/-1.jpeg（暗）用 <picture> + prefers-color-scheme 自动切换。
  GitHub 保留 <picture>/<source> 的 media 与 srcset，但 media 只认 prefers-color-scheme，
  按宽度做 art direction 会被剥掉；URL 片段法 #gh-dark-mode-only / #gh-light-mode-only 已被 GitHub 废弃。
  仓库内相对路径图片由 GitHub 自己托管渲染（不经过本机 hosts 污染的 raw.githubusercontent.com）。
  两张头像已压到 400x400（显示宽 200px 的 2 倍），一共约 49KB；不要再放回 1500px 的原图（两张共 761KB）。
  与引语左右并列用 <table>：GitHub 会剥掉 style 属性（flex/grid 无效），表格内必须全用 HTML 且不能夹空行。
-->

<div align="center">

<img src="assets/banner.svg" alt="YV3507" width="100%" />

<a href="https://github.com/YV3507">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1200&color=36BCF7&center=true&vCenter=true&width=780&height=48&lines=%24+whoami;Feature+integration+%2F+Refactoring+%2F+Co-development;Second+author%2C+first-class+output." alt="typing" />
</a>
</div>

<br/>

<table>
<tr>
<td>
<blockquote>
<p align="left"><em>"Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away."<br/>
完美不是无可增添，而是无可删减。</em></p>
<p align="right">&mdash;&mdash;&mdash;安托万·德·圣-埃克苏佩里</p>
</blockquote>
协作开发 · 功能并入 · 重构与集成 —— 把已经跑起来的项目接过来，让它跑得更好。<br/>
Not greenfield ownership, but taking a project that already moves and making it move better.
</td>
<td width="300" align="center" valign="middle">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="image/-1.jpeg" />
<source media="(prefers-color-scheme: light)" srcset="image/+1.jpeg" />
<img src="image/+1.jpeg" width="200" alt="YV3507" />
</picture>
<br/><br/>
<img src="https://img.shields.io/github/followers/YV3507?label=Followers&style=flat-square&color=36BCF7&logo=github&logoColor=white" alt="followers" />
<br/>
<img src="https://visitor-badge.laobi.icu/badge?page_id=YV3507.YV3507" alt="visitors" />
<br/>
<img src="https://img.shields.io/github/last-commit/elysia395/dsh-wallpaper-engine?label=last%20commit&style=flat-square&color=22D3A6&logo=git&logoColor=white" alt="last commit" />
</td>
</tr>
</table>

<br/>

<div align="center">

<img src="https://img.shields.io/github/stars/elysia395/dsh-wallpaper-engine?label=stars&style=flat-square&color=36BCF7" alt="stars" />
<img src="https://img.shields.io/github/forks/elysia395/dsh-wallpaper-engine?style=flat-square&color=8B5CF6" alt="forks" />
<img src="https://img.shields.io/github/contributors/elysia395/dsh-wallpaper-engine?style=flat-square&color=22D3A6" alt="contributors" />

<a href="https://github.com/elysia395/dsh-wallpaper-engine"><b>dsh-wallpaper-engine</b></a> 上提交最多的人——不是 owner，是先替上游把墙撞一遍的那个。

</div>

<br/>

<div align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Axum-000000?style=flat-square&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/Qt-41CD52?style=flat-square&logo=qt&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" />
<img src="https://img.shields.io/badge/Keil%20MDK-0091BD?style=flat-square&logo=arm&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
<img src="https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl&logoColor=white" />

</div>

<br/>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://fastly.jsdelivr.net/gh/YV3507/YV3507@output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://fastly.jsdelivr.net/gh/YV3507/YV3507@output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://fastly.jsdelivr.net/gh/YV3507/YV3507@output/github-contribution-grid-snake.svg" />
</picture>

<br/><br/>

祝你的 build 常绿，重构不背锅。需要有人接手半成品的时候，开 issue 就行。<br/>
May your builds stay green and your refactors never take the blame.

</div>

# 册府 · Cefu — 古今中外史学家时间轴

> 取《册府元龟》府库之意，收藏天下史家
> *A Treasury of Historians — an interactive timeline of Chinese and Western historiography*

「册府」是一个面向初学者的交互式史学史网站。不论你是高中生、历史爱好者还是历史学萌新，都能在这里用最直白的方式了解中外重要史学家、他们的代表作与所属流派。

*Cefu is an interactive, beginner-friendly website on the history of historiography. Whether you are a high-school student, a history enthusiast, or a newcomer to the field, it introduces the major historians of China and the West, their key works, and the schools they belong to — all in plain language.*

---

## ✨ 功能特点 · Features

**中文**

- **竖向时间轴**：131 位中外史学家按时代排列，卡片左右交替挂在中轴线两侧，手机和电脑都顺手。
- **三轴筛选 + 搜索**：可按地区（中国 / 外国）、时代（古代—现当代）、流派自由组合筛选，也可直接搜索人名或著作。
- **史学家详情**：点击卡片，从右侧滑出抽屉，查看生卒年、国籍、代表作、所属流派与白话简介。
- **流派百科**：点击任意流派标签，弹出该流派的"一句话定性 + 通俗解释 + 代表人物"。
- **名著简介**：核心著作（带 ⓘ 标记）可点击，弹出该书主要内容的简介。
- **新中式美术**：水墨松枝 + 浅金几何的视觉风格，安静雅致。

**English**

- **Vertical timeline** of 131 historians arranged by era, with cards alternating along a central ink-pine spine — comfortable on both mobile and desktop.
- **Three-axis filtering + search**: filter freely by region (China / West), era (ancient → contemporary), and school of thought; or search by name or work.
- **Historian details**: click a card to open a side drawer with dates, nationality, key works, schools, and a plain-language introduction.
- **School encyclopedia**: click any school tag for a one-line definition, an accessible explanation, and representative figures.
- **Work introductions**: core classics (marked with ⓘ) are clickable, opening a summary of the book's main content.
- **New-Chinese-style aesthetic**: ink-wash pine sprigs and fine gold geometry for a calm, refined look.

---

## 📊 内容规模 · Content

| | 数量 / Count |
|---|---|
| 史学家 · Historians | **131** (中国 / Chinese: 63 · 西方 / Western: 68) |
| 史学流派 · Schools of historiography | **29** |
| 名著简介 · Annotated classics | **46** |
| 时代跨度 · Time span | 先秦 — 当代 / Pre-Qin — Contemporary |

内容整理自中外史学史教程与课程资料。
*Content compiled from Chinese and Western historiography textbooks and course materials.*

---

## 🚀 使用与部署 · Usage & Deployment

**中文**

本项目是**单文件 HTML**，无需任何依赖或构建步骤。

- **本地查看**：直接用浏览器打开 `index.html` 即可。
- **发布到 GitHub Pages**：
  1. 把 `index.html` 放在仓库根目录。
  2. 进入仓库 `Settings → Pages`。
  3. 在 `Source` 选择部署分支（通常是 `main`）和 `/ (root)` 目录，保存。
  4. 稍等片刻，GitHub 会生成一个公开网址（形如 `https://用户名.github.io/仓库名/`）。

**English**

This project is a **single HTML file** — no dependencies, no build step.

- **View locally**: just open `index.html` in any browser.
- **Publish on GitHub Pages**:
  1. Put `index.html` in the repository root.
  2. Go to `Settings → Pages`.
  3. Under `Source`, choose your branch (usually `main`) and the `/ (root)` folder, then save.
  4. After a moment, GitHub will give you a public URL like `https://username.github.io/repo-name/`.

---

## 🛠 技术栈 · Tech Stack

- 纯 **HTML / CSS / JavaScript**，无框架、无依赖 · Plain HTML / CSS / JavaScript, no framework, no dependencies
- 字体 · Fonts: Noto Serif SC, Noto Sans SC, EB Garamond (via Google Fonts)
- 全部数据与逻辑内联于单个文件 · All data and logic inlined in one file

---

## 🤝 欢迎补充 · Contributing

「册府」是一个开放的项目，欢迎补充更多史学家、著作简介或流派说明。

*Cefu is an open project. Contributions of additional historians, work summaries, or school descriptions are warmly welcomed.*

数据结构很直观：每位史学家是 `historians` 数组中的一个对象（含 `name / years / nation / region / era / schools / works / shortDesc / fullDesc`），流派与著作简介分别在 `SCHOOLS` 和 `WORKS` 对象中。

*The data structure is straightforward: each historian is an object in the `historians` array (with `name / years / nation / region / era / schools / works / shortDesc / fullDesc`); schools and work summaries live in the `SCHOOLS` and `WORKS` objects respectively.*

---

## 📄 许可 · License

可自由用于学习与非商业用途，欢迎自由分享给同学与朋友。
*Free for educational and non-commercial use. Feel free to share with classmates and friends.*

---

<p align="center"><i>made by Kira Zhang</i></p>

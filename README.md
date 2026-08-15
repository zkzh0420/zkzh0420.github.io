# Zhengkang Zhang | Personal Academic Homepage

A lightweight bilingual Jekyll site for GitHub Pages. The site uses a hand-written layout, a compact academic homepage structure, and separate English and Chinese entry pages.

Live site: [https://zkzh0420.github.io](https://zkzh0420.github.io)

## Highlights

- Bilingual homepage: English at `/` and Chinese at `/zh/`.
- Language toggle in the shared navigation bar.
- Lightweight custom layout without a heavy theme dependency.
- Profile, biography, experience, education, honors, and selected publications.
- Publication cards with local PDF links.
- GitHub Pages friendly Jekyll configuration.

## Project Structure

```text
_config.yml          # Site metadata, author profile, and Jekyll settings
index.html           # English homepage
zh/index.html        # Chinese homepage
_includes/           # Shared navigation and footer
_layouts/            # Shared page layouts
assets/css/style.css # Site styling
images/Profile.jpg   # Profile photo
files/               # Papers, CV, and other downloadable files
```

## Common Edit Points

- Update site metadata and author links in `_config.yml`.
- Edit the English homepage in `index.html`.
- Edit the Chinese homepage in `zh/index.html`.
- Place papers, CVs, or other public files in `files/`.
- Keep shared styling in `assets/css/style.css`.

## Run Locally

```bash
bundle install
bundle exec jekyll serve
```

Then open the local address printed by Jekyll, usually `http://127.0.0.1:4000/`.

## Commit Message Style

Use a short imperative subject line, followed by a blank line and a concise detail block. Group the details by theme: layout, content, data updates, and verification notes.

```text
Update English homepage structure

Replace the old hero-only English homepage with the bilingual homepage
structure used by the Chinese page. Translate profile, biography, experience,
education, honors, and selected publications into natural English.

Fix the profile photo path and keep language switching metadata aligned with
the Chinese page.
```

---

# 张正康 | 个人学术主页

这是一个面向 GitHub Pages 的轻量级双语 Jekyll 主页。网站采用手写布局，页面结构简洁，分别维护英文首页和中文首页，适合展示个人简介、研究经历、教育背景、荣誉奖项和代表性论文。

访问地址：[https://zkzh0420.github.io](https://zkzh0420.github.io)

## 主要特点

- 双语首页：英文页面位于 `/`，中文页面位于 `/zh/`。
- 顶部导航栏支持 EN/中文 切换。
- 使用轻量级自定义布局，不依赖复杂主题。
- 包含个人资料、简介、经历、教育背景、荣誉奖项和代表性论文。
- 论文以卡片形式展示，并支持本地 PDF 链接。
- 配置简洁，适合直接部署到 GitHub Pages。

## 项目结构

```text
_config.yml          # 网站信息、作者信息和 Jekyll 配置
index.html           # 英文首页
zh/index.html        # 中文首页
_includes/           # 公共导航栏和页脚
_layouts/            # 公共页面布局
assets/css/style.css # 网站样式
images/Profile.jpg   # 个人照片
files/               # 论文、简历和其他可下载文件
```

## 常用修改位置

- 在 `_config.yml` 中更新网站信息、作者信息和外部链接。
- 在 `index.html` 中修改英文主页内容。
- 在 `zh/index.html` 中修改中文主页内容。
- 将论文、简历或其他公开文件放入 `files/`。
- 在 `assets/css/style.css` 中统一调整页面样式。

## 本地运行

```bash
bundle install
bundle exec jekyll serve
```

启动后打开 Jekyll 输出的本地地址，通常是 `http://127.0.0.1:4000/`。

## 提交说明写法

以后提交时建议使用清晰的摘要行，加上一段分主题的细节说明。公开协作项目通常用英文提交说明；个人项目也可以用中文。重点是让以后回看历史时，能快速知道这次提交改了什么、为什么改。

```text
完善英文首页结构

将英文首页从旧的简短 hero 结构改为与中文首页一致的完整个人主页结构，
包括个人资料、简介、经历、教育背景、荣誉奖项和代表性论文。

同步翻译中文页面内容，并修正头像路径，保持中英文页面的语言切换信息一致。
```

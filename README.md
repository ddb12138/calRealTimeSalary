# 实时工资计算器（calRealTimeSalary）

一个纯前端的单页小工具：实时显示工作收入，并提供喝水、充电、摸鱼记录与锁屏等体验功能。  
项目为静态页面，无需后端，适合直接发布到 GitHub Pages 给朋友体验。

## 功能简介

- 实时工资显示（按工作时段与配置计算）
- 喝水 / 充电 / 摸鱼记录与收益统计
- 喝水提醒（支持 30 秒、10 分钟、15 分钟、30 分钟）
- 6 位数字锁屏与自动锁定倒计时
- 本地数据存储（浏览器 `localStorage`）

## 本地使用

直接双击打开 `index.html` 即可使用。

## 发布到 GitHub Pages（推荐）

### 1) 初始化并提交到 GitHub

在项目根目录执行：

```bash
git init
git add .
git commit -m "feat: initial release"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

### 2) 开启 Pages

1. 打开仓库页面 -> `Settings`
2. 左侧进入 `Pages`
3. `Source` 选择 `Deploy from a branch`
4. Branch 选择 `main`，目录选择 `/ (root)`，保存

稍等 1-2 分钟后，你会得到线上地址：

`https://<your-username>.github.io/<repo-name>/`

## 给朋友体验建议

- 分享 GitHub Pages 链接即可，无需安装任何环境
- 建议用最新版 Chrome/Edge 打开，体验更稳定
- 提醒朋友：数据保存在各自浏览器本地，不会同步到云端

## 项目结构（最小）

```text
calRealTimeSalary/
├─ index.html
├─ README.md
└─ .gitignore
```


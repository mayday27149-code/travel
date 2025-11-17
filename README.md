# 武汉×宜昌三峡（升船机）家庭亲子行程

一个精美的旅行计划网页，包含详细的行程安排、票务信息、预算和实用贴士。

## 功能特点

- 📱 移动端优化，支持离线阅读
- 🎨 现代化 UI 设计，美观易读
- 📅 支持添加到日历功能
- 🗺️ 详细的行程安排和交通指南
- 💰 预算估算和票务清单

## 本地预览

直接在浏览器中打开 `index.html` 文件即可预览。

## 发布到 GitHub Pages

### 方法一：通过 GitHub 网页界面（最简单）

1. **创建 GitHub 仓库**
   - 访问 [GitHub](https://github.com) 并登录
   - 点击右上角的 "+" 号，选择 "New repository"
   - 仓库名称建议：`trip-wuhan-yichang` 或 `travel-plan`
   - 选择 Public（公开）或 Private（私有）
   - **不要**勾选 "Initialize this repository with a README"
   - 点击 "Create repository"

2. **上传文件**
   - 在仓库页面，点击 "uploading an existing file"
   - 将项目中的所有文件拖拽上传（包括 `index.html`、`assets` 文件夹、`README.md` 等）
   - 在页面底部填写提交信息，如："Initial commit: 旅行计划网页"
   - 点击 "Commit changes"

3. **启用 GitHub Pages**
   - 在仓库页面，点击右上角的 "Settings"（设置）
   - 在左侧菜单中找到 "Pages"
   - 在 "Source" 部分，选择 "Deploy from a branch"
   - 在 "Branch" 下拉菜单中选择 "main"（或 "master"）
   - 在 "Folder" 中选择 "/ (root)"
   - 点击 "Save"
   - 等待几分钟，GitHub 会显示你的网站地址，格式为：`https://你的用户名.github.io/仓库名`

### 方法二：通过 Git 命令行（推荐）

1. **初始化 Git 仓库**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: 旅行计划网页"
   ```

2. **连接到 GitHub 仓库**
   ```bash
   git remote add origin https://github.com/你的用户名/仓库名.git
   git branch -M main
   git push -u origin main
   ```

3. **启用 GitHub Pages**
   - 按照方法一的第 3 步操作

## 访问网站

发布成功后，你的网站地址将是：
- `https://你的用户名.github.io/仓库名`

例如：`https://mayday27149-code.github.io/trip-wuhan-yichang-2025-11`

## 更新网站

每次修改文件后，只需：

```bash
git add .
git commit -m "更新内容描述"
git push
```

GitHub Pages 会自动更新（通常需要 1-2 分钟）。

## 注意事项

- 确保所有图片路径使用相对路径（如 `assets/image.jpg`）
- 如果网站无法正常显示，检查浏览器控制台是否有错误
- GitHub Pages 支持 HTML、CSS、JavaScript，但不支持服务器端语言（如 PHP）

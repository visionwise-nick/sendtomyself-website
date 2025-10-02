# GitHub Pages 设置指南

## 启用 GitHub Pages

1. 访问您的 GitHub 仓库：https://github.com/visionwise-nick/sendtomyself-website

2. 点击仓库页面顶部的 "Settings" 选项卡

3. 在左侧菜单中，向下滚动找到 "Pages" 选项

4. 在 "Source" 部分：
   - 选择 "Deploy from a branch"
   - 在 "Branch" 下拉菜单中选择 "main"
   - 在 "Folder" 下拉菜单中选择 "/ (root)"

5. 点击 "Save" 按钮

6. 等待几分钟，GitHub Pages 将自动部署您的网站

## 访问您的网站

部署完成后，您的网站将在以下地址可用：
- **主要地址**: https://visionwise-nick.github.io/sendtomyself-website/
- **备用地址**: https://sendtomyself-website.pages.dev/

## 更新网站

每次您推送更改到 main 分支时，GitHub Pages 会自动重新部署网站。

## 自定义域名（可选）

如果您有自己的域名，可以在 GitHub Pages 设置中配置自定义域名。

## 文件结构

```
sendtomyself-website/
├── index.html          # 主页
├── privacy.html        # 隐私政策
├── terms.html          # 服务条款
├── downloads/          # 下载文件
│   ├── windows-portable.zip
│   ├── macos-app.zip
│   └── linux-bundle.zip
└── README.md
```

## 注意事项

- 确保所有文件都正确推送到 main 分支
- 下载文件较大，可能需要使用 Git LFS 来管理大文件
- 网站部署通常需要几分钟时间

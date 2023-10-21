<img align="right" width="150" alt="logo" src="https://user-images.githubusercontent.com/5889006/190859553-5b229b4f-c476-4cbd-928f-890f5265ca4c.png">

# Blog.Seayay.top

这是一个使用 [Hugo theme Stack](https://github.com/CaiJimmy/hugo-theme-stack) 主题的博客站点. 它使用了 [Hugo modules](https://gohugo.io/hugo-modules/) 以加载主题.

它具有基本的主题结构和配置. GitHub Actions 将自动把主题部署到 GitHub Pages. 另外, 还有一个 Cron 任务每天自动更新主题.

## 开始使用

1. 点击 *Use this template*, 然后创建你的 GitHub 存储库.
![Step 1](https://user-images.githubusercontent.com/5889006/156916624-20b2a784-f3a9-4718-aa5f-ce2a436b241f.png)

2. 创建存储库后, 创建与其关联的 GitHub 代码空间.
![Create codespace](https://user-images.githubusercontent.com/5889006/156916672-43b7b6e9-4ffb-4704-b4ba-d5ca40ffcae7.png)

3. 瞧! 你已完成准备工作. 代码空间已配置了最新版本的 Hugo 扩展, 只需在终端中运行 `hugo server` 即可看到您的新站点正在运行.

4. 检查 `config` 文件夹中的配置文件. 您可以编辑它们以满足您的需要. 确保将 `config/_default/config.toml` 中的 `baseurl` 属性更新为您网站的 URL.

5. 完成网站编辑后, 只需提交并推送即可. GitHub Actions 会将站点自动部署到与存储库关联的 GitHub Pages.
![GitHub action](https://user-images.githubusercontent.com/5889006/156916881-90b8bb9b-1925-4e60-9d7a-8026cda729bf.png)

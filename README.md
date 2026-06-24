# 桂林四日游静态网页

这是一个可直接部署到 GitHub Pages 的静态网页项目，内容为桂林 / 阳朔 4 天 3 晚旅行规划。

## 发布结构

- `docs/index.html`
  GitHub Pages 发布入口。
- `index.html`
  当前编辑中的主页面文件。

## GitHub Pages 部署

1. 把项目推送到 GitHub 仓库。
2. 打开仓库的 `Settings` -> `Pages`。
3. 在 `Build and deployment` 中选择 `Deploy from a branch`。
4. 分支选择 `main`，目录选择 `/docs`。
5. 保存后等待 GitHub 生成公开链接。

## 说明

- 这个项目是纯静态页面，不需要安装依赖或运行构建命令。
- 如果后续继续修改页面，记得同步更新 `index.html` 和 `docs/index.html`。

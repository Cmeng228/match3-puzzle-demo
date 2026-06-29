# 三消解谜 Demo

一个可以直接部署到 GitHub Pages 的静态三消解谜小游戏。

## 在线部署

仓库根目录已经包含入口文件 `index.html`，不需要构建步骤。

GitHub Pages 设置：

1. 打开仓库的 `Settings`
2. 进入 `Pages`
3. `Source` 选择 `Deploy from a branch`
4. `Branch` 选择 `main`，目录选择 `/root`
5. 保存后等待 GitHub 生成访问链接

## 本地预览

可以直接双击打开 `index.html`，也可以用任意静态服务器预览：

```bash
python -m http.server 8000
```

然后访问 `http://localhost:8000`。

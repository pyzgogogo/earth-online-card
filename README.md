# 地球 ONLINE · 全息闪卡

独立静态网页，保留人物视差、全息镭射、翻面、自动旋转和图片保存功能。页面所需的 Three.js 模块、模型和贴图均已附带，无需在线 CDN 或构建步骤。

## 发布到 GitHub Pages

1. 在 GitHub 账号 `pyzgogogo` 下创建公开仓库 `earth-online-card`。
2. 将本目录中的全部文件和文件夹上传到仓库的 `main` 分支根目录；应直接看到 `index.html`、`app.js`、`style.css`、`card-config.json`、`.nojekyll`、`assets/` 和 `vendor/`。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中，将 **Source** 设为 **Deploy from a branch**，将 **Branch** 设为 `main`，目录选择 `/(root)`，然后保存。
5. 等待发布完成，使用 Pages 页面显示的网站链接。本项目地址为 `https://pyzgogogo.github.io/earth-online-card/`。

上传 ZIP 时须先解压，再上传其内部文件；不要只把 ZIP 文件本身放入仓库。ZIP 内没有额外的外层目录。

## 操作

- 鼠标或手指拖动卡片即可改变角度。
- 使用按钮自动旋转、查看背面、复位或保存图片。
- 下方滑块可调节镭射强度与人物、背景的视差。

## 本地预览

在本目录运行 `python -m http.server 4173`，再访问 `http://127.0.0.1:4173/`。网页使用模块和本地资源请求，应通过 HTTP 服务预览。

此分享包仅包含已生成的卡片素材和网页资源，不含原始人物照片或 Blender 工程。

Three.js 的许可文件位于 `vendor/three/LICENSE`。

网页查看器基于 [Holo Card Studio](https://github.com/EverettFish/holo-card-studio)，其 MIT 软件许可保留在 `LICENSE-HOLO-CARD-STUDIO`。人物参考照片及生成的卡面素材不在该软件许可范围内。

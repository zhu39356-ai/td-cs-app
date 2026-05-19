# 台达客服部｜内部协作台

这是一个网页版内部 App / PWA 原型，可上传到 GitHub Pages 后用手机加入主画面。

## 文件说明

- `index.html`：App 主页面
- `manifest.json`：PWA 设置，控制手机桌面名称、图标、显示模式
- `sw.js`：离线快取设置，让页面更像 App
- `icons/`：手机桌面图标

## GitHub Pages 上传方式

1. 新建一个 GitHub 仓库。
2. 把本资料夹里面的所有文件上传到仓库根目录。
3. 到仓库 Settings → Pages。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`。
6. 等待 GitHub 生成网址。
7. 用手机打开 GitHub Pages 网址。

## iPhone 加到主画面

Safari 打开网址 → 分享 → 加入主画面。

## Android 加到主画面

Chrome 打开网址 → 右上角菜单 → 加到主画面 / 安装应用程式。

## 注意

这是 PWA / 网页 App，不是 App Store / Google Play 上架的原生 App。
正式使用时建议用 HTTPS 网页环境，例如 GitHub Pages。

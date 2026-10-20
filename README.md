# 飞星Z工作室主页

独立的静态网站，无需安装依赖或构建。双击 `index.html` 即可打开；移动或发布时保留整个文件夹的相对目录结构。

## 内容

- `index.html`：工作室简介、《字中形》TapTap 入口和联系邮箱。
- `styles.css`：独立的网站样式，包含手机适配。
- `assets/`：工作室 Logo 和游戏图标。
- `privacy/`：从当前项目复制的《字中形》隐私政策与样式。

工作室 Logo 沿用用户提供的图片，图片内英文为 FEIXING Z STUDIO，网页品牌使用 Feixing Z Games。联系邮箱沿用当前游戏公开政策中的 `yangyige@buaa.edu.cn`。

## 发布到 GitHub Pages

1. 将本文件夹内的文件上传到目标仓库根目录，使 `index.html` 位于仓库根目录。
2. 在仓库 Settings → Pages 中，选择 Deploy from a branch，分支选择 `main`，目录选择 `/ (root)`，保存。
3. 等待部署完成，使用 Pages 页面显示的实际网址填写厂商网址。

用户名或组织名对应的主站仓库应命名为 `用户名.github.io`，网址为 `https://用户名.github.io/`；普通项目仓库的网址为 `https://用户名.github.io/仓库名/`。本网站全部本地资源均使用相对路径，两种形式均可使用。

## 后续修改

工作室文案、游戏链接和邮箱直接修改 `index.html`。图片可替换 `assets/` 下的同名文件。隐私政策是独立副本，原项目政策更新后需同步到 `privacy/index.html`，并保留其样式文件。

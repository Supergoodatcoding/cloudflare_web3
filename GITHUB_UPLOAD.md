# 手动上传到 GitHub

这个文件夹已经整理成 GitHub 仓库根目录结构。

需要上传的文件：

- `index.html`
- `web3_ecosystem.html`
- `README.md`
- `GITHUB_UPLOAD.md`

## GitHub 上传步骤

1. 打开 GitHub，新建一个仓库，例如 `web3-site`。
2. 进入新仓库页面。
3. 点击 `uploading an existing file`。
4. 把本文件夹里的文件拖进去，注意不要把外层文件夹本身作为子目录上传。
5. 点击 `Commit changes`。

## Cloudflare Pages 连接设置

在 Cloudflare Pages 连接这个 GitHub 仓库时：

- Framework preset：`None`
- Build command：留空
- Build output directory：`/`

部署后再到 Pages 项目的 `Custom domains` 绑定你的 Cloudflare 域名。

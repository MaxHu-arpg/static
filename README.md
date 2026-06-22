# static

用于存放网页使用的 CDN 静态资源（如 JS、CSS、图片、字体等），并通过 GitHub + jsDelivr 加速访问（含国内）。

## 使用方式

1. 直接在 GitHub 网页上传静态文件到 `/assets` 目录（可按业务自行分子目录）。
2. 上传后使用 jsDelivr 链接访问资源。

## jsDelivr 链接格式

- 最新分支文件：

  `https://cdn.jsdelivr.net/gh/MaxHu-arpg/static@main/assets/<your-file-path>`

- 指定版本（推荐生产环境）：

  `https://cdn.jsdelivr.net/gh/MaxHu-arpg/static@<tag>/assets/<your-file-path>`

## 示例

如果上传文件为：`/assets/libs/app.js`

- `https://cdn.jsdelivr.net/gh/MaxHu-arpg/static@main/assets/libs/app.js`
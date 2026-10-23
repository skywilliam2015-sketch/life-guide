# 生活选择速查手册 · 2026 科学证据版

静态网站部署包。

## 文件
- `index.html`：主页面
- `404.html`：静态托管回退页
- `.nojekyll`：GitHub Pages 兼容
- `netlify.toml`：Netlify 静态部署配置

## GitHub Pages
1. 新建一个 Public repository，例如 `life-guide`
2. 上传本目录全部文件到仓库根目录
3. Settings → Pages → Build and deployment → Deploy from a branch
4. Branch 选择 `main`，Folder 选择 `/ (root)`
5. 保存后即可获得 `https://你的用户名.github.io/life-guide/`

## Netlify
将整个文件夹拖入 Netlify Drop 即可部署。

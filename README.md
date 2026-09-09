# suvianwu.github.io

Suwan Wu（巫苏皖）的个人主页。纯静态，无构建步骤。

## 本地预览

```bash
cd site && python3 -m http.server 4000
# http://localhost:4000
```

## 部署到 GitHub Pages

1. 注册 / 登录 GitHub，用户名 `suvianwu`。
2. 新建 **public** 仓库，名字必须精确为 `suvianwu.github.io`。
3. 把本目录下的 `index.html`、`styles.css` 放到仓库根目录（不要放在子文件夹里），push 到 `main`。
4. Settings → Pages → Source 选 `Deploy from a branch`，branch `main` / `(root)`，保存。
5. 1–2 分钟后访问 https://suvianwu.github.io/

> 如果用的是普通仓库名（比如 `homepage`），网址会变成 `https://suvianwu.github.io/homepage/`，且相对路径资源需要检查。用户主页仓库更干净。

## 可选后续

- 自定义域名：仓库根加 `CNAME` 文件 + DNS 配置
- `cv.pdf` 放根目录，header 加一条链接
- Research 里的 `Work in progress` 条目替换为可公开的项目/论文链接

# 上海苏珀曼科技有限公司 · 官网（GitHub Pages）

极简官网，用于 App Store / Apple Developer：

| 页面 | App Store 字段 |
|------|----------------|
| `index.html` | Marketing URL（可选） |
| `support.html` | **Support URL** |
| `privacy.html` | **Privacy Policy URL** |

---

## 一键推到 GitHub Pages

在本机执行（把 `你的用户名` 和仓库名改成你的）：

```bash
cd /Users/wittamer/Documents/AIFridge/demo/03_ios_version/AIFridge-main/site

# 若还没有远程仓库：先在 GitHub 新建 Public 仓库 aifridge-site
git init
git add .
git commit -m "Add 上海苏珀曼科技官网 for App Store"
git branch -M main
git remote add origin https://github.com/你的用户名/aifridge-site.git
git push -u origin main
```

然后：仓库 → **Settings → Pages** → Source：`main` / root → Save。

约 1～2 分钟后访问：

```text
https://你的用户名.github.io/aifridge-site/
https://你的用户名.github.io/aifridge-site/support.html
https://你的用户名.github.io/aifridge-site/privacy.html
```

---

## 上线前请修改

1. 三个页面里的邮箱 `support@aifridge.shop` → 真实可收信邮箱  
2. 本地预览：`python3 -m http.server 8080` 后打开 http://127.0.0.1:8080  

公司全称已统一为：**上海苏珀曼科技有限公司**。

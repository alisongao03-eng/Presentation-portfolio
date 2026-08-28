# Alison Gao · Presentation Portfolio

金黄 × 墨色调的个人简报作品集网站（静态页面，可直接托管于 GitHub Pages）。

## 目录结构

```
├── index.html            # 作品集主页
├── assets/               # 艺术视觉素材（主视觉、纹理）
└── covers/               # 各套简报封面图（deck-01 ~ deck-06）
```

## 部署到 GitHub Pages

1. 在 GitHub 新建仓库（如 `presentation-portfolio`），Public
2. 将本文件夹全部内容上传到仓库根目录（网页端直接拖拽即可）
3. 进入仓库 **Settings → Pages**，Source 选择 `Deploy from a branch`，Branch 选 `main` / `(root)`，保存
4. 约 1 分钟后，网站上线于 `https://<你的用户名>.github.io/presentation-portfolio/`

## 替换为你的真实作品

- 将每套 PPT 导出的封面图替换 `covers/deck-XX.png`（建议 1280×720）
- 在 `index.html` 中修改各卡片的标题、页数、年份
- 将「在线浏览」「下载 PDF」的 `href="#"` 改为实际链接（如 `decks/ai-strategy.pdf`）

# 产品与能力展示页（对外）

**这是专门给客户 / 外部访问者看的页面，与本地项目盘点看板完全分离。**

- 从零新建，不基于 `项目整理清单.html`；不含本地路径、本地端口、review/archive/delete 处置标签、成本信息、私有仓库链接。
- 只保留：项目名、能力描述、技术标签、可公开访问的在线链接与公开源码链接。
- 单文件自包含（内联 CSS/JS，无外部 CDN 依赖），可直接托管于 Cloudflare Pages / GitHub Pages。
- 支持分类筛选与关键词搜索，移动端自适应。

## 部署

- Cloudflare Pages：`../deploy.sh`（需 `~/.cloudflare.env` 中的 API Token）。
- GitHub Pages：仓库 Settings → Pages → 从 `main` 分支根目录部署。

内容源以 GitHub 仓库为准；本地 `项目整理清单.html` 仅作为私有备份，不对外发布。

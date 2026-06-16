# 清风伴端午 廉洁过佳节 — H5 页面

贵州联合化工集团有限公司纪委 · 2026 端午廉洁提醒

## 修复说明

- 已将静态资源路径从 `/assets/...` 改为 `./assets/...`，适配 GitHub Pages 项目站点。
- 已将背景音乐路径从 `/bgm.mp3` 改为 `./bgm.mp3`。
- 已删除 Skywork 的 embed、badge、track 外链脚本，页面右下角不会再出现 `Edit with Skywork` 标识。
- 已本地验证 H5 主流程：封面、提醒、六禁、测试、五彩绳、承诺弹窗均可点击进入。

## GitHub Pages 部署步骤

1. 新建一个 GitHub 仓库（建议设为 Public）
2. 将本文件夹内所有文件上传到仓库 **根目录**，不要漏传 `assets/` 和 `bgm.mp3`
3. 进入仓库 → Settings → Pages
4. Source 选择 **Deploy from a branch**，Branch 选 `main`，目录选 `/ (root)`
5. 保存后等待约 1 分钟，即可获得访问链接：
   `https://<你的用户名>.github.io/<仓库名>/`

## 文件说明

| 文件 | 说明 |
|------|------|
| index.html | H5 页面入口 |
| assets/ | CSS + JS 资源 |
| bgm.mp3 | 端午背景音乐 |
| .nojekyll | GitHub Pages 必需文件 |

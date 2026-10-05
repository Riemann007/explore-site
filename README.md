# 三个人，三种问法

给初中生的一页：苏格拉底、柏拉图、亚里士多德。

| 页面 | 文件 | 说明 |
| --- | --- | --- |
| **线上版**（推荐） | [`index.html`](index.html) | 图片外链 + `srcset` + WebP + 屏外跳过渲染，**手机端最快** |
| 单文件图文版 | [`socrates-plato-aristotle-illustrated.html`](socrates-plato-aristotle-illustrated.html) | 六图内联，**可下载离线看**（960 KB） |
| 单文件轻量版 | [`socrates-plato-aristotle.html`](socrates-plato-aristotle.html) | 纯矢量，无位图（73 KB） |
| 分享卡 | [`share-card.png`](share-card.png) | 2400×1260 |

线上版与单文件版**内容完全一致**，只是图片的承载方式不同：线上版让手机只下载当前需要的图片，
单文件版把图片全内联以便离线与转发。两者都由 `build-site-fast.py` / `build-illustrated.py` 从同一份源生成。

- 三个页面都是**零外部依赖**：不联网也能读，不加载任何第三方字体、脚本或图片。
- 内容纪律：每处史实标了等级（史料 / 传说 / 类比）；插图为 AI 生成的想象场景，非史料。
- 校验和见 [`SHA256SUMS.txt`](SHA256SUMS.txt)。

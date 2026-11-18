# wanzi-costume-pics

丸子 AI 绘图 / AI 换装的服装参考图集，供 `wanzi-homepage` 与 `wanziwk-29` 共用。

## 内容

- `costumes.json`：1407 条服装数据（中文标签 + 英文关键词 + 检索词元）
- `img/{ID}.webp`：高清原图
- `thumbs/{ID}.webp`：缩略图

编号前缀：`SPR` 春、`SUM` 夏、`AUT` 秋、`WIN` 冬、`PTY` 派对、`LNG` 内衣睡衣、`SWM` 泳装度假、`SXY` 性感。

`costumes.json` 里的 `thumb` / `img` 是 jsDelivr 绝对地址，前端直接使用；`nsfw: true` 的分类（内衣睡衣、泳装度假、性感）默认不展示，由各项目自行过滤。

## 使用

```
https://cdn.jsdelivr.net/gh/wanziwk/wanzi-costume-pics@main/costumes.json
https://cdn.jsdelivr.net/gh/wanziwk/wanzi-costume-pics@main/img/SPR-0001.webp
https://cdn.jsdelivr.net/gh/wanziwk/wanzi-costume-pics@main/thumbs/SPR-0001.webp
```

## 来源与版权

服装图与元数据来自 [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh)（原图作者 ギア 等）。本仓库仅做镜像与结构整理，图片版权归原作者，禁止打包倒卖。

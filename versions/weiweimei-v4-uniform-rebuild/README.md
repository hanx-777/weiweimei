# 维什戴尔·维维美 Codex 桌面宠物（统一尺寸重建版）

这是 Codex v2 animated pet 包，保留 `weiweimei` ID、9 个标准动作、16 个朝向和 8×11 图集接口。

本版从仓库原始 GIF 重新提取，不在旧图集上继续放大。以 `relax.gif` 的主体高度作为统一尺度，所有动作共用同一缩放基准、水平中心和脚底锚点；重采样采用透明度感知的 Lanczos，并做轻度锐化以减少边缘发软。

## 文件

- `pet.json`：Codex v2 宠物元数据
- `spritesheet.webp`：无损 RGBA 主图集，`1536×2288`
- `spritesheet.png`：PNG 备份
- `preview-contact-sheet.png`：动作与朝向总览
- `preview-look-directions.png`：16 个朝向预览
- `registration-manifest.json`：统一尺寸、缩放和基线记录
- `validation.json`：Codex v2 图集验证结果

## 素材来源

动作和角色素材主要来自 [OTAXIO/digit_maid 的维什戴尔皮肤素材](https://github.com/OTAXIO/digit_maid/tree/main/resource/wisdel/%E7%9A%AE%E8%82%A4%E7%B4%A0%E6%9D%90)。

# 维什戴尔·维维美 Codex 桌面宠物（2×清晰度增强版）

这是 Codex v2 animated pet 包，保留原有 `weiweimei` ID、动作分配和 8×11 图集规格。

本版仅对原始 GIF 帧做清晰度处理：先以 2×目标尺寸进行高质量重采样，再缩回 `192×208` 单格，并施加轻度 UnsharpMask（半径 0.55、强度 90、阈值 3）。透明通道、动作顺序、镜像方向和注册点保持不变。

## 文件

- `pet.json`：Codex v2 宠物元数据
- `spritesheet.webp`：无损 RGBA 主图集，`1536×2288`
- `spritesheet.png`：PNG 备份
- `preview-contact-sheet.png`：11 行图集总览
- `preview-look-directions.png`：16 个朝向预览
- `resampling-report.json`：本版处理参数与验证结果

## 素材来源

动作和角色分层素材主要来自 [OTAXIO/digit_maid 的维什戴尔皮肤素材](https://github.com/OTAXIO/digit_maid/tree/main/resource/wisdel/%E7%9A%AE%E8%82%A4%E7%B4%A0%E6%9D%90)。

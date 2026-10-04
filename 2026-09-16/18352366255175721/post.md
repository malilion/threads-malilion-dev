# 如果遊戲技能不是按 Q，而是真的伸手施法呢？

- 時間：2026-09-16 15:24:33（Asia/Taipei）
- 貼文 ID：`18352366255175721`
- 類型：貼文
- 永久連結：匯出檔未提供

如果遊戲技能不是按 Q，而是真的伸手施法呢？

最近看到一個很狂的 Three.js 專案：HandCastAbilityThreeJS / Elemental Sandbox。

它用 Three.js + Vite + 手寫 GLSL 做了一套完整的技能 VFX Sandbox，目前有：
－9 種技能
－3 種瞄準方式
－1,758 個可即時調整的參數
－大量 Procedural Geometry / Shader 特效。

技能也不是普通「光球飛出去」。
像是：
🧊 Glacial Prison
直接把角色凍成冰雕，最後碎成 40 塊冰片，掉到地上再慢慢融化。
💚 Toxic Shield
地板先裂開，升起毒性玻璃結界，裡面的角色會逐漸「玻璃化」，最後整個碎掉。
🔥 Serpent Tide Field
從火堆召喚一隻 Phoenix，會主動獵殺目標，遠距離噴 Fireball、近距離直接用爪子攻擊。
🤖 還能召喚 Monowheel Bot 等機械單位。
而且很多效果不是 Sprite 貼圖假裝出來的。

## 媒體

- [18121108240713130.jpg](./18121108240713130.jpg)
- [18352366255175721.mp4](./18352366255175721.mp4)

# 如果 Blender 的 Geometry Nodes，不只是在 Blender 裡跑呢？

- 時間：2026-10-01 08:13:10（Asia/Taipei）
- 貼文 ID：`18422718589154956`
- 類型：貼文
- 永久連結：匯出檔未提供

如果 Blender 的 Geometry Nodes，不只是在 Blender 裡跑呢？

最近看到一個很猛的 Three.js 專案
🏙️ ProceduralBuildingsThreeJS

它直接把 Blender 裡的 Procedural Building 系統搬到瀏覽器

而且不是「照著結果重寫一個差不多的版本」

其中紐約與中國建築甚至是：

把 Blender Geometry Nodes Graph 匯出，再直接由瀏覽器執行

目前有三種主要建築：

🇫🇷 巴黎 Haussmann 風公寓 
🇺🇸 紐約戰前 Corner Building 
🇨🇳 中式街角住宅＋商店

你可以即時調整：

樓層數 
建築寬度與深度 
陽台 
窗戶 
商店 
冷氣 
消防梯 
然後整棟建築會直接重新生成

把 Blender 的：
Geometry Nodes 
↓ 
Geometry / Instances 
↓ 
Material Node Graph 
↓ 
GLSL Shader 
↓ 
Three.js

整套流程搬進 Web。

## 媒體

- [17945940438302019.mp4](./17945940438302019.mp4)
- [18422718589154956.jpg](./18422718589154956.jpg)

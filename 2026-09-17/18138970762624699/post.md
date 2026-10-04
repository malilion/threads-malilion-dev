# 如果你也想做「動畫風」Web 3D，但不想每次從 Shader 重新刻，這個 Repo 很值得收。

- 時間：2026-09-17 21:25:48（Asia/Taipei）
- 貼文 ID：`18138970762624699`
- 類型：貼文
- 永久連結：匯出檔未提供

如果你也想做「動畫風」Web 3D，但不想每次從 Shader 重新刻，這個 Repo 很值得收。

最近看到一個很漂亮的開源專案：Stylized Components。

它是一套用 Next.js + Three.js + React Three Fiber + 自訂 GLSL做的即時 Stylized Rendering 元件庫。

目前最吸睛的是兩套系統：

🌊 Anime Water
不是單純透明水面，而是把：
－Cel Shading
－Voronoi 水紋
－Ripple
－水深交界線
－GPU Wave Simulation
－Procedural Sparkles
整套組在一起。
物件碰到水面時，還會真的產生波紋。

🌿 Stylized Grass
則用 Instancing 生成大量草和花，再加入：
－風吹動畫
－泥土地形混合
－踩踏效果
－背光 Translucency
－每根草自己的 Shadow 判定
－Spring / Autumn 等季節 Preset
甚至石頭壓到草時，不只是把草「縮短」，而是會把草壓平並往外倒，讓它更像真的被踩過。

## 媒體

- [18113727892823869.mp4](./18113727892823869.mp4)
- [18138970762624699.jpg](./18138970762624699.jpg)
- [18184485040413491.mp4](./18184485040413491.mp4)

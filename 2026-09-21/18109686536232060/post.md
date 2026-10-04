# 如果作品集不要再做成 Grid，而是直接做成一整排可以拿下來翻的 3D 精裝書呢？

- 時間：2026-09-21 10:50:20（Asia/Taipei）
- 貼文 ID：`18109686536232060`
- 類型：貼文
- 永久連結：匯出檔未提供

如果作品集不要再做成 Grid，而是直接做成一整排可以拿下來翻的 3D 精裝書呢？
最近看到 Meng To 的一個很漂亮的 Three.js 專案：The Complete Shelf

它把 7 本布面精裝書做成一個真的可以互動的 3D 書架：
－滑動瀏覽整排書
－把書從架上抽出來
－360° 查看裝幀
－Hover 可以微微打開封面
－點擊後正式開書
－甚至可以拖曳翻動有弧度的頁面

布料、紙張、木頭、燙金、粗糙度與 Normal 等 Texture 很多都是 Procedural 生成

最誇張的是：

整個體驗幾乎都塞在一個 `index.html` 裡

Markup、Shader、Material、3D Geometry、動畫、互動 State、圖片 Atlas，甚至 Audio 都包在裡面。

沒有 Framework、沒有 Bundler、沒有 Backend

底層就是：

Three.js + PBR Material + OrbitControls + State Machine

## 媒體

- [18109686536232060.jpg](./18109686536232060.jpg)

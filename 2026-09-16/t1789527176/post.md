# 結果也滿猛： Google 表示，把能力蒸餾進 Diffusion Retriever 後

- 時間：2026-09-16 10:52:56（Asia/Taipei）
- 貼文 ID：`t1789527176`
- 類型：回覆
- 回覆對象：@malilion.dev
- 永久連結：匯出檔未提供

結果也滿猛： Google 表示，把能力蒸餾進 Diffusion Retriever 後
⚡ 推理速度約提升 12～20 倍 而且在大型 Context Batch 下
傳統 Autoregressive Fan-out 可能接近 50 秒， Retrieve-for-Train 則維持在： 
不到 1 秒～數秒的範圍。 
我覺得這篇最值得注意的不只是 Search。 而是背後這個方向： 不要把所有智慧都留到 Inference Time。 
以前： Query ➡️LLM 大量思考 ➡️搜尋 ➡️結果 現在可能變成： Offline RL ➡️把「怎麼思考」學起來 ➡️ Distillation ➡️ 小模型快速執行 也就是： Train expensive, infer cheap. 
未來很多 Agent / RAG / Recommendation System， 可能都會開始往這個方向走。 不是讓模型每次都「想更久」， 而是讓它： 在部署前，就學會怎麼想。

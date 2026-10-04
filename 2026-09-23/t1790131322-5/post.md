# 另一個很有意思的測試： Anthropic 讓 Opus 5.5 和 Fable 5.1 把： HAProxy 從 C 改寫成 Rust兩邊最後都通過幾乎所有 …

- 時間：2026-09-23 10:42:02（Asia/Taipei）
- 貼文 ID：`t1790131322-5`
- 類型：回覆
- 回覆對象：@malilion.dev
- 永久連結：匯出檔未提供

另一個很有意思的測試： Anthropic 讓 Opus 5.5 和 Fable 5.1 把： HAProxy 從 C 改寫成 Rust兩邊最後都通過幾乎所有 Regression Tests。
 但是： Fable 5.1：12 小時 Opus 5.5：9.5 小時 而且 Opus 5.5： 成本低了 51%。
 這就滿符合這次的主題： 不是單純把模型做得更大， 而是： 讓 Agent 用更少 Tokens、更少 Steps，把大型工作完成。
Terminal-Bench 4.0 Opus 5.5：66.4% Opus 5：52.3% FrontierCode： Opus 5.5：54.4% Opus 5：48.0% CursorBench 4.0： Opus 5.5：57.8% Opus 5：46.6%

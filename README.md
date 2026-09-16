# Enterprise AI Adoption Gap, Barriers & ROI

中英雙語簡報：瑞銀 Evidence Lab 企業 AI 落地落差、六大障礙、ROI 量測與長期追蹤。

Live: https://ming050823.github.io/ai-roi-briefing/
Repo: https://github.com/Ming050823/ai-roi-briefing

## 為什麼會看到 Error: 404

GitHub Pages **已經有開**，根目錄的 `index.html` 也存在。目前這個 `index.html` 是 loader，會再去拉 `data/a.txt` 與 `data/b.txt`。這兩個檔還沒上傳完，瀏覽器就會顯示 404 / unable to expand。

## 一分鐘修法（推薦，一定有效）

1. 打開：https://github.com/Ming050823/ai-roi-briefing/upload/main
2. 把完整報告 HTML 改名為 **`index.html`**，拖進頁面（覆蓋舊的 loader）
3. Commit to `main`
4. 等 30–60 秒，強制整理打開 https://ming050823.github.io/ai-roi-briefing/

不要再用拆檔 loader。把完整 HTML 直接當 `index.html` 就行。

## Pages 設定

Settings → Pages → Source = Deploy from a branch → `main` / `/ (root)`
https://github.com/Ming050823/ai-roi-briefing/settings/pages

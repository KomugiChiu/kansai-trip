# 關西・山陽・四國 8 日旅程

2026/11/28 – 2026/12/05 的關西旅行行程頁面，以日系簡約風格呈現，包含每日分頁籤與時間軸卡片。

- 行程路線：神戶 → 姬路 → 赤穗溫泉 → 倉敷 → 高松
- 頁面為單一 `index.html`，所有 CSS / JS / SVG 圖示皆內嵌，不依賴任何 CDN、外部字型或圖片，可離線開啟。
- 本頁為行程靜態展示頁，依個人行程備忘整理。

## 檔案

| 檔案 | 說明 |
| --- | --- |
| `index.html` | 行程頁面（自包含靜態網頁） |
| `README.md` | 專案說明與發佈方式 |

## 本機預覽

直接以瀏覽器開啟 `index.html` 即可；或啟動一個簡單的靜態伺服器：

```bash
python3 -m http.server 8000
# 開啟 http://localhost:8000
```

## 發佈到 GitHub Pages

1. 在 GitHub 建立新的 repository，並將本專案推送上去：

   ```bash
   git remote add origin https://github.com/<your-account>/<repo-name>.git
   git branch -M main
   git push -u origin main
   ```

   若已安裝 [GitHub CLI](https://cli.github.com/)，也可以直接建立 repo 並推送：

   ```bash
   gh repo create <repo-name> --public --source=. --remote=origin --push
   ```

2. 回到 GitHub repository 頁面，進入 **Settings → Pages**。
3. 在 **Build and deployment** 中，將 **Source** 選為 **Deploy from a branch**。
4. **Branch** 選擇 `main`、資料夾選擇 `/ (root)`，按下 **Save**。
5. 稍等片刻，頁面會發佈於 `https://<your-account>.github.io/<repo-name>/`。

## 備註

- 行程時間與停留長度依原始行程備忘整理呈現，實際狀況請以現場為準。
- 頁面建立於 2026 年 11 月。

# GitHub Pages 發布步驟

這個 `site` 資料夾裡的檔案可以直接放到 GitHub Pages。

## 最簡單做法

1. 到 GitHub 建立一個新的 repository，例如 `bubble-echo`。
2. 把 `site` 資料夾裡的檔案上傳到 repository 根目錄：
   - `.nojekyll`
   - `index.html`
   - `chapter-01.html`
   - `site.css`
3. 到 repository 的 `Settings`。
4. 進入 `Pages`。
5. 在 `Build and deployment` 選擇：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. 儲存後等待 1 到 3 分鐘。
7. GitHub 會產生公開網址，格式通常像：
   `https://你的帳號.github.io/bubble-echo/`

## 後續新增章節

新增章節時，可以複製 `chapter-01.html`，改成 `chapter-02.html`，再把首頁的章節列表加上一筆連結。
Deployment refresh.

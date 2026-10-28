# Vegetables 網頁排版作業

本專案依照你提供的課堂圖片，重新撰寫 HTML、CSS 與英文介紹文字。

## 開啟網頁

解壓縮後，直接以瀏覽器開啟 index.html 即可。CSS、照片與字型皆採相對路徑並已附在專案內，不需要安裝套件。

- index.html：網頁結構與內容。
- css/style.css：獨立樣式檔，含中文註解與手機排版。
- img/：南瓜主視覺、三張蔬菜照片與社群圖示。
- fonts/：Noto Sans 字型及授權文件。

請保留所有子資料夾的位置，勿只上傳 index.html。

## 本次修改

1. 原本左下三張圖片，各自增加獨立文字欄，包含名稱、介紹與料理小提示。
2. 右下 Contact 增加四段介紹與聯絡資訊，內容使用自然換行，不固定文字區高度。
3. 維持教材色彩：Primary #778A50、Background #EDF2C5、Text #7D7D7D、Content #F7FBDA。
4. 字型為 Noto Sans；桌機內容寬度為 1120px，左右欄各 528px，中間 64px。
5. 導覽列可跳到對應段落；社群圖片與 LOGIN / JOIN 僅為版型示意，無帳號系統。
6. 聯絡方式為作業示意，不是真實商家。

## Figma 部分（必須在自己的帳號內完成）

目前提供的是參考圖片，並不是可編輯的 Figma 文件連結。本專案不會自動建立或修改你的 Figma 文件。

1. 開啟老師的 Figma 教材，複製至自己的草稿（Duplicate to your drafts），在自己的副本編輯。
2. 保留 Logo、導覽列、大圖與兩欄標題。
3. 左下圖片順序改為 Carrots、Sweet Corn、Bell Peppers。
4. 在三張圖下方新增淺色矩形 #F7FBDA，再加文字。文字可直接由 index.html 複製。
5. 右下 Contact 貼上 index.html 內對應的四段介紹，增加文字框與背景高度，避免文字被裁掉。
6. 頁尾移到內容下方，四周保留適當留白。
7. 使用 Share / 分享，將連結存取設定為老師可開啟且角色為 Can view / 僅供檢視，再複製設計文件連結。

不要把截圖或本機 HTML 路徑當作 Figma 設計稿 URL。

## GitHub 與 GitHub Pages

1. 在自己的 GitHub 帳號建立專門的作業 repository（例如 vegetables-homework）。
2. 將本專案內的 index.html、css、img、fonts 及 README.md 上傳到 repository 根目錄，提交變更。
3. Settings → Pages → Build and deployment → Source 選 Deploy from a branch。
4. Branch 選 main（或實際預設分支）、資料夾選 / (root)，按 Save。
5. 等待部署完成後，使用 Pages 頁面實際顯示的 Visit site 網址，不要自行猜網址。
6. 開啟網站確認照片與排版正常，再填寫表單。

## 表單需繳交三個不同網址

- Figma 設計稿 URL：你自己的 Figma 文件，可供老師檢視。
- GitHub 程式碼 URL：你的作業 repository 首頁。
- GitHub Pages URL：已發布、可直接觀看網頁的網址。

## 圖片與字型來源

照片及社群圖示為與課堂畫面相同的教材素材，取自公開存放這組素材的 repository；本專案未採用該 repository 的 HTML 或 CSS。
https://github.com/s110719001/Vscode-homework

如老師提供原始圖片，亦可將同名素材替換為老師的檔案。

Noto Sans 來自 Google Fonts，使用 SIL Open Font License，見 fonts/OFL.txt。
https://github.com/google/fonts/tree/main/ofl/notosans

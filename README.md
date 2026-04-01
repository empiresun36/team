# ☀️ 太陽帝國社區・管委會競選網站

余盈賢・梁哲嘉・方冠凱・游子瑩・朱真瑩 五人競選團隊

---

## 🚀 上傳到 GitHub Pages（5 分鐘完成）

### Step 1：建立 GitHub 帳號
前往 https://github.com 免費註冊

### Step 2：新增 Repository
1. 右上角 **＋** → **New repository**
2. Repository name：`taiyangdiguo`（或任何名稱）
3. 選 **Public**
4. 勾選 **Add a README file**
5. 點 **Create repository**

### Step 3：上傳 index.html
1. 點 **Add file** → **Upload files**
2. 拖入 `index.html`
3. 點 **Commit changes**

### Step 4：啟用 Pages
1. 點 **Settings** → 左側 **Pages**
2. Source → **Deploy from a branch**
3. Branch → **main** / **root**
4. 點 **Save**

### Step 5：取得網址
約 2 分鐘後，網址為：
```
https://你的帳號.github.io/taiyangdiguo
```
把這個網址轉成 QR Code 印在傳單上！

---

## 📝 串接 Google 表單

### 建立兩份表單

**表單一：社區滿意度問卷**
建議題目：
- 整體滿意度（1-5 星）
- 最需改善項目（多選）
- 各項目滿意度（安全/清潔/公設/溝通）
- 開放意見

**表單二：向候選人提問**
建議題目：
- 您的問題（段落）
- 問題類別（安全/財務/公設/活動/其他）
- 匿名暱稱（選填）

### 取得嵌入網址
1. 表單右上角 **傳送（Send）**
2. 點 **嵌入 `<>`** 圖示
3. 複製 `src="..."` 裡的網址

### 貼入 index.html
用記事本開啟 index.html，找到並替換：

```
REPLACE_SURVEY_FORM_ID  →  你的滿意度問卷 src
REPLACE_QA_FORM_ID      →  你的提問表單 src
```

重新上傳 index.html 即可。

### 查看回覆
Google 表單 → **回覆** 標籤 → **試算表圖示**
所有回答自動存入 Google Sheets，可篩選與統計。

---

## ✏️ 修改候選人資料

用「搜尋」功能找到對應文字直接修改即可，不需要懂程式。

| 想改的 | 搜尋 |
|--------|------|
| 余盈賢資料 | `余盈賢` |
| 梁哲嘉資料 | `梁哲嘉` |
| 方冠凱資料 | `方冠凱` |
| 游子瑩資料 | `游子瑩` |
| 朱真瑩資料 | `朱真瑩` |
| 投票日倒數 | `2025-04-11` |

---

## 💡 選戰加分策略

1. **QR Code 傳單**：網址轉 QR Code（qr-code-generator.com），印在 A4 傳單上貼公告欄
2. **填問卷換禮品**：問卷截圖換小禮品，大幅提升填答率
3. **每週公告數字**：在住戶 LINE 群組每週公告「已有 XX 人填問卷」，製造聲勢
4. **倒數提醒**：投票前 3 天在 LINE 群組貼倒數截圖

---

*本網站以 GitHub Pages 免費託管 · Google 表單免費收集回覆*

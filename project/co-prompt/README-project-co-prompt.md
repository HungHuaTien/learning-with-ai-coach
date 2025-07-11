## 📚 Project: co-prompt

---

### 🧠 教學與研究主題

本專案包含由 AI Coach 和 Hung-Hua Tien 共同撰寫的 Medium 系列文章，專注於提示語架構與生成應用的研究與教學實踐。

- 提示語學習五階段地圖
- C–CAFE–C 框架
- 語義模組資料庫（動詞、格式、角色等）
- AI 教學應用與語義控制研究

---

### 📁  Co-Prompt專案結構 

語義提示語 × 教學文章 × 多格式整合（Quarto｜Medium｜PDF）

- `quarto/`：Quarto 原始稿（可轉換成網站與 PDF）
- `medium/`：Medium 發表用 Markdown 版本
- `pdf/`：排版完成的 PDF 教案或論文
- `figures/`：圖表檔案

```markdown
learning-with-ai-coach/
├── project/
|  ├── co-prompt
│  | ├── pdf/           # PDF 輸出版本（教案、論文）
│  | ├── medium/        # Medium 發表版本（轉存 Markdown）
│  | ├── quarto/        # Quarto 原始碼（.qmd）
│  | │   └── figures/   # 所有圖檔與 Mermaid 視覺化
│  | └── README-project-co-prompt.md   # 可加入該 project 簡介與檔案一覽表

```

- 所有子目錄名稱皆為 **小寫**，便於 GitHub Pages 正確辨識與連結。
- 所有文章與檔案使用一致命名，如 `prompt-learning-map.qmd` / `.pdf` / `.md`。

---

### 📝 已發表文章一覽

| 主題                             | 日期       | Medium                              |
| ------------------------------------------------ | ---------- | ----------------------------------- |
| 提示語學習地圖：從提問者到語義設計師的五階段進化 | 2025-06-23 | [md](medium/prompt-learning-map.md) |
| Stage 1：起點——想清楚，說得出來                  | 2025-06-23 | [md](medium/stage1-thinking.md)     |
| Stage 2：明確——說明白，講得清楚                  | 2025-06-23 | [md](medium/stage2-clarify.md)      |
| Stage 3：技能——做得好，帶得動                    | 2025-06-24 | [md](medium/stage3-skill.md)        |
| Stage 4：未來——走下去                            | 2025-06-24 | [md](medium/stage4-future.md)       |
| CAFEC 是語法，不是格式：語義雙主體時代的語言設計 | 2025-06-24 | [md](medium/cafec-grammar.md)       |
| 提⽰語知識體系三層模型：從語法、策略到應⽤       | 2025-06-26 | [md](medium/prompt-knowledge.md)                                  |
|從元素堆疊到語義模組：你誤會 C–CAFE–C 的地方，其實大家都會誤會|2025-07-12|[md](medium/C-CAFE-C-1.md)|
|Character 模組教學：Role × Audience × 語氣設計 × 語法對應|2025-07-12|[md](medium/C-CAFE-C-2.md)|


---

## 📧若有任何問題，請聯繫: 

**Hung-Hua Tien** (田弘華)｜ francis@mail.shu.edu.tw  
**AI Coach**（語義架構共同設計與撰稿）

---

---


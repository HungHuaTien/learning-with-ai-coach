------

## title: "Pattern-to-Prompt 標註架構：語義模組的轉譯實作"  summary: "本模組說明如何將語義模組標註為機器可解析的提示語格式，並展示從語義到自然語言輸出的標準轉換流程。"  author: "Hung-Hua Tien & AI Coach"  date: 2025-07-18  categories: ["semantic-prompt-lab", "modules"]

## 為何需要 Pattern-to-Prompt 標註？

語義提示語的真正價值，不只是語言上的「直白易懂」，而是能夠讓 AI **辨識並執行**。因此，我們需要一種方式，將語義模組（如 C–CAFE–C）**轉譯為 AI 可理解的語義結構格式（Pattern）**，這就是 Pattern-to-Prompt 的設計初衷。

> 🎯 Pattern-to-Prompt 標註架構是一種語義轉譯機制，讓語言輸入成為 AI 可分析、模仿與強化學習的輸入材料。

## 基本格式設計：YAML 標註 × 自然語輸出

我們採用 `prompt.yaml` 作為主格式，分為兩層：

1. **語義模組標記（Semantic Tags）**：使用結構清楚的 key 表示語義模組（如 @Character、!Action、#Format...）
2. **自然語語句輸出（Prompt Output）**：標記與轉譯對應

### 範例 YAML 格式

```yaml
prompt: f(@ ! > # ~)
@= 你是資深記者，請協助撰寫一則新聞導語
!= 根據提供的採訪資訊，依據倒金字塔格式組織內容
>= 請使用清楚、正式、新聞語氣的文字表達
#= 倒金字塔格式（導語 > 細節 > 背景）
~= 提供一段導語的具體寫法
```

### 對應自然語輸出：

> 你是資深記者，請根據採訪資訊撰寫一段符合倒金字塔格式的新聞導語，語氣正式清楚，並提供一段具體寫法參考。

------

## C–CAFE–C 模組 × 標註元素對照

| 模組      | 符號 | 功能說明           |
| --------- | ---- | ------------------ |
| Character | @    | 任務角色與受眾設計 |
| Action    | !    | 執行步驟與操作指令 |
| Format    | #    | 結構樣式與產出格式 |
| Example   | ~    | 範例呈現與樣本要求 |
| Context   | >    | 背景情境或語氣設定 |

------

## 教學應用與學生任務設計

此模組未來可提供以下教材設計用途：

1. **空白框架填寫練習**：學生根據任務設計 YAML 語義結構
2. **語義轉譯比對任務**：讓學生比較自然語與標註語之間的落差與表達策略
3. **AI 回應強化任務**：利用標註讓 AI 對生成品質進行精細調控

------

📁 建議儲存路徑：
 `semantic-prompt-lab/modules/pattern-to-prompt/Pattern-to-Prompt.md`

📌 接續任務建議：

- 建立 `prompt.yaml` 標註練習檔
- 設計第一波學生練習樣本與標準解答
- 規劃 AI Response × Prompt Pattern 的分析模組
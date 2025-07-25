# Stage 2｜AI，說明白:CAFEC 與提示語的第二課
## AI Coach", "Hung-Hua Tien

當我們帶學生走過「想清楚」的階段，下一步，就是如何讓 AI 聽得懂。 這個階段的重點，不再只是人腦內部的釐清，而是語言外部的傳達——**如何把我們的思考，轉化成 AI 能理解並正確執行的語言？**

## **一、這階段是什麼？｜語義轉換 × 任務說明**

這一階段，是提示語學習最容易被誤解的地方。 許多教學一開始就跳入「怎麼寫好提示語」，卻忽略了：**提示語本身是一種語言轉譯的技術，而不是排列咒語的技巧。**

這些問題其實不是程式設計問題，而是語言與邏輯的問題。 這也是為什麼我們主張：**提示語是語義結構化的語言設計工作，讓語言能轉譯成 AI 理解的任務，而不只是技巧堆疊。**

### **📍問題的關鍵: AI 如何看待你的提示語？**

人類使用語言時，常仰賴語境與默契，但 AI 處理語言則是：

-   試圖找出**任務的動詞與執行結構**

-   呼叫內部模組（如分類器、摘要器、生成器）

所以，**語義不清會導致 AI 呼叫錯誤模組、走錯任務邏輯。** 提示語學習的核心，其實是「讓語言轉譯成 AI 能正確理解的任務」。

## **二、目前發展到哪？｜從技巧提示到策略分流**

現在坊間討論許多策略（COT、ReAct、Few-shot...），但這些策略都假設「你已經知道要做什麼」。 如果 Stage 1 沒完成，Stage 2 再多技巧都派不上用場。

我們的觀察是：

-   學生以為自己說清楚了，但 AI 不知道你在幹嘛

-   學生搞不清楚自己要幹嘛，但寫了很複雜的句子

這就是提示語學習的第一道瓶頸。

此外，我們發現提示語學習其實牽涉一個更深的議題：**人與 AI 如何分工協作？**

### **🧠 不同的提示語策略 = 不同的協作關係**

-   **全權交給 AI（如 COT）**：適合 AI 已擅長的任務

-   **明確規劃人主導（如 SOP）**：適合流程清楚的人工作流

-   **人機對話來回（如討論）**：適合探索式任務與創作

### **❗補充一個常見誤解**

> 「API 才是進階用法」其實並不完全正確：

-   任務明確可用 API，但探索與思辨反而需要互動式提示語

-   與 AI 協作的本質，是根據需求與任務設計策略與語言結構

## **三、我們的貢獻與主張：CAFEC 與語義動詞設計**

我們的 CAFEC 框架，不只是一個寫作格式，它是語言結構的設計指南。

CAFEC 的五個欄位：

-   Character

-   Action

-   Format

-   Example

-   Constraint

其中 **Action** 是核心中的核心，因為：

-   **動詞（Verb）**：決定 AI 認知任務的起點

-   **方法（Method）**：對應人與 AI 的協作策略

坊間多數提示工程聚焦方法設計，但我們發現：**在教育現場，動詞選得好，比策略用得炫更重要。**

Claude 曾指出：CAFEC 是語義模組的語法，能以結構化語言傳達任務意圖，讓人「說明白」、AI「聽得懂」。

## **四、我們的教學策略：從語義元素到提示語流程設計**

Stage 2 的教學落點在大二課程《與 AI 一起詠唱》，是第一次大量引入：

-   CAFEC Prompt

-   語義變項資料庫（動詞庫、格式庫...）

-   Meta Prompt × Parsing Prompt

學生會練習：

-   拆解提示語

-   替換語義元素

-   比對動詞與任務結構

-   分析語義策略與協作效果

這些訓練讓學生**開始像設計者與觀察者一樣思考提示語**，而不只是使用者。

## **五、我們要做的事：從結構學習走向策略協作**

我們正在進行兩件事：

1.  **語義變項資料庫建構**（角色、動詞、格式、範例、限制）

2.  **提示語模擬器與協作流程卡設計**：觀察語義組合 × 設計人機分工

因為我們相信：

> 提示語不是「下命令」，而是**設計任務與策略的語言工具**。

## **📌 Stage 1 × Stage 2 的總結**

-   Stage 1 解決「人搞不清楚」的問題

-   Stage 2 解決「AI 聽不懂你說什麼」的問題

CAFEC 就是這個關鍵橋梁，幫助人類將內在思考轉化為 AI 理解的語言結構。 這是一種語義設計能力，也是一種新的語言素養。

> 下一篇，我們將進入 Stage 3，討論資料的角色，探索提示語如何進一步支援資料分析與行動決策。

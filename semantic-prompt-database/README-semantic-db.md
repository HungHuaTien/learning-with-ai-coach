# 📘 語義提示語資料庫 Semantic Prompt Database

本資料夾為 **C–CAFE–C 模組 × 語義控制策略 × 提示語觀測與實驗資料庫**，提供統一語義架構下的可操作、可觀測提示語資源，作為以下用途：

- 教學設計（模組訓練、語義範例、句型練習）
- 控制策略研究（觀測模組效果、變項控制、組合實驗）
- 提示語學理論建構（語法語義語用對位、IPO 對應分析）

------

## 📁 資料夾架構

```bash
semantic-prompt-database/
├── README-semantic-db.md           # 本說明文件
├── L1-modules-overview.md         # C–CAFE–C 六大模組語義定義與觀測方式
├── CAFEC-L2-control-table.md      # 六大模組 × 控制策略（L2）對照表
├── prompt-annotation-examples/    # 單句語義標註範例集合
└── pattern-experiments/           # 提示語組合變化與觀測資料
```

------

## 🔍 建構原則

本語義資料庫遵循以下三項原則：

1. **可觀測性（Observable）**：每個語義模組需能在輸出中呈現效果變異。
2. **可組合性（Combinable）**：模組之間可自由組合，不互相衝突。
3. **可控制性（Controllable）**：可針對單一模組進行語義或語法操作控制。

此設計邏輯與統計中的變項設計原則一致，有利於建立因果推論與實證研究基礎。

------

## 🔗 延伸參考

- C–CAFE–C 框架介紹文章：〈CAFE–C 的地方，其實大家都會誤會〉
- Character 模組教學文章：〈Character 模組教學：Role × Audience × 語氣設計 × 語法對應〉
- GitHub 應用路徑：`learning-with-ai-coach/project/co-prompt/`

------

如需新增觀測模組、語義任務，請先更新本說明文件與對照表，保持架構一致性。

> Maintained by: Hung-Hua Tien & AI Coach
>  Repository: https://github.com/HungHuaTien/learning-with-ai-coach
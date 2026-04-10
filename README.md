# wuji-my-axiom

> 從你的價值推導 AI 的一切行為。

## 這是什麼

一套公理式 AI 治理系統。不列規則，從一條公理推導所有行為。

傳統做法：寫 100 條規則告訴 AI 怎麼做。
wuji-my-axiom：寫 1 條公理，AI 自己推導怎麼做。

## 快速開始

1. 複製 `templates/CLAUDE.md` 到你的專案
2. 執行冷啟動校準：讓 AI 按 `calibration/GUIDE.md` 問你 10 個問題
3. 把校準結果填入「我的卦」區塊
4. 開始使用，系統會透過「變通」機制持續校準

## 核心架構

```
道（不動）：CLAUDE.md — 太極 + 生生 + 爻則
德（常新）：Memory   — 回饋記憶，持續累積
器（可換）：Skills   — 具體工具，隨時替換
```

## 生生循環

```
感（接觸）→ 化（轉化）→ 貞（校驗）→ 新（更新）
```

所有工作遵循此循環。貞而無據，標記不確定，交人。不生即死。

## 理論基礎

- 易經繫辭：太極→兩儀→四象→八卦→萬物
- PDCA 循環同構：感=Plan，化=Do，貞=Check，新=Act
- 強化學習：使用中持續校準

詳見 [docs/THEORY.md](docs/THEORY.md)

## 目錄

```
docs/           — 理論、架構、環境建置、日常操作、演化、評估
templates/      — CLAUDE.md + MEMORY.md + 記憶模板
calibration/    — 冷啟動校準流程 + 題庫 + 角色庫 + 檢測
examples/       — 虛構人物完整範例
research/       — 相關工作比較 + 學術引用
```

## 環境需求

- 支援 system prompt + 持久記憶的 AI 工具（如 Claude Code）
- Git

不需要 GPU、雲端服務或額外付費 API。

## License

MIT

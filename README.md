# 真相雜誌 Claude Project Instructions

這個 repo 存放真相雜誌 Claude Project 的所有指令檔與已完成文章備份。

## 檔案結構

- `instructions.md` — 主指令檔（品牌定位、欄目定義、選題原則、產出 SOP、口吻規範）
- `humanizer.md` — 去 AI 寫作痕跡準則（所有文字產出的最高寫作標準）
- `archive/` — 已完成文章的備份資料夾

## 使用方式

Claude Project 的 Custom Instructions 裡寫一句：

> 開始工作前，先用 GitHub MCP 讀取 `kid790817-ai/detective-007` repo 裡的 `instructions.md`，照裡面的流程跟老闆互動。所有文字產出遵守 `humanizer.md` 的去 AI 寫作準則。

## 修改方式

需要調整流程、口吻、欄目規範時，直接在對話中跟 Claude 說，Claude 會來這個 repo 改檔案。

## 備份規則

每篇文章定稿後，Claude 會將完成稿推進 `archive/` 資料夾，檔名格式：`YYYY-MM-DD_slug.md`。

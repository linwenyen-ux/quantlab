# 量化策略實驗室（QuantLab）

台股／美股日線策略回測平台 — 單檔網頁應用，可安裝為手機 App（PWA）。

**線上版：** https://linwenyen-ux.github.io/quantlab/

## 功能
- 39 支策略（Alorse 30 支 ＋ 台股常用 8 支 ＋ Dual CCI）× 台股／美股，另可用條件積木自訂策略
- 穩健性檢驗：隨機基準檢定、成本敏感度、交易序列模擬、Walk-Forward
- 今日訊號、策略組合、多股批次、標的風險卡、參數最佳化
- 匯出：CSV、Markdown、PDF、PPTX、Pine Script
- 資料來源：FinMind 開放 API（免 token；填免費 token 額度加倍）

## 安裝到手機
用手機瀏覽器開啟上面的網址：
- **iPhone**：Safari → 分享 → 加入主畫面
- **Android**：Chrome → ⋮ → 安裝應用程式

## 檔案
| 檔案 | 用途 |
|---|---|
| `index.html` | 應用程式本體（單檔，由原始碼專案建置產出） |
| `manifest.json` | PWA 設定 |
| `sw.js` | Service Worker（離線快取） |
| `icons/` | 應用程式圖示 |

## 注意
本工具為研究用途，不構成投資建議。所有數字來自歷史回測，不保證未來績效。行情資料來自 FinMind，請遵守其使用條款。

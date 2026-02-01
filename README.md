# OpenClaw AI - GitHub Codespaces 零成本部署 [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new)

## 🚀 快速開始

### 方法一：GitHub Codespaces（推薦）
1. **Fork 或上傳此倉庫到你的 GitHub**
2. **點擊綠色 "Code" 按鈕** → 選擇 "Codespaces" 標籤
3. **點擊 "Create codespace on main"**
4. 等待 2-3 分鐘，OpenClaw AI 將自動從 GitHub 克隆並構建最新版本
5. 終端會顯示公網訪問地址

### 方法二：手動安裝（GitHub 最新版）
在 Codespace 終端執行：
```bash
git clone https://github.com/openclaw/openclaw.git ~/openclaw
cd ~/openclaw
npm install
npm run build
npm link
```
然後啟動 OpenClaw：
```bash
openclaw
```

## 📋 規格配置
| 項目 | 規格 |
|------|------|
| CPU | 2 核心 |
| 記憶體 | 8 GB |
| 硬碟 | 32 GB |
| 免費時數 | 120 小時/月 |

## 🌐 端口映射
GitHub Codespaces 會自動將以下端口映射為公網地址：
- **3000**: OpenClaw Web UI 主界面
- **8080**: OpenClaw API 服務

## ⚙️ 環境說明
- **作業系統**: Ubuntu (Linux)
- **Node.js**: v20.x LTS
- **Git**: 已預裝
- **安裝來源**: [github.com/openclaw/openclaw](https://github.com/openclaw/openclaw)

## 🔄 更新到最新版
```bash
cd ~/openclaw
git pull origin main
npm install
npm run build
```

## 📝 注意事項
1. 免費額度每月重置，建議在不使用時停止 Codespace
2. Codespace 閒置 30 分鐘後會自動暫停（可在設定中調整）
3. 暫停狀態不消耗免費時數
4. 資料會保留在 Codespace 中，刪除前請備份重要資料

## 🔗 相關連結
- [OpenClaw GitHub](https://github.com/openclaw/openclaw)
- [OpenClaw AI 官網](https://openclaw.ai)
- [GitHub Codespaces 文件](https://docs.github.com/en/codespaces)
- [GitHub 免費額度說明](https://docs.github.com/en/billing/managing-billing-for-github-codespaces/about-billing-for-github-codespaces)

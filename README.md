# AWA - English Vocabulary Learning App

一個幫助用戶背英文單字的全棧應用

## 📚 功能特性

- ✅ **單詞卡片學習** - 互動式閃卡系統
- ✅ **多種學習模式** - 拼寫、選擇題、聽力
- ✅ **進度追蹤** - 記錄學習進度和掌握程度
- ✅ **自定義詞庫** - 創建和管理個人單詞集合
- ✅ **統計分析** - 學習統計和複習提醒

## 🛠️ 技術棧

- **前端**: React 18 + TypeScript + Tailwind CSS
- **後端**: Node.js + Express + TypeScript
- **數據庫**: MongoDB
- **工具**: Docker, Jest

## 📁 項目結構

```
awa/
├── frontend/          # React 前端應用
├── backend/           # Express 後端服務
├── shared/            # 共享類型定義
├── docker-compose.yml # Docker 配置
└── README.md
```

## 🚀 快速開始

### 前置需求
- Node.js 18+
- MongoDB
- npm 或 yarn

### 安裝與運行

```bash
# 安裝依賴
cd frontend && npm install
cd ../backend && npm install

# 啟動後端 (port 5000)
cd backend && npm run dev

# 啟動前端 (port 3000)
cd frontend && npm start
```

## 📖 API 文檔

詳見 `backend/docs/API.md`

## 🤝 貢獻

歡迎提交 PR 和 Issue！

## 📄 授權

MIT License

# Ragic 表單梳理工具

一方生活營運系統 - 467 個 Ragic 表單完整審查工具

## 🚀 Zeabur 部署步驟

### 方法 1：自動部署（推薦）
1. 打開 [Zeabur Dashboard](https://dash.zeabur.com)
2. 點擊「Create new project」
3. 選擇「Deploy from GitHub」
4. 選擇 repo: `mry88312/ragic-review-tool`
5. 選擇 branch: `main`
6. 點擊「Deploy」
7. 等待部署完成（約 1-2 分鐘）
8. Zeabur 會自動分配一個網址（例如：`https://ragic-review-tool-xxx.zeabur.app`）

### 方法 2：一鍵部署按鈕
[![Deploy on Zeabur](https://zeabur.com/button.svg)](https://zeabur.com/templates/deploy?repo=mry88312/ragic-review-tool)

## 📦 專案結構
```
.
├── index.html              # 主頁面
├── ragic-forms-data.csv    # 467 個表單資料
├── zbpack.json             # Zeabur 設定
└── README.md               # 說明文件
```

## ✨ 功能特色
- 📊 467 個表單完整呈現
- 🔍 即時搜尋與篩選
- ✍️ 審查決定（保留/整合/廢棄）
- 📝 備註記錄
- 💾 自動儲存進度
- 📥 匯出決定為 CSV

## 🎯 使用方式
1. 打開網址
2. 瀏覽表單列表
3. 為每個表單標記決定
4. 添加備註說明
5. 完成後匯出 CSV
6. 提供給 AI 助手生成整改計畫

## 🔧 技術棧
- 純靜態網站（HTML + CSS + JavaScript）
- 無需後端
- 瀏覽器 localStorage 儲存

## 📝 授權
一方生活內部使用

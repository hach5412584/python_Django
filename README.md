# Django 學習歷程

## 🚀 簡介
這是一個用來記錄我學習 Django 過程的 GitHub 專案，透過實作一個簡單的網站，掌握 Django 的基礎概念與應用。

## 🎯 學習目標
- 了解 Django 的基本架構
- 學習 Django 的 MVT（Model-View-Template）設計模式
- 建立簡單的網頁應用程式
- 連接 PostgreSQL 資料庫（或 SQLite）
- 建立 CRUD（Create, Read, Update, Delete）功能
- 部署 Django 專案到雲端

## 🛠️ 環境與工具
- **Python**: 3.9+
- **Django**: 最新穩定版本
- **資料庫**: SQLite（開發）/ PostgreSQL（生產環境）
- **前端框架**: Bootstrap + Material-UI
- **版本控制**: Git & GitHub
- **開發工具**: VS Code / PyCharm

## 📌 專案架構
```
.
├── mysite/               # Django 專案目錄
│   ├── mysite/           # 專案設定與 URL 配置
│   ├── myapp/            # 自訂應用程式（App）
│   │   ├── migrations/   # 資料庫遷移檔案
│   │   ├── templates/    # HTML 模板
│   │   ├── static/       # 靜態資源（CSS, JS, Images）
│   │   ├── models.py     # 資料庫模型
│   │   ├── views.py      # 處理請求與回應
│   │   ├── urls.py       # 路由設定
│   │   ├── forms.py      # 表單處理
│   │   ├── admin.py      # Django Admin 設定
│   ├── manage.py         # 專案管理指令
├── requirements.txt      # 套件需求列表
├── README.md             # 本文件
```

## 🚀 安裝與啟動
1. **安裝 Django**
   ```bash
   pip install django
   ```
2. **建立專案與應用程式**
   ```bash
   django-admin startproject mysite
   cd mysite
   python manage.py startapp myapp
   ```
3. **啟動伺服器**
   ```bash
   python manage.py runserver
   ```
4. **開啟瀏覽器**，前往 `http://127.0.0.1:8000/`

## 🔖 進度紀錄
- [x] 安裝 Django
- [x] 建立專案與應用程式
- [x] 設定基本路由與視圖
- [ ] 建立資料庫模型（Models）
- [ ] 開發 CRUD 功能
- [ ] 設計前端頁面
- [ ] 部署到雲端

## 📚 參考資源
- [Django 官方文件](https://docs.djangoproject.com/en/stable/)
- [Django 教學課程](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django)
- [GitHub Markdown 語法](https://guides.github.com/features/mastering-markdown/)

---
**作者**: [你的 GitHub 名稱]


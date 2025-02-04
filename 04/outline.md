# 第四章：API 開發和測試

## 學習目標 (新手階段)
- 理解 API 和 HTTP 的基本概念
- 學會閱讀 API 文檔
- 掌握 curl 的基礎使用
- 認識 JSON 數據格式

## 學習目標 (進階新手階段)
- 理解 REST 架構原則
- 掌握不同的認證機制
- 學會使用環境變量
- 建立基本的測試習慣

## 章節內容

### [4.1 認識 API](4-1.md) (新手必學)
- 什麼是 API
- HTTP 請求方法介紹
  - GET：獲取數據
  - POST：提交數據
- JSON 格式介紹
  - JSON 語法規則
  - 常見 JSON 結構
- API 文檔閱讀方法

### [4.2 curl 入門](4-2.md) (新手必學)
- curl 介紹和安裝
- 基本命令格式
- 發送基本請求
  - GET 請求操作
  - POST 請求操作
- 查看響應結果
  - 狀態碼含義
  - 響應數據解析
- 常用參數說明
  - -X：指定請求方法
  - -H：設置請求頭
  - -d：發送數據

### [4.3 API 認證基礎](4-3.md) (進階新手)
- 常見認證類型介紹
- Basic Authentication
- API Key 認證
- Token 認證
- curl 中的認證參數
  - -u：Basic Auth
  - -H：Token/API Key

### [4.4 API 測試進階](4-4.md) (進階新手)
- 環境變量使用
  - 設置環境變量
  - 在 curl 中使用環境變量
- 請求參數設置
  - URL 參數構建
  - 請求頭（Headers）設置
  - 請求體格式化
- 常見錯誤處理
  - 狀態碼解讀
  - 錯誤信息分析
- 建立測試腳本
  - 基本 shell 腳本
  - 組合多個請求

## 實戰練習
1. API 基礎操作練習 (新手)
   - 使用 curl 發送 GET 請求
   - 使用 curl 發送 POST 請求
   - 解析 JSON 響應數據

2. API 認證練習 (進階新手)
   - 實現不同認證方式
   - 使用環境變量
   - 編寫簡單測試腳本

## 常見問題解答
- curl 命令格式錯誤解決
- API 請求失敗排查
- 認證不通過處理方法
- JSON 格式錯誤的解決
- 找不到正確的 API 地址

## 測試心法
- 從簡單的 curl 命令開始
- 善用 curl 的 verbose 模式（-v）
- 記錄常見問題和解決方法
- 逐步建立測試腳本庫

## 延伸學習資源
- curl 官方文檔
- API 測試教學網站
- shell 腳本入門教程
- 推薦的 API 練習平台

## 章節導航
- [回到首頁](../README.md)
- [上一章：第三章](../03/outline.md)
- [下一章：第五章](../05/outline.md)

## 本章節檔案
- [4.1 認識 API](4-1.md)
- [4.2 curl 入門](4-2.md)
- [4.3 API 認證基礎](4-3.md)
- [4.4 API 測試進階](4-4.md)
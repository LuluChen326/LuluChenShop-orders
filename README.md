# 🛍️ LuluChen Shop 訂單管理系統

這個倉庫用於管理來自 [LuluChen Shop 網站](https://luluchen326.github.io/LuluChenShop-website/) 的所有客戶訂單。

## 📋 訂單處理流程

### 1. 新訂單提交
- 客戶在網站填寫訂單表單
- 自動在此倉庫創建新的 Issue
- 自動標記為 🆕 **新訂單**

### 2. 處理步驟
1. **聯繫客戶** → 標記為 📞 **已聯繫**
2. **確認付款** → 標記為 💰 **已付款**
3. **安排代購** → 開始採購流程
4. **商品出貨** → 標記為 📦 **已出貨**
5. **完成訂單** → 標記為 ✅ **已完成** 並關閉 Issue

## 🏷️ 標籤系統

| 標籤 | 意義 | 處理狀態 |
|------|------|----------|
| 🆕 新訂單 | 剛提交的訂單 | 需要聯繫客戶 |
| 📞 已聯繫 | 已聯繫客戶確認 | 等待客戶回覆 |
| 💰 已付款 | 客戶已完成付款 | 可以開始代購 |
| 📦 已出貨 | 商品已寄出 | 等待客戶收貨 |
| ✅ 已完成 | 訂單完成 | 可以關閉 Issue |
| ❌ 已取消 | 訂單取消 | 記錄取消原因 |
| 🔥 緊急處理 | 需要緊急處理 | 優先處理 |

## 📊 快速篩選

- 查看所有新訂單：[🆕 新訂單](https://github.com/LuluChen326/LuluChenShop-orders/issues?q=is%3Aissue+is%3Aopen+label%3A%22🆕+新訂單%22)
- 查看已付款訂單：[💰 已付款](https://github.com/LuluChen326/LuluChenShop-orders/issues?q=is%3Aissue+is%3Aopen+label%3A%22💰+已付款%22)
- 查看所有進行中：[進行中的訂單](https://github.com/LuluChen326/LuluChenShop-orders/issues?q=is%3Aissue+is%3Aopen)
- 查看已完成訂單：[✅ 已完成](https://github.com/LuluChen326/LuluChenShop-orders/issues?q=is%3Aissue+is%3Aclosed+label%3A%22✅+已完成%22)

## 🔍 搜尋功能

### 按客戶搜尋
```
author:客戶名稱
```

### 按時間搜尋
```
created:>2024-01-01  # 2024年1月1日後的訂單
updated:<2024-12-31  # 2024年12月31日前更新的訂單
```

### 按商品搜尋
```
"泰迪熊" in:title,body
```

## 📱 通知設定

### GitHub 通知
- 新 Issue 會自動發送 Email 通知
- 可在 GitHub Settings > Notifications 調整通知偏好

### 手機 App
- 下載 GitHub 手機 App 可即時接收訂單通知

## 📈 統計資訊

可以使用 GitHub 的 Insights 功能查看：
- 每月訂單數量
- 處理時間統計
- 熱門商品分析

## 🔒 隱私保護

- 客戶個人資訊僅用於訂單處理
- 完成的訂單會保留記錄但會關閉 Issue
- 敏感資訊不會公開顯示

---

📞 **聯絡資訊**
- Instagram: [@arceus_fcy
- LINE: @luluchen326
- Email: luluchen326@gmail.com

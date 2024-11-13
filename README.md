For English version, please see [README_EN.md](README_EN.md)

# 球模擬器

這是一個基於 HTML5 Canvas 和原生 JavaScript 開發的球模擬器。

## 主要特性

- 動態響應式畫布：自動調整以適應不同的螢幕尺寸
- 物理模擬：
  - 摩擦力模擬
  - 邊界碰撞檢測和反彈
- 視覺化運動軌跡：使用箭頭指示球的運動方向和速度
- 實時數據展示：
  - 鼠標位置坐標
  - 球與鼠標之間的距離
  - 球的速度分量

## 使用指南

1. 打開 [ball.html](https://onenok.github.io/ball.html/)
2. 移動鼠標來影響球的運動軌跡

## 技術實現

- 採用 HTML5 Canvas 進行渲染
- 使用原生 JavaScript 實現，無外部依賴
- 物理模擬：
  - 速度和位置計算
  - 碰撞檢測
  - 摩擦力

## 貢獻指南

我們歡迎社區貢獻！如果您有改進建議或新功能想法，請遵循以下步驟：

1. Fork 此存儲庫
2. 創建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 開啟一個 Pull Request

## 許可證

本項目採用 MIT 許可證 - 詳情請參閱 [LICENSE](LICENSE) 文件。

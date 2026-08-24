# 國王遊戲抽籤程式 — 設計討論摘要

## 定位（v10）
- **手機專用** PWA（不再以電視投影三欄為主）
- GitHub Pages：https://catalinaerantzo.github.io/king-game/
- 視覺參考高級深色卡片風：襯線標題、大圓角、留白、無實線邊框

## 玩法
- **抽牌模式**：國王牌 → 受罰牌（可連抽，1v1）
- **抽組別模式**：國王組 → 受罰組（可連抽）
- **處罰**可獨立抽（Beer Pong 等）
- 牌組可排除花色／點數；預設 A–10 × 四花色

## 技術
- `index.html` + `manifest.webmanifest` + `sw.js` + `icons/`
- 加到主畫面：Safari「分享 → 加入主畫面」

# CountCard

快速計算撲克牌點數總和的網頁小工具。

線上使用：https://deantw69.github.io/CardCount/

## 點數規則

| 牌 | 點數 |
|---|---|
| A | 1 |
| 2 ~ 10 | 同牌面 |
| J / Q / K | 15 |

## 功能

- 點一下牌，總和加上該牌點數，牌的右上角顯示這張牌已點幾次
- 復原：撤回最後一張
- 歸零：清空總和與紀錄
- 可加入 iPhone 主畫面：Safari 開啟 → 分享 → 加入主畫面，以全螢幕 App 方式開啟

## 開發

純 HTML/CSS/JS 單檔 `index.html`，無依賴、無 build，直接用瀏覽器開啟即可。

`manifest.webmanifest` 與 `apple-touch-icon.png`、`icon-192.png`、`icon-512.png` 供加入主畫面使用。

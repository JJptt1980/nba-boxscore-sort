# NBA Box Score 欄位置前與排序

[![Ko-fi](https://img.shields.io/badge/Ko--fi-%E8%AB%8B%E6%88%91%E5%96%9D%E6%9D%AF%E5%92%96%E5%95%A1-FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/jjptt1980)

在 NBA.com 的 box score 頁面左下角加入兩個按鈕：

- **📌 排第一**：選擇任一欄位（PTS、REB、AST…）移到球員名字後面
- **⇅ 依數字排序**：依該欄位排序，循環切換「高到低 → 低到高 → 還原」

## 安裝

1. 瀏覽器先安裝 [Tampermonkey（篡改猴）](https://www.tampermonkey.net/)
2. **[點此安裝腳本](https://raw.githubusercontent.com/JJptt1980/nba-boxscore-sort/main/nba-boxscore-sort.user.js)**
3. 在跳出的畫面按「安裝」
4. 打開任一場 NBA.com 的 box score 頁面即可使用

## 截圖

![範例](screenshot.png)

## 說明

- 只在瀏覽器端調整顯示，不會修改 NBA.com 的任何資料
- 本專案為非官方工具，與 NBA 無關
- 沒有收集或傳送任何個人資料

## 更新紀錄

- **2.0.0**：新增兩個按鈕，可自選欄位置前與排序
- **1.2**：修正被頁面還原的問題
- **2.2.0**
   - ⭐ 預設配置按鈕：內建 9 種配置，可儲存自訂配置
   - 自動記住上次選的欄位與排序
## 授權

從 2026-11-26 起，之後的版本改用 [PolyForm Noncommercial 1.0.0](LICENSE) 授權：個人、學習、非營利用途免費使用；商業用途需要另外購買商用授權，請到本專案的 GitHub Issues 聯絡。

在這之前已發布的版本，仍依當時的 MIT 授權。

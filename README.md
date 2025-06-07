# 自訂溫和倒數計時器

這是一個基於純前端技術 (HTML/CSS/JavaScript) 實作的**自訂倒數計時器**，可用於會議、演講、活動現場等需要大字體全螢幕投影倒數的場景，不會連續響鈴過長，也有純閃爍的提示方式，屬於溫和提醒。

---

## 功能特色

- 使用者可自由設定計時器名稱  
- 可自訂倒數時間（時、分、秒）  
- 快捷選擇提前提醒時間（剩10秒、30秒、1分鐘、5分鐘提醒）
- 可自訂提前提醒時間
- 提醒方式可選：響聲提醒、紅字閃爍、無提醒  
- 可選不同鈴聲，並僅於選「響聲提醒」時生效  
- 全螢幕模式顯示計時器名稱與倒數時間
- 倒數完畢退出全螢幕倒數，回到設定介面
- 中途可按ESC終止計時
- 計時中可選擇暫停/繼續
- 簡潔、直觀的使用介面，無需安裝，直接用瀏覽器開啟即可使用
  

---

## 使用說明

1. [使用Demo](https://jokctseng.github.io/timer) 或下載並於現代瀏覽器開啟 `index.html`檔案  
2. 在設定區域輸入倒數計時名稱與時、分、秒  
3. 選擇或自訂提前提醒秒數 
4. 選擇提醒方式（響聲提醒、紅字閃爍或無）  
5. 選擇響聲鈴聲（僅限響聲提醒時生效）  
6. 點擊「開始倒數」按鈕，頁面會切換至全螢幕模式，顯示倒數  
7. 倒數結束或提前提醒時，會以選擇的方式進行提醒  
8. 按鍵盤 `ESC` 可退出全螢幕倒數，回到設定介面繼續調整或重新開始
9. 按暫停按鈕可暫停計時 

---

## 技術細節

- 使用純前端技術：HTML5 + CSS3 + JavaScript (ES6)  
- 全螢幕倒數區塊字體大小採用響應式 `vw` 單位，適應不同螢幕尺寸與投影  
- 響聲提醒透過 `<audio>` 元素播放，並連續播放3次提示聲
- 可用鍵盤事件監聽 `ESC` 退出計時，提升使用便利性  
- 所有音效均採用 Google 提供的免費音效  

---

## 音效來源

鈴聲音效來自 Google Actions Sound Library，授權自由商用與修改：

- Ding: [digital_watch_alarm_long.ogg](https://actions.google.com/sounds/v1/alarms/digital_watch_alarm_long.ogg)  
- Pop: [pop.ogg](https://actions.google.com/sounds/v1/cartoon/pop.ogg)  
- Beep: [beep_short.ogg](https://actions.google.com/sounds/v1/alarms/beep_short.ogg)  
- Chime: [chime_long.ogg](https://actions.google.com/sounds/v1/alarms/chime_long.ogg)  
- Notify: [medium_bell_ring.ogg](https://actions.google.com/sounds/v1/alarms/medium_bell_ring.ogg)  
- Ping: [ping.ogg](https://actions.google.com/sounds/v1/alarms/ping.ogg)  

---

## 開發與貢獻

歡迎對此專案提出建議或功能需求，若想協助改進，請 fork 本專案並提出 Pull Request。

---

## 授權條款

本專案程式碼採用 GNU General Public License v3.0 (GPL-3.0) 授權。  

歡迎自由使用、修改及散布，但必須在相同授權條款下釋出衍生作品，並保留原作者資訊。  
詳細條款請參考 [GPLv3 官方說明](https://www.gnu.org/licenses/gpl-3.0.html) 


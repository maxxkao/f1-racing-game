# f1-racing-game
🏎️ F1 Racing Game — Wireframe Edition

A single-file, browser-based wireframe F1 racing game with a built-in track editor, 8-car AI grid, cyberpunk skyline, and zero build steps. Just open the HTML file and race.

繁體中文說明請見下方 ↓ / Traditional Chinese version below ↓

✨ Features
Custom track editor — snap straight and curve pieces onto a 16×16 grid, set your own start/finish line, and validate that your track forms a proper closed loop before racing
3 built-in sample tracks — Easy / Medium / Hard, ranging from a simple oval to a 32-corner maze
Export / Import tracks — turn any track you design into a short text code you can share with friends; they paste it back in to load your exact layout
8-car grid — you vs. 7 AI opponents, each with randomized colors, speed, and behavior (weaving, drafting close to you, or blocking overtakes)
Low-poly wireframe visuals — neon cyberpunk aesthetic with a scattered city skyline, double-line track boundaries with tie markers, and a proper F1-style low-poly car (front/rear wings, sidepods, rolling wheels)
Full race flow — start screen with a spinning showcase car, countdown, live lap/position/speed/time HUD, FINAL LAP banner, collision sparks, top-speed tail-light trails, a slow-motion finish-cam orbit, and a trophy for podium finishes
Synthesized audio — engine note that tracks your speed, countdown beeps, collision hits, lap chimes, and victory/defeat fanfare — all generated with the Web Audio API, no audio files needed
First-person cockpit view — toggle between chase cam and driver's-eye view (press C or tap the camera button)
Mobile-friendly — on-screen touch controls, responsive layout, and touch-safety fixes for long-press issues on iOS/Android
Mute toggle and 1–5 selectable laps / 3 difficulty levels
🚀 Quick Start

There is no build step and no dependencies to install.

Download index.html
Open it in any modern browser (Chrome, Safari, Edge, Firefox)
Click START
Hosting on GitHub Pages
Push f1_wireframe.html to your repository (rename it to index.html for the cleanest URL, or keep the name and link to it directly)
Go to Settings → Pages, set the source branch, and save
Your game will be live at https://<username>.github.io/<repo>/

The game loads three.js from a CDN (cdnjs.cloudflare.com), so an internet connection is required the first time it loads (it will be cached by the browser afterward).

🎮 Controls
Action	Keyboard	Touch
Accelerate	↑	▲ button
Brake / Reverse	↓	▼ button
Steer	← →	◀ ▶ buttons
Toggle camera view	C	📷 button
Mute audio	—	🔊 button
🛠️ Building a Track
From the start screen, click START to enter the Track Editor
Select STRAIGHT or CURVE and tap grid cells to place pieces — tap an existing piece again to rotate it
Select SET START and tap a placed piece to mark it as your start/finish line
Use ERASE to remove pieces, or CLEAR ALL to start over
Try SAMPLE 1/2/3 for ready-made tracks of increasing difficulty
Click NEXT — the editor checks that your track forms a single closed loop with at least 8 pieces before letting you continue
On the next screen, choose laps (1–5) and difficulty, then START RACE
Sharing your track

Click EXPORT in the editor to get a text code representing your track. Send it to a friend — they click IMPORT, paste the code, and your exact track loads instantly.

🧰 Tech Stack
Plain HTML / CSS / JavaScript — no framework, no bundler
three.js (r128) for WebGL rendering, loaded via CDN
Web Audio API for all sound effects and the engine note (synthesized, no audio files)
Everything — track logic, 3D rendering, physics, AI, UI — lives in a single .html file
📄 License

Feel free to adapt this for your own README/license preference — for example, MIT:

MIT License — do whatever you like with this project, just keep the copyright notice.
🙏 Acknowledgments
three.js for the WebGL rendering engine
🏎️ F1 Racing — 線框版

一個完全單一 HTML 檔案、不需要任何安裝的線框風格 F1 賽車遊戲，內建賽道編輯器、8 台車的 AI 對戰、賽博龐克風格城市場景。打開檔案就能玩。

✨ 功能特色
自製賽道編輯器：在 16×16 的方格中自由拼接直線與彎道拼圖、設定起點/終點線，系統會自動驗證賽道是否組成完整的封閉迴圈才能開始比賽
內建 3 條範例賽道：簡單／普通／困難，從簡單橢圓賽道到 32 個彎道的迷宮賽道都有
賽道匯出／匯入：把自己設計的賽道轉成一段文字代碼，傳給朋友，對方貼上就能載入你設計的一模一樣的賽道
8 台車對戰：你 + 7 台 AI 對手，每台車顏色隨機、速度不同，還會隨機蛇行、靠近你或故意擋車
低多邊形線框畫面：霓虹賽博龐克風格，四周散布著隨機大小的城市天際線，賽道邊線是雙線＋等距刻度標記，車輛造型接近真正的F1賽車（前後翼、側箱、會轉動的輪胎）
完整比賽流程：開始畫面有旋轉展示車、倒數計時、即時圈數/名次/速度/時間顯示、最後一圈提示、碰撞火花特效、極速拖曳光尾、終點慢動作環繞鏡頭、前三名還有旋轉獎盃動畫
即時合成音效：引擎聲會隨車速變化、倒數音效、碰撞聲、過圈提示音、勝利/落敗音樂，全部用 Web Audio API 即時生成，不需要任何音檔
第一人稱視角：可以切換第三人稱/駕駛座視角（按 C 鍵或點螢幕上的相機按鈕）
手機支援：畫面上有虛擬方向按鍵、版面會自動依手機比例調整，也修正了手機長按容易卡住的問題
靜音開關，以及可選1-5圈、3種難度
🚀 快速開始

不需要安裝任何東西，也不需要建置流程。

下載 index.html
用任何現代瀏覽器打開（Chrome、Safari、Edge、Firefox 都可以）
點擊 START 開始遊玩
部署到 GitHub Pages
把 f1_wireframe.html 上傳到你的 repository（可以改名成 index.html 讓網址更簡潔，或保留原檔名直接連結過去）
到 Settings → Pages，選好來源分支後儲存
之後就可以透過 https://<你的帳號>.github.io/<repo名稱>/ 連到遊戲

遊戲會從 CDN（cdnjs.cloudflare.com）載入 three.js，所以第一次打開需要網路連線（之後瀏覽器會自動快取）。

🎮 操作方式
動作	鍵盤	觸控
加速	↑	▲ 按鈕
減速／倒車	↓	▼ 按鈕
轉向	← →	◀ ▶ 按鈕
切換視角	C	📷 按鈕
靜音	—	🔊 按鈕
🛠️ 如何設計賽道
從開始畫面點 START 進入賽道編輯器
選擇 直線 STRAIGHT 或 彎道 CURVE，點格子放置拼圖，再點一次同樣的拼圖可以旋轉方向
選擇 設起點 SET START，點已放置的拼圖將它設為起點/終點線
用 清除 ERASE 移除拼圖，或 清空全部 CLEAR ALL 重新開始
也可以直接試試看 範例1/2/3，難度由簡到難
點 下一步 NEXT — 系統會檢查賽道是否組成一個完整封閉迴圈（至少8個拼圖）才會讓你繼續
下一頁選擇圈數（1-5圈）與難度，接著 開始比賽 START RACE
分享你的賽道

在編輯器點 匯出 EXPORT 會產生一段代表這條賽道的文字代碼，傳給朋友；對方點 匯入 IMPORT 貼上代碼，就能立刻載入你設計的賽道。

🧰 技術架構
純 HTML / CSS / JavaScript，沒有框架也不需要打包工具
three.js（r128版本）負責WebGL渲染，透過CDN載入
Web Audio API 負責所有音效與引擎聲（即時合成，不需要音檔）
賽道邏輯、3D渲染、物理運算、AI、介面全部都在同一個 .html 檔案裡

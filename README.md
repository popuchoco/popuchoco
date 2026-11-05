<div align="center">

# P.Choco

### IoT Rebuild · Meteorology · Practical Tools

把停止維護的裝置重新接回現代，把颱風資料翻成可用資訊，  
也做一些替 Windows 收拾麻煩的小工具。

<br>

![Taiwan](https://img.shields.io/badge/Based%20in-Taiwan-0F766E?style=flat-square)
![Android](https://img.shields.io/badge/Android-12%2B-3DDC84?style=flat-square&logo=android&logoColor=white)
![BLE](https://img.shields.io/badge/Focus-Bluetooth%20LE-2563EB?style=flat-square&logo=bluetooth&logoColor=white)
![Weather](https://img.shields.io/badge/Domain-Meteorology-0284C7?style=flat-square)
![Windows](https://img.shields.io/badge/Builds-Windows%20Tools-512BD4?style=flat-square&logo=dotnet&logoColor=white)

</div>

## What I build

我喜歡處理那些「硬體還好好的，只是軟體先離場」的問題，也把氣象電碼、颱風路徑與日常維運需求，整理成能直接使用的工具。

- **IoT Rebuild** — 讓仍能工作的裝置擺脫過時 App 與雲端依賴。
- **Meteorology Tool** — 把專業氣象資料轉成可解析、可比較、可視覺化的資訊。
- **Third-Party Assist Tool** — 用小而實用的桌面工具，消除重複操作與診斷摩擦。
- **NAS Operations** — 以唯讀檢查與可稽核證據，協助 QNAP NAS 維運與相容性診斷。
- **Everyday Web Tools** — 把日常計算做成免安裝、重視隱私的網頁工具。
- **Interactive Stories** — 用生活場景呈現選擇與判斷線索，不以單一分數評斷使用者。

## IoT Rebuild

| Project | One-liner |
| --- | --- |
| [Unofficial TWM myAir S1 Client](https://github.com/popuchoco/Unofficial-TWM-MyAirS1-Client) | 讓退役雲端不等於硬體報廢：在 Android 上直接讀取、保存與排程 myAir S1 空氣資料。 |
| [Unofficial HTC RE Client](https://github.com/popuchoco/Unofficial-HTC-RE-Client) | 把 HTC RE 接回現代 Android：涵蓋 BLE 配網、Wi-Fi Direct、媒體傳輸與直播控制。 |
| [Unofficial LG PuriCare Mini Client](https://github.com/popuchoco/Unofficial-LG-PuriCare-Mini-Client) | 讓 PuriCare Mini 在 Android 12+ 繼續呼吸：本機監測、風量控制與背景連線。 |

## Meteorology Tool

| Project | One-liner |
| --- | --- |
| [Typhoon TAC Parser](https://github.com/popuchoco/typhoon-tac-parser) | 將熱帶氣旋、航空與海象電碼解碼、驗證並翻譯成忠實的繁體中文。 |
| [Typhoon Tracker](https://github.com/popuchoco/typhoon-tracker) | 在同一張工作台比較多機構颱風路徑、風圈、警戒區與人工預報線。 |
| [Weather Tools](https://github.com/popuchoco/weather-tools) | 把 Dvorak、DVTS 趨勢與 ATCF 最佳路徑整理成可輸出圖表的 Windows 氣象工具箱。 |

## Third-Party Assist Tool

| Project | One-liner |
| --- | --- |
| [Disk Resource Mover](https://github.com/popuchoco/DiskResourceMover) | 依自訂規則監看磁碟用量，將過期檔案與資料夾移往正確的位置。 |
| [Network Diagnostic Tool](https://github.com/popuchoco/NetworkDiagTool) | 把 Ping、TCP、路由、DNS、ARP、Proxy 與網卡狀態集中在一個 Windows 診斷介面。 |
| [Rho Viewer](https://github.com/popuchoco/Rho-Viewer) | 瀏覽與分析 `.rho` 封存檔，預覽、匯出並播放其中的音訊資源。 |
| [Android Network Diag](https://github.com/popuchoco/android-network-diag) | 在 Android 上驗證 DNS、HTTPS、網路狀態與公開 IP，並比較網路變更前後的實際連線結果。 |

## NAS Operations

| Project | One-liner |
| --- | --- |
| [QNAP NAS CLI](https://github.com/popuchoco/qnap-nas-cli) | 面向 QTS 5.x 的唯讀診斷 CLI／MCP：檢查 NAS 健康、儲存、RAID、磁碟拓樸、網路與 Tailscale／Container Station 狀態，並匯出已遮蔽的相容性資料；目前不提供 Synology-SA 事件掃描、封鎖或修復功能。 |
| [AdGuard Home QNAP Extension](https://github.com/popuchoco/AdGuard-Home-QNAP-Extension) | 為 TS-431K／ARMv7 設計的低資源唯讀監控 Dashboard，整合 AdGuard Home、Uptime Kuma、QTS 與 QuRouter；目前 repository 提供設計與 API 契約，尚未部署成品。 |

## Everyday Web Tools

| Project | One-liner |
| --- | --- |
| [現金怎麼配｜新台幣拆鈔計算器](https://github.com/popuchoco/how-much-NTD-for-this) | 精確列出新台幣紙鈔與硬幣的拆分組合及補足配法；純前端運作，金額不儲存也不上傳。 |

## Interactive Stories

| Project | One-liner |
| --- | --- |
| [你有禮貌嗎？](https://github.com/popuchoco/how-dare-you) | 以六個日常情境探索禮貌與公共場合判斷的互動故事，提供思考線索而非禮貌分數或人格排名。 |

## Web Game

| Project | One-liner |
| --- | --- |
| [虹膜色彩校準｜Hue of the Fake](https://github.com/popuchoco/Alternate-Visual-Identification-Test) | 以色點辨讀與色相排序展開的短篇心理恐怖網頁遊戲，逐步讓校準結果與玩家記憶發生錯位。 |
| [火鍋湯底過濾挑戰](https://github.com/popuchoco/hotpot-filter-simulator) | 在不同湯底、食材與工具間挑戰撈沫與撈油，完成各種限時關卡並解鎖成就。 |
| [夜嵐夜市](https://github.com/popuchoco/yelan-night-market) | 以 2.5D 斜視角經營台灣港邊夜市，管理菜單、備料與人員，在每日營運和夜市事件中逐步擴店。 |

## Toolbox

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![VB.NET](https://img.shields.io/badge/VB.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

<div align="center">

**Local-first when possible. Useful before flashy. Document the weird parts.**

</div>

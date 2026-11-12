<div align="center">

# P.Choco

### Android & IoT · Weather Data · Local-first Tools

讓舊裝置延續使用，把氣象資料與系統診斷變成可靠、可驗證的工具。

<br>

![Taiwan](https://img.shields.io/badge/Based%20in-Taiwan-0F766E?style=flat-square)
![Android](https://img.shields.io/badge/Android-12%2B-3DDC84?style=flat-square&logo=android&logoColor=white)
![BLE](https://img.shields.io/badge/Focus-Bluetooth%20LE-2563EB?style=flat-square&logo=bluetooth&logoColor=white)
![Weather](https://img.shields.io/badge/Domain-Meteorology-0284C7?style=flat-square)
![Windows](https://img.shields.io/badge/Builds-Windows%20Tools-512BD4?style=flat-square&logo=dotnet&logoColor=white)

</div>

## What I build

我喜歡處理那些「硬體還好好的，只是軟體先離場」的問題；也重視可驗證的資料、清楚的能力邊界與本機優先設計。

- **Android & Systems** — Android IoT 復原、網路診斷、NAS 維運與 Windows 工具。
- **Weather & Data** — 氣象電碼解析、颱風路徑比較與衛星強度分析。
- **Web & Interactive** — 日常計算、教育故事、經營模擬與策略遊戲。

## 技術與取向

| 領域 | 技術與實作 |
| --- | --- |
| Android／IoT | Kotlin、Java、BLE、Wi-Fi Direct；舊裝置相容、連線與本機控制。 |
| 氣象資料 | WMO／ICAO TAC、ATCF、Dvorak／DVTS；解析、驗證、比較與視覺化。 |
| 系統工具 | Python、Rust、C#、VB.NET；CLI／MCP、Windows 工具、QNAP QTS 唯讀診斷。 |
| Web | HTML、CSS、JavaScript；純前端工具、互動故事與遊戲。 |
| 工程取向 | Local-first、隱私優先、唯讀優先、明確標示限制；重視自動化測試與 GitHub Actions CI。 |

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
| [Project Nanako](https://github.com/popuchoco/Project-Nanako) | Windows 本機檔案空間原型，提供使用者／權限、檔案管理與私人網路 HTTPS 存取；SMB 尚未實作，並非正式 NAS 替代品。 |

## Education Projects

| Project | Focus | One-liner |
| --- | --- | --- |
| [現金怎麼配｜新台幣拆鈔計算器](https://github.com/popuchoco/how-much-NTD-for-this) | 金錢與數學素養 | 精確計算新台幣紙鈔與硬幣的拆分組合及補足配法，並以生活例子練習估算與捨入；純前端，金額不儲存也不上傳。 |
| [你有禮貌嗎？](https://github.com/popuchoco/how-dare-you) | 生活禮儀與公共情境 | 透過六個家庭與公共場所情境，思考禮貌、現場指引與彼此需求；不設分數或人格排名。 |
| [夜嵐夜市](https://github.com/popuchoco/yelan-night-market) | 經營與經濟素養 | 以 2.5D 斜視角經營台灣港邊夜市，體驗成本、現金流、投資與會計週期。 |

## Computer Games

| Project | One-liner |
| --- | --- |
| [虹膜色彩校準｜Hue of the Fake](https://github.com/popuchoco/Alternate-Visual-Identification-Test) | 以色點辨讀與色相排序展開的短篇心理恐怖網頁遊戲，逐步讓校準結果與玩家記憶發生錯位。 |
| [火鍋湯底過濾挑戰](https://github.com/popuchoco/hotpot-filter-simulator) | 在不同湯底、食材與工具間挑戰撈沫與撈油，完成各種限時關卡並解鎖成就。 |
| [Project-TWN｜臺灣選戰模擬器](https://github.com/popuchoco/Project-TWN) | 以 Rust 打造的虛構臺灣選戰命令列策略遊戲，包含全國／地方選舉、候選人／幕僚與人民罷免模式；不是民調預測器。 |

---

<div align="center">

**Local-first when possible. Useful before flashy. Document the weird parts.**

</div>

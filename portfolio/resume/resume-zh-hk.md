# 蓋劍秋
iOS / 流動應用保安 / 全端開發

求職意向：iOS 開發 / 流動應用開發 / 前端及跨平台開發 / 全端開發

+86 13182870092 · +86 13182970092  
gaijianqiu@gmail.com · 616096372@qq.com
[Portfolio](https://kennaki.github.io/portfolio/)

## 個人簡介

**透過 AI 將編碼效率提升十倍以上：原預計約半年完成的 API 監測 Flink 項目，實際三週交付。熟練運用 Claude Code、Codex 處理重複編碼及伺服器端邏輯，將十多年工程經驗投入架構設計、文件不足的原生系統深度整合及複雜排障，並以像素級標準打磨 UI 視覺細節、互動回饋及操作流暢度，兼顧用戶體驗、系統穩定性及交付質素。**

在 iOS 保安領域，自主研發 hookengine 靜態程式庫，深入 Runtime、Mach-O 與現代連結機制，處理 Hook 偵測、誤報及宿主應用程式生命週期問題；在全端領域，獨立完成 API 保安分析流程及 Web 改造，從環境部署到數據統計口徑驗證，承擔完整交付責任。具備 Swift、SwiftUI 實戰經驗，應用於華米產品開發及電科院保安監測宿主應用程式，能結合現代介面開發、Objective-C 與底層 SDK 整合。

持有香港、澳洲、新西蘭、日本及申根地區的簽證或入境許可，可安排行程出席當地面試。大學英語六級（CET-6）高分通過，能以英語口頭表達自己的想法，現正準備 IELTS。

了解我的職業經歷與 AI 研發實踐: [https://kennaki.github.io/portfolio/about.html](https://kennaki.github.io/portfolio/about.html)

## 工作經驗

### 國網電力科學研究院有限公司 · 駐場項目
2022.04 — 2026.10 · 研發組副組長（2025） / 流動應用組長（2023） / iOS 開發

**Swift / SwiftUI / Objective-C / C / C++ / Java / Flink / Elasticsearch / Docker / Kubernetes**

- 自主研發流動應用保安監測 SDK 的 hookengine 靜態程式庫，負責安全接入 SDK 開發及維護，主導鴻蒙 SDK 研發與版本發佈；由端側開發拓展至團隊協作及全端交付。以 Swift、SwiftUI 開發保安監測宿主應用程式。
- 獨力運用 Claude Code、Codex 建立 API 即時分析流程，從 Mac mini 虛擬機環境搭建到內網部署，協調資源完成端到端交付。原預計約半年，實際三週交付。
- 項目論證與匯報：主導 2024、2025 年科技項目可行性研究、概要設計及詳細設計文件編寫，負責北京總部技術匯報。
- 重大問題處理：主動承擔 i國網 Android 耗電問題，跨技術棧研讀原始碼定位並修復；在總部匯報中以技術證據釐清責任，將團隊責任佔比降至 50%，並促成後續項目合作。

### 南京華米科技
2020.02 — 2022.03 · iOS 開發 / 裝置功能模組化項目負責人

**Swift / SwiftUI / Bluetooth / CBB / Git hooks**

- 推進 CBB 元件化方案研究及落地，負責裝置功能模組化項目的任務拆解、資源協調及進度管理。
- 華米任職期間全程使用 Swift、SwiftUI，開發及維護小米運動、Zepp 的健康、錶面、實驗室及世界時鐘模組，整合藍牙裝置與可重用功能，並整理 Git hook 工具及技術文件。

### 早期工作經驗
塗鴉智能（2018.10—2020.01）：商用 SDK、Wi-Fi 配網、ODM 客製化及 CI/CD；與華米階段共同累積藍牙、BLE Mesh 及模組化經驗。有貨（2016.03—2018.10）：潮流服飾電商、React Native、直播推流、小程式及 Native A/B 測試。途牛旅遊項目及早期流動應用開發（2012.10—2016.01，其中途牛任職 2014.03—2016.01）：iPad 大屏幕電商及旅遊詳情頁，深化 Objective-C Runtime、RunLoop 等原生技術基礎。

## 教育背景
南京中醫藥大學 · 全日制本科 · 管理學學士 · 2012 年畢業。具備閱讀英文技術文件及編寫商用 SDK 手冊的經驗。

## 精選項目

### iOS 保安監測 SDK · 自研 hookengine 靜態程式庫
iOS 研發負責人 · 原生保安與穩定性

- 供應商停止支援後，獨立負責 hookengine 靜態程式庫的自主研發，運用 Claude Code、Codex 從零建立核心偵測邏輯，涵蓋越獄、偵錯、動態程式庫注入、Hook 及網絡環境風險。
- 實作 Mach-O 傳統符號指標表及 Chained Fixups 匯入槽偵測，交叉核對磁碟原始匯入資料與執行期目標，處理 PAC 指標差異，補足現代連結機制下的偵測路徑。
- 利用 Objective-C Runtime 核對關鍵方法 IMP 所屬映像，結合系統程式庫、主程式及允許清單識別異常來源，並驗證 dladdr 等偵測依賴，減少入口遭竄改造成的盲點。
- 重整前後台及網絡變化觸發的偵測排程，加入有容量上限的事件快取及分路重試；持續排查並行處理、計時器生命週期及宿主穩定性問題。
- 以真實越獄、Frida 注入、Method Swizzling 及 GOT 改寫進行正反例驗證；排查正常裝置誤報、異常移除後的恢復及再次觸發，保留重現步驟、命中證據與自測紀錄。
- 以 Swift、SwiftUI 開發保安監測宿主應用程式，整合原生偵測 SDK，支援真機檢查偵測結果及應用程式生命週期行為。

Swift / SwiftUI / Objective-C / C / C++ / Runtime / Mach-O / GCD / LLDB
[項目詳情](https://kennaki.github.io/portfolio/projects/mobile-security.html)

### 安全接入平台 SDK · ISCP / SSAG
iOS SDK 及底層網絡開發維護

- 維護從 Objective-C 介面到 C/C++ 安全通道的完整呼叫鏈，改造基於 kqueue 的代理 I/O，完善 ACL 本地連接埠映射及連線狀態回呼。
- 針對網絡切換、並行重連及資源釋放崩潰進行跨層定位，完善狀態保護、重連防抖、DNS 及連接埠快取管理。
- 涵蓋 Wi-Fi／流動網絡切換、前後台及來電中斷等情境，整理整合說明、故障分析與回歸測試方法，支援業務應用程式接入。
- 將連線失敗拆解為介面狀態、非同步回呼、網絡路徑及底層資源問題，跨 Objective-C 與 C/C++ 呼叫鏈追蹤，兼顧 SDK 介面可用性及宿主生命週期。

Objective-C / C / C++ / Socket / OpenSSL / kqueue / Network.framework
[項目詳情](https://kennaki.github.io/portfolio/projects/secure-access.html)

### 流動應用 API 保安監測系統
單人全端交付 · AI 輔助開發

- 原預計約半年完成，實際三週交付；運用 Claude Code、Codex 加快實作，親自負責任務拆解、整合、驗證及部署。
- 從零建立 Zeek→Kafka→Flink→Elasticsearch 分析流程，接管及改造既有 Spring MVC Web 工程，取代供應商黑盒查詢介面，新增 API 資產彙總及展示。
- 實作時間窗口彙總、token 與裝置／IP 關聯偵測，並以約十萬筆裝置紀錄補全 H5 資料；完善風險、敏感數據、態勢圖表、篩選及匯出功能。
- 獨立協調並完成從 ARM 開發環境到 x86 隔離內網的部署，解決離線依賴、映像快取、欄位解析、索引類型及時間／計數口徑問題，整理測試與交接文件。
- 以 API、Host、Method 作為資產維度，區分存取明細與彙總資產；排查多個分析作業的重複計數、時區及缺失時間桶問題，統一圖表統計口徑。
- 逐層核對原始碼、JAR、容器映像及實際執行個體，定位舊映像快取與多模組依賴問題；以測試指令碼、已確認根因及交接文件支援內網交付。

Java / Flink / Zeek / Kafka / Elasticsearch / MySQL / Spring MVC / Docker / Kubernetes
[項目詳情](https://kennaki.github.io/portfolio/projects/api-security.html)

## 原生工程能力

結合 Swift、SwiftUI 產品開發與 Objective-C／C／C++ SDK 整合經驗，能從介面行為追蹤至執行期證據及底層資源生命週期，跨層定位問題。安全能力以真實攻擊樣本及正常裝置雙向驗證，兼顧異常移除後的恢復與再次觸發，並保留可重現步驟，支援後續回歸及交接。

## 工程方法與個人優勢

- 將 AI 融入實作、重構、測試指令碼及文件整理，先拆解可驗證任務，再依介面契約審查生成結果，以實際執行行為確認交付。
- 能串聯產品介面、原生執行期與後端數據流程；透過原始碼、回呼、日誌及部署產物排查問題，將已確認根因整理為可重現的檢查與交接文件。
- 兼具獨立交付與技術帶隊經驗：協調資源、整理設計決策，向相關人員說明複雜問題，同時親自處理關鍵技術難點。

早期項目與技術實踐: [https://kennaki.github.io/portfolio/#earlier](https://kennaki.github.io/portfolio/#earlier)

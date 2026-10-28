# Hi there, I'm 廖英盛 (Liao Ying-Sheng) 👋

### 全端軟體工程師 (Full-Stack Engineer) ｜ C# ASP.NET Core & Vue.js & WinForms

[![Online Resume](https://img.shields.io/badge/📄_線上履歷_(GitHub_Pages)-點擊瀏覽_A4_標準版-2563eb?style=for-the-badge)](https://sheng118137.github.io/Resume/)
[![Email](https://img.shields.io/badge/Email-shengliao379%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shengliao379@gmail.com)

> 💡 **關於我**  
> 具備在職系統維護優化實績與 6 年大型科技展會、政府數位專案統籌經驗。  
> 曾於**台北市電腦商業同業公會 (TCA)** 任職期間以 **C# ASP.NET MVC + MS SQL Server** 維護並優化展期活動系統（穩定服務逾 5 萬參觀人次）；後於**資策會 (III) / 資展國際 (iSpan) 全端網頁開發工程師養成班（159 期）**完成高強度實戰培訓並擔任**結訓專題組長**。擅長需求分析、關聯式資料庫設計、桌面應用 (WinForms) 與前後端分離架構開發。

---

## 🛠 技術能力 (Tech Stack)

### 後端與桌面應用開發 (Backend & Desktop)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![.NET Core](https://img.shields.io/badge/ASP.NET_Core_MVC_%2F_Web_API-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/Entity_Framework_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![WinForms](https://img.shields.io/badge/WinForms_(Windows_Forms)-0078D6?style=flat-square&logo=windows&logoColor=white)
![LINQ](https://img.shields.io/badge/LINQ_%2F_ADO.NET-512BD4?style=flat-square)

### 前端開發 (Frontend)
![Vue.js](https://img.shields.io/badge/Vue_3_(Vite_%2F_Pinia)-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript_(ES6%2B)-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5_%2F_CSS3-E34F26?style=flat-square&logo=html5&logoColor=white)
![Axios](https://img.shields.io/badge/Axios_%2F_jQuery_Ajax-5A29E4?style=flat-square&logo=axios&logoColor=white)

### 資料庫與系統整合 (Database & Tools)
![MSSQL](https://img.shields.io/badge/MS_SQL_Server_(T--SQL)-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Git](https://img.shields.io/badge/Git_%2F_GitHub_Flow-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Gemini API](https://img.shields.io/badge/Google_Gemini_API-4285F4?style=flat-square&logo=google&logoColor=white)
![ECPay](https://img.shields.io/badge/綠界金流_(ECPay)-00A650?style=flat-square)

---

## 💻 代表軟體開發專題 (Featured Projects)

### 1. [書嶼 BookISLE — 前後端分離線上書店電商平台](https://github.com/sheng118137/BookISLE)
- **擔任角色**：團隊專題組長 ＆ 核心架構開發
- **使用技術**：`Vue 3 (Vite / Pinia)`、`ASP.NET Core MVC & Web API`、`EF Core`、`MS SQL Server`、`Google Gemini API`、`綠界金流 (ECPay)`
- **核心實作亮點**：
  - **架構統籌與版控規範**：制定 Git Flow 分支管理與 RESTful API 介面規格，主導底層架構建置、資料庫整合與跨模組除錯支援。
  - **無限階層分類與動態麵包屑**：採用**資料表自我關聯 (Self-Referencing)** 結構設計，結合遞迴查詢與反向排序演算法，實作多層級圖書分類管理與前台動態麵包屑導覽。
  - **第三方金流驗簽與交易一致性**：串接**綠界金流 (ECPay)** 刷卡流程與 Server 端回傳驗簽機制，確保付款授權成功後自動更新訂單狀態並精準扣減庫存。
  - **AI 智慧客服與評論權限控管**：整合 **Google Gemini API** 實作自然語言找書推薦與即時訂單查詢客服；開發商品 CRUD 模組、登入限定評論驗證與後台精選管理功能。

### 2. [Smart Coffee System — 咖啡廳 POS 與後台營運管理系統](https://github.com/sheng118137/SmartCoffeeSystem)
- **擔任角色**：個人專題（獨立全端開發）
- **使用技術**：`C#`、`WinForms`、`Entity Framework`、`ADO.NET`、`LINQ`、`MS SQL Server`
- **核心實作亮點**：
  - **客製化計價引擎與會員系統**：實作 POS 收銀點餐流程，支援飲品甜度、冰塊、加料動態計價邏輯，並整合會員分級折扣與消費積分累點／折抵機制。
  - **混合資料存取與關聯完整性**：結合 EF + LINQ 與 ADO.NET 開發商品、分類、會員與訂單完整 CRUD；設計嚴謹之外鍵約束 (Foreign Key)、Transaction 交易控管與防呆驗證，防止誤刪關聯資料並確保庫存一致性。
  - **RBAC 權限控管與營運報表**：運用 LINQ 彙整銷售數據繪製視覺化營收圖表；實作多角色權限隔離（店長／店員）與 T-SQL 一鍵式資料庫備份功能。

---

## 💼 實務工作經歷與系統維護實績 (Work Experience)

| 期間 | 公司 / 單位 | 職稱 | 關鍵技術與專案實績 |
| :--- | :--- | :--- | :--- |
| **2023/02 ~ 2026/06** | **台北市電腦商業同業公會 (TCA)** | 專案企劃 ＆ 活動網站維護優化 | • **2025 高雄智慧城市展 (KSCSE) 展期活動系統維護優化**：運用 **C# ASP.NET MVC、MS SQL Server、jQuery/Ajax、Bootstrap 5** 修正資料存取邏輯與前端顯示，穩定服務逾 **50,000 名**展會參觀者。<br>• 主責 3 屆大型科技展會與 75+ 場專業論壇統籌，對接上市櫃科技大廠與政府單位，收斂業務需求並轉化為系統規格。 |
| **2022/02 ~ 2023/01** | **承鴻企業行** | 專案管理主管 (主企劃) | • 主導經濟部數位群聚計畫與標案規格書撰寫、預算控管及結案驗收。<br>• 主持「古坑桌球村」智慧科技場域活化專案，於全國 104 個團隊中榮獲數位發展部**全國亞軍**及**服務推廣獎**。 |

---

## 🏆 專業培訓與獲獎榮譽 (Education & Awards)

- **資策會 (III) / 資展國際 (iSpan)** — 全端網頁開發工程師養成班 159 期（擔任結訓專題組長）
- **國立虎尾科技大學** — 休閒遊憩系 碩士 & 學士（碩士期間主導經濟部 SBIR 科技數位旅遊計畫）
- 🏅 **數位發展部「創業歸故里競賽」** — 全國亞軍 ＆ 服務推廣獎（智慧科技場域應用）
- 🏅 **教育部青年發展署全國競賽** — 全國優秀企劃設計獎 ＆ 夢想實踐家亞軍

---

## 📬 聯絡方式 (Contact)

- **線上互動式 A4 履歷 (可切換單/雙頁與下載 PDF)**：[https://sheng118137.github.io/Resume/](https://sheng118137.github.io/Resume/)
- **Email**：[shengliao379@gmail.com](mailto:shengliao379@gmail.com)
- **求職地點**：高雄 / 台南 / 遠端

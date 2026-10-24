# 台灣 5–30 人中小企業「AI 工作流程自動化」一人顧問事業：市場可行性研究筆記（截至 2026-10-24）

> 研究範圍：n8n / Make / Zapier + LLM、Google Workspace / Microsoft 365 自動化，賣給 5–30 人公司（貿易商、工程行、小型電商、記帳/會計事務所），商業模式為付費診斷 → 固定範圍「30 天衝刺」專案 → 月維護費。
> 匯率附註：本筆記未查證即時匯率，推論處以約 NT$30–32／USD、NT$33–35／EUR 粗估，報告撰寫者請自行校正。
> 資料可信度：多數政府數據透過工商時報／旺得富等媒體轉述，未直接取得原始報告 PDF；第三方工具定價整理文已與官方頁面交叉比對（n8n、Zapier 已直接抓官方頁；Make 官方頁未顯示價格，數字來自第三方 2026-09 查核）。

## 1. 需求訊號與市場規模

### Takeaway
台灣有約 171.6 萬家中小企業（占全體企業 98% 以上），數位基礎普及（僅 0.7% 未數位化），但 AI 實際導入率只有約 7.4%，超過九成老闆對 AI 只有粗淺或完全不了解。最大障礙是「不知道要用在哪裡」，而不是預算。對「先做付費診斷、把需求講清楚」的服務來說，這是正面訊號。

### Cited Findings
- 「2025 中小企業白皮書」（經濟部，2025-12-26 發表）：2024 年中小企業 171.6 萬家，就業人口約 919.4 萬人，銷售額 31.1 兆元；家數占全體企業 98% 以上，提供近 8 成就業機會 — [旺得富/工商時報 2025-12-27](https://wantrich.chinatimes.com/news/20251227900033-420501)、[旺得富 2025-12-27](https://wantrich.chinatimes.com/news/20251227900014-420501)
  - 不同報導對中小企業銷售額寫法不一，有 31.1 兆與 31.7 兆兩種（全體企業 59.7 兆，中小企業占比破 5 成），需以白皮書原文為準 — 同上兩篇
  - 舊口徑：2020 年 154 萬 8,835 家、占 98.93%（2020-06-24 修正〈中小企業認定標準〉後，統計數字明顯增加）— [工商時報 2021-10-31](https://www.ctee.com.tw/news/20211031700403-431204)
- 「2025 年中小企業 AI 運用現況調查」：由中企署委託工研院執行，對象為 199 人以下公司，22 縣市共 1,207 份有效樣本 — [旺得富 2025-12-26](https://wantrich.chinatimes.com/news/20251226900494-420501)
  - 0.7% 尚未數位化；15% 的關鍵營運數據達「可視化／預測模擬／數據加值」等級 — 同上
  - 86% 表示「僅稍微瞭解／大致了解 AI」，6.5% 完全不了解，合計超過 92% — 同上
  - 15% 有 AI 人才，85% 沒有；有 AI 人才的企業中約 75% 只是操作現成工具的初階人才 — 同上
  - 生成式 AI 使用率「近 7 成」（報導沒有說明分母定義）— 同上
  - 障礙依序為：尚無明確應用需求 → 不理解 AI → 導入成本高 → 人才短缺 → 成效難以評估（報導沒有給各項百分比）— 同上
  - 有 13 個行業「充分了解 AI」的比例不到 1 成，包括金屬製品、機械設備、食品飼料、電力設備、營建工程、運輸倉儲、不動產、支援服務等 — 同上
- 依 2025 白皮書，國內僅 7.4% 中小企業實際導入 AI；同一報導引用的 OECD 全球中小企業導入率為 39%。超過六成企業認為最大挑戰是「尚無明確應用需求」— 搜尋摘要引自 [工商時報 2026-01-08](https://www.ctee.com.tw/news/20260108701350-430701)、[旺得富 2026-01-08](https://wantrich.chinatimes.com/news/20260108900446-420201)（摘要轉述，未逐字核對原文）
- 政策目標為 2028 年 AI 普及率達 50%；前經濟部長郭智輝認為，許多中小企業根本問題是尚未真正數位化 — 同上搜尋摘要來源（[工商時報 2026-04-13](https://www.ctee.com.tw/news/20260413701714-430104)、[2026-04-14](https://www.ctee.com.tw/news/20260414700101-430104)）
- IDC 2026 台灣 ICT 趨勢：54% 企業計畫增加 AI 投資（經 TechOrange 二手引用）— [恆遠數位 2026-04-24](https://foreverwebs.com/blog/ai-budget-breakdown-100k-500k-2m-taiwan-sme-2026)
- 國際對照（非台灣）：日本中小企業生成式 AI 利用率從 2024 年度 55.2% 升到 2026 年度 96.2%（N=106，小樣本），用途以「事務・後勤業務」87.5% 最高 — [PR TIMES](https://prtimes.jp/main/html/rd/p/000000008.000108242.html)
- 國際對照：美國 Duke CFO 調查中，過去 12 個月有自動化任務的組織約 37% 使用 AI；自動化範圍包括付款給供應商、開發票、採購、財務報告 — [HCAMag](https://www.hcamag.com/us/specialization/hr-technology/1-in-2-employers-to-adopt-ai-in-automating-employees-tasks-survey/496394)

### Inferences
- 5–30 人公司若以白皮書口徑（多數是 5 人以下微型企業）推算，目標客群只占 171.6 萬的一部分，但絕對數量仍有數萬至十萬家級。這是推論，白皮書的員工規模分布表本次未取得。
- 「尚無明確應用需求」排第一位，代表市場缺的是「幫我找出該自動化什麼」的診斷服務。付費診斷作為入口產品，和這個痛點直接對應。
- 生成式 AI 使用率近 7 成，導入率卻只有 7.4%，可能代表老闆和員工已經在用 ChatGPT，但沒有把它串進流程。從「個人用 ChatGPT」升級到「流程自動化」，是可以主打的敘事。
- 想自動化的後勤工作，可從國際調查（事務後勤、發票、採購、報表）和台灣顧問案例（Email 分類、PDF/OCR 擷取、跨店報表）推估：報價／詢價單整理、訂單 → Excel/ERP、發票/收據 OCR、客服信件分類、每日業績報表、LINE 通知。

### Gaps
- 沒有找到台灣官方調查中「中小企業最想自動化哪些後勤任務」的百分比排名。工研院調查報導沒有細分用途，需要查白皮書或調查原文。
- 白皮書中 5–29 人企業的家數未取得。
- 沒有找到 104、資策會 MIC 在 2026 年發布的中小企業 AI／自動化調查（搜尋無結果）。
- 7.4% 導入率的原始定義（樣本、年度）未核實。

## 2. 政府補助與計畫（2026 年現況）

### Takeaway
2026 年經費很多（經濟部預告 2027 年起每年 250 億、目標百萬家導入 AI），但現行主力計畫多由法人（工研院等）及「輔導團」執行，且 2026 年各梯次大多已截止。目前沒有找到「一人工作室可直接登錄成補助供應商」的明確管道。對一人顧問來說，補助比較適合當行銷話題，或用來和法人／記帳士網絡合作，不宜當主要收入來源。

### Cited Findings
- 「中小微企業 AI 創新應用輔導」（115 年度，中企署）：2026-04-02 宣布受理，分「行業通用型」和「體系創新型」雙軌，目標 2,500 家，受理至 2026-04-30 17:00，隨到隨審、額滿為止。報導沒有寫每家補助金額、自付比例或服務商資格，需查 sme.gov.tw/list-tw-2275 — [工商時報 2026-04-10](https://www.ctee.com.tw/news/20260410700385-439901)
- 「提升中小企業智慧化經營效能計畫」：以診斷、培訓、導入三種模式推動，申請期限 115-03-10（已截止）— [優分析](https://uanalyze.com.tw/articles/2629447366)
- 「中小企業網路大學校計畫」：單一企業最高補助 15 萬元，聯合型最高 30 萬元，以 AI 人才培育為重點，受理至 7 月底（已截止）— 搜尋摘要（來源見 [iThome](https://www.ithome.com.tw/news/157092)、[工商時報 2026-01-15](https://www.ctee.com.tw/news/20260115700319-439901)；未逐字核對）
- 經濟部產發署「產業競爭力輔導團」：2025-10 啟動，由工研院、精機、金工、石資中心設區域輔導中心，另有 44 個次產業輔導團，提供「諮詢診斷 → 進廠輔導 → AI 工具導入」；截至 2026-03 底輔導 2,058 家，其中中小企業占 91% — [工商時報 2026-04-14](https://www.ctee.com.tw/news/20260414700101-430104)
  - 之後累計輔導超過 1 萬家，2026-09 報導為超過 1.3 萬家 — 搜尋摘要（[CNA 2026-08-05](https://www.cna.com.tw/news/afe/202608050235.aspx)、[udn](https://udn.com/news/story/7240/9638300)）
- 2025 年（114 年度）官方 DM：階段一為專家進廠診斷 AI 成熟度，政府補助 18 萬、企業自付 2 萬；階段二為 AI 應用導入，個案最高補助 500 萬（2025 年資料，2026 是否沿用未知）— [TMTS 114 年度診斷服務 DM](https://www.tmts.tw/storage/tmba/files/2025年2月/產業聚落供應鏈數位串流暨AI應用-主題是研發計畫/114年度診斷服務DM.pdf)
- 「中小微企業社會發展計畫」（2026–2029 四年期）：總預算 42.5 億元，其中 21 億協助高潛力中小企業導入數位平台與 AI 工具、10.4 億媒合新創、約 7.9 億做碳帳（與記帳公會體系合作）、3.2 億做海外拓展；目標培育 5.3 萬人次、為 10 萬家次建立碳排資料 — [工商時報 2026-02-13](https://www.ctee.com.tw/news/20260213700065-430104)
  - 「中小微企業碳健檢與財會 AI 應用計畫」針對沒有專職財會人員的企業，透過全國記帳士與報稅代理人網絡，在記帳時同步完成碳帳 — 同上
  - AI 財會課程（分服務業／製造業、初階／中階）由中企署全額補助，學員可免費試用 AI 財務軟體 — 搜尋摘要（[工商時報 2026-02-12](https://www.ctee.com.tw/news/20260212701563-430104)）
  - 前身「中小微企業多元振興發展計畫」（2025-01-14 啟動）累計輔導 24.7 萬家，協助 4.3 萬家導入 AI 與數位工具 — [工商時報 2026-02-13](https://www.ctee.com.tw/news/20260213700065-430104)
- 擴大方案：經濟部長龔明鑫 2026-09-15 表示，明年（2027）起每年投入高達 250 億元，目標協助 100 萬家中小微企業導入或應用 AI；資金來源為總統 2026-05 宣布的「8 年加碼 1,000 億」；行政院研擬《中小微企業轉型升級發展條例》草案（含租稅優惠），預計 9 月送立法院，是否已送出或通過未確認 — 搜尋摘要（[優分析](https://uanalyze.com.tw/articles/6586755318)、[工商時報 2026-07-31](https://www.ctee.com.tw/news/20260731700113-430101)、[CIO](https://www.cio.com.tw/96951/)）
- 「小型企業人力提升計畫」（勞動部勞發署）：補助 50 人以下企業辦理在職訓練，並有顧問輔導；115 年度已開放受理；部落格稱前 1–3 年可全額補助、之後遞減（非官方說法）；官方入口為 onjobtraining.wda.gov.tw — [udn 部落格](https://blog.udn.com/b590437d/189216696)、[勞發署簡報 PDF](https://www.tmts.tw/storage/tmba/files/2025年11月/勞動部提供企業人才培訓相關服務措施.pdf)、[CNA](https://www.cna.com.tw/postwrite/chi/390263)
- 名為「雲世代」的 2026 年補助計畫：本次搜尋沒有找到現行版本，可能已結束或改名 — 搜尋結果（無直接來源）

### Inferences
- 一人顧問現實上可走三種路：（1）當「小人提」課程的外聘講師或顧問，由客戶以補助款付訓練費；（2）成為法人輔導團或次產業輔導團的協力廠商或分包；（3）把「2027 年 250 億擴大方案」當銷售話術，提醒客戶先做好準備、再搭補助。三條路的資格規定都要再查證。
- 碳帳／財會 AI 計畫走的是記帳士網絡，記帳士因此有政策誘因接觸 AI 工具，可能是合作或轉介的切入點。
- 補助案多採「隨到隨審、額滿為止」，申請窗口在年初（3–4 月）。想利用 2027 年方案，應在 2027 年第一季前和客戶談好。

### Gaps
- 每個 2026 計畫的每家補助金額、自付比例、服務商登錄資格都沒有取得，需要中企署申請須知原文。
- 一人工作室（行號或個人）能不能成為補助案的合格服務供應商：沒有找到明確規定。
- 2027 年 250 億方案的具體子計畫、條例草案的立法進度未確認。
- 「小人提」115 年度講師鐘點費上限與每家補助額度未取得。

## 3. 競爭者與價格水準

### Takeaway
台灣已經有自稱 n8n／AI 自動化顧問的個人或工作室，公開報價為專案 NT$5 萬起、常見 5–15 萬、多系統 15 萬以上，並以「免費診斷」當入口。PRO360 平台所有類別專家平均時薪約 NT$646。國際接案平台的 n8n 服務從每件 €17 到 US$497 一週方案都有，價格帶很寬。這門生意的定價錨點大約在「單一流程 5 萬」上下。

### Cited Findings
- Darrell TW（台灣 n8n 顧問，第一人稱經營，品牌為「Darrell TW · Automation Studio」，頁尾 © 2026）：專案 5 萬起，常見 5–15 萬，多系統 15 萬以上；提供免費診斷（填表後 48 小時內評估）；時薪諮詢和維護方案都沒有公開價格；交期為單一流程 2–4 週、多系統整合 4–8 週；案例包括 AI 客服信件分類（Gmail + Sheets）、批次 PDF/OCR 擷取、一張表發布五個社群平台、多分店每日營運報表等 — [darrelltw.com/n8n-expert](https://www.darrelltw.com/n8n-expert/)
- 恆遠數位（台灣中小企業 AI 預算指南，2026-04-24，最後修改 2026-10-17）：
  - 10 萬以下（5–15 人）：月固定成本 NT$900–1,200；n8n 建置 NT$3,000–5,000、培訓 NT$1–2 萬、提示詞範本 NT$5,000–1 萬；建議每月保留 NT$3,000–5,000 維護預算 — [恆遠數位](https://foreverwebs.com/blog/ai-budget-breakdown-100k-500k-2m-taiwan-sme-2026)
  - 30–50 萬（15–50 人）：客製工作流 NT$5–10 萬、整合 2–3 個系統 NT$8–15 萬、維護 NT$3–5 萬（每季調整）；顧問一般 1–2 個月上線 — 同上
  - 100–200 萬（50–200 人）：六個月維護合約 NT$12–24 萬（約每月 NT$2–4 萬）— 同上
  - 成本結構：工具訂閱 20–30%、API 10–20%、整合開發 20–30%、培訓 10–15%、維護迭代 15–25%；資料清理通常需 2–4 週 — 同上
  - 注意：該文由顧問公司撰寫，帶行銷性質，部分數字前後不一致（例如年度工具費超過該級距總預算）— 同上
- 一份台灣預算指南引用 SmartDev：軟體授權只占 AI 導入總成本 30–50%；引用 gigCMO：年費 NT$4 萬的工具加上整合、培訓、維護後，可達 NT$11–13 萬 — [恆遠數位](https://foreverwebs.com/blog/ai-budget-breakdown-100k-500k-2m-taiwan-sme-2026)
- PRO360 達人網：自稱 500+ 服務類別、每月媒合 10 萬+ 案件、5 萬+ 專家在線，所有類別專家平均時薪 NT$646 — [Yourator PRO360 公司頁](https://www.yourator.co/companies/PRO360)
  - PRO360 網頁設計參考行情：一頁式 NT$1–5 萬、形象網站 NT$2–10 萬+、電商 NT$3–30 萬+（網頁設計，不是自動化，只能當鬆散參考）— [PRO360 blog](https://www.pro360.com.tw/blog/web_design_freelancer/)
  - PRO360 高雄地區個別軟體外包需求的預算，從 NT$1 萬以下到 NT$5–10 萬都有（單一案例，不是平均）— [PRO360 高雄程式外包](https://www.pro360.com.tw/nearme/software_outsourcing/高雄市/鹽埕區)
- 國際接案平台的 n8n 服務：Contra／Freelancehunt 上有每件 €17 起的方案，也有一週交付、US$497 起的方案；常見範圍定義方式為「每個工作流最多 20 個節點、不含子流程」或「最多 5 個客製工作流、3 輪修改」，並要求客戶事先提供 API 金鑰和帳號權限 — 搜尋摘要（[Upwork n8n consultation](https://www.upwork.com/services/product/development-it-n8n-automation-consultation-and-evaluation-2072801924536675096)、[Contra](https://contra.com/s/6XPUgMZm-business-process-automation-with-n8n)、[Fiverr](https://fiverr.com/khatrifaiz/build-n8n-automations-and-workflows)）
- 其他台灣同業與內容行銷者（n8n／Make 比較文、教學）：恆遠數位、Leadion、es2idea、Yourator 專欄等，都在經營 2026 年「n8n vs Make vs Zapier」的中文 SEO 內容 — [Leadion](https://leadion.ai/blog/n8n-zapier-make-comparison/)、[恆遠數位 Make 教學](https://foreverwebs.com/blog/make-com-automation-tutorial-smb)、[es2idea](https://blog.es2idea.com/posts/n8n-vs-make-automation-comparison/)、[Yourator](https://www.yourator.co/articles/968)
- 政府輔導團（工研院等法人）提供 AI 診斷，2025 年 DM 價格為政府補助 18 萬、企業自付 2 萬。這是一人顧問的間接競爭者，也是價格錨點 — [TMTS DM](https://www.tmts.tw/storage/tmba/files/2025年2月/產業聚落供應鏈數位串流暨AI應用-主題是研發計畫/114年度診斷服務DM.pdf)

### Inferences
- 一人顧問的專案定價合理區間：「30 天衝刺」1–3 個流程報 NT$4–12 萬，與 Darrell 的 5–15 萬接近；付費診斷 NT$3,000–15,000（可折抵專案費）；月維護 NT$3,000–15,000／家（恆遠數位小型級距建議保留 3,000–5,000／月，中型約每季 3–5 萬）。這些是推論，不是市場實測。
- 競品多以「免費診斷」當入口，堅持收診斷費需要更強的交付物，例如流程地圖、ROI 試算、可直接執行的提案。收費方式也可改為「診斷費可全額折抵專案」。
- PRO360 全類別平均時薪 NT$646，可見平台上的買家價格敏感。高價專案不適合靠平台接，平台比較適合當早期案例來源。

### Gaps
- 沒有找到 Tasker 出任務、104 外包網上「n8n／自動化／RPA」類案件的平均預算或成交價（搜尋結果偏離主題）。
- 沒有找到台灣 RPA／AI agency（例如 UiPath 經銷商）對小型企業的公開報價。
- 沒有找到台灣顧問公開的月維護費實際數字。
- Upwork 上 n8n 專家的時薪分布未取得具體數據。

## 4. 工具與成本（2026 年定價）

### Takeaway
入門工具費很低：n8n Cloud Starter 約 €20/月（年繳），Make Core 約 US$9/月（年繳、10k credits），Zapier Pro 約 US$19.99/月（年繳、750 tasks），自架 n8n 只需 VPS 費 US$5–20/月。輕量 LLM API（GPT-5 mini、Gemini 2.5 Flash）每百萬 token 輸入約 US$0.25–0.30。每位客戶每月的執行成本大多在 NT$300–2,000 之間，毛利空間在人工時數，不在工具差價。

### Cited Findings
- **n8n 官方定價頁**（2026-10 抓取，頁面只顯示年繳價）— [n8n.io/pricing](https://n8n.io/pricing/)
  - Starter：€20/月（年繳），2,500 executions/月，並行 5，1,600 Assistant credits，1 個共享專案，log 保留 7 天，單次執行最長 5 分鐘
  - Pro：€50/月（年繳），10,000 executions/月，並行 20/50，最多 9,600 Assistant credits，3 個共享專案，log 保留 30 天
  - Business：€667/月（年繳），40,000 executions/月，只能自架，含 SSO/LDAP、Git、多環境；超量每 30 萬 executions 收 €4,000；一個授權金鑰可用於無限個實例，但用量合併計算
  - Enterprise：洽詢；Community Edition 可在 GitHub 免費自架
  - Cloud 試用：1,000 executions、並行 5、180 秒逾時
- n8n 月繳價：Starter €24、Pro €60（第三方整理）；一個每 5 分鐘輪詢一次的 trigger 每月約用掉 8,640 executions — [Jetadmin 2026-09-26](https://www.jetadmin.io/blog/n8n-pricing/)、[Activepieces](https://www.activepieces.com/blog/n8n-pricing-2026-plans-free-tier-costs-explained.md)
- n8n 公平程式碼（fair-code）授權：作者解讀為「把 n8n 當付費託管服務提供給客戶需要企業授權；收顧問費幫客戶建工作流則可以」（作者解讀，非法律意見）— [Shareuhack 2026-05-25](https://www.shareuhack.com/zh-TW/posts/n8n-automation-solopreneur-taiwan-guide-2026)
- 自架主機：Railway 一般用量約 US$5/月、重度約 US$14/月；Fly.io 約 US$5–10；一般 VPS 約 US$5–20/月（作者估計）。自架需每 1–2 個月檢查版本更新並設定錯誤通知工作流 — [Shareuhack](https://www.shareuhack.com/zh-TW/posts/n8n-automation-solopreneur-taiwan-guide-2026)
- **Make**：官方頁不顯示價格。2026-09 第三方查核為 Free 1,000 credits/月；Core US$9／Pro US$16／Teams US$29（年繳，10k credits/月）；月繳分別為 US$10.59／US$18.82／US$34.12。Zapier 部落格列的 US$12／21／38 可能是舊價 — [Latenode](https://latenode.com/blog/make-com-pricing)、[Jetadmin 2026-09-26](https://www.jetadmin.io/blog/make-pricing/)、[Zapier blog](https://zapier.com/blog/make-com-pricing/)
  - Make 官方：多數模組每次操作 1 credit，使用 Make AI Provider 的進階功能可能耗更多 credits；Router 和錯誤處理模組不計 credit；另有 20 人以下組織的 Start-up Plan（「Business」方案 5 折）— [make.com/en/pricing](https://www.make.com/en/pricing)
- **Zapier 官方定價頁**（2026-10 抓取）— [zapier.com/pricing](https://zapier.com/pricing)
  - Free：100 tasks/月，只能建兩步驟 Zap，15 分鐘輪詢
  - Professional：750 tasks 級距月繳 US$29.99、年繳 US$19.99/月；多步驟 Zap，2 分鐘輪詢，1,500 Agent activities/月
  - Team：2,000 tasks 級距月繳 US$103.50、年繳 US$69/月，最多 25 人
  - 超量計費：月繳方案為基本費率 2.5 倍，年繳為 1.25 倍；用量到訂閱量 3 倍時停止
- **LLM API**（第三方彙整，2026-09 前後）：GPT-5 mini 每百萬 token 輸入 US$0.25／輸出 US$2.00；Gemini 2.5 Flash 輸入 US$0.30／輸出 US$2.50 — [anotherwrapper](https://anotherwrapper.com/tools/llm-pricing/gpt-5-mini-2025-08-07/gemini-2.5-flash)
- 台灣顧問文估算：中型案（15–50 人）Claude API 用量 NT$1,500–5,000/月；小型案（5–15 人）月固定成本（n8n 自架、Claude Pro、Workspace 等）NT$900–1,200 — [恆遠數位](https://foreverwebs.com/blog/ai-budget-breakdown-100k-500k-2m-taiwan-sme-2026)
- LINE Notify 已在 2025 年停止服務，舊工作流會失效，必須改用 LINE Messaging API — [Shareuhack](https://www.shareuhack.com/zh-TW/posts/n8n-automation-solopreneur-taiwan-guide-2026)

### Inferences
- 每位客戶每月執行成本推估：一個 n8n Starter（約 NT$700–850）或分攤自架 VPS（約 NT$150–600），加上 LLM API（輕量模型處理數百至數千份文件，約 NT$30–1,000），合計大約 NT$300–2,000/月。主要變數是輪詢頻率和文件量。
- 一人顧問可以自架一台 n8n 服務多個客戶。但依 fair-code 授權的解讀，「代管 n8n 並收費」可能要另外取得授權，比較穩妥的做法是讓客戶自己開 Cloud 帳號（客戶付費、所有權歸客戶），顧問只收建置和維護費。這點需要法律確認。
- 台灣小企業 M365 普及率不低，Make 和 Zapier 的 Microsoft 365 連接器比 n8n 成熟。工具選擇可以依客戶環境決定：Google 系客戶用 n8n 或 Make，M365 系客戶用 Make、Zapier 或 Power Automate。這是推論，本次沒有查 Power Automate 價格。
- LINE Messaging API 是台灣客戶的關鍵整合點，免費訊息額度和超量費用本次未查（見 Gaps）。

### Gaps
- OpenAI、Google、Anthropic 官方定價頁未直接抓取，LLM 價格只有第三方數字。Claude 系列價格未查。
- Make 官方頁未顯示價格，數字為第三方 2026-09 查核。
- Microsoft Power Automate、Google Workspace 2026 年台灣售價未查。
- LINE 官方帳號 2026 年台灣訊息方案價格未查。

## 5. 交付產能與常見失敗模式

### Takeaway
公開資料顯示，單一流程從建置到穩定約需 2–4 週，多系統整合需 4–8 週，資料清理另需 2–4 週。這代表「30 天衝刺」只適合 1–3 個邊界清楚的流程。一人可同時服務的客戶數沒有找到可靠統計，需要自行推估。

### Cited Findings
- 交期：單一流程 2–4 週，多系統整合 4–8 週 — [Darrell TW](https://www.darrelltw.com/n8n-expert/)
- 中型案顧問一般 1–2 個月上線；大型案分 3–4 階段、每階段 2–3 個月；資料清理通常 2–4 週 — [恆遠數位](https://foreverwebs.com/blog/ai-budget-breakdown-100k-500k-2m-taiwan-sme-2026)
- 時間估計（作者估計，文章由 AI agents 撰寫、未經人工逐篇審查）：第一個 onboarding 工作流約 1–2 小時，Google OAuth 設定另加 30–60 分鐘；穩定的複雜工作流需 2–4 週；學習曲線為 2–3 週跑通第一個實用工作流、1–3 個月穩定 — [Shareuhack](https://www.shareuhack.com/zh-TW/posts/n8n-automation-solopreneur-taiwan-guide-2026)
- 維護內容包括：每 1–2 個月檢查版本更新、建立錯誤通知工作流；Railway 免費方案會休眠，導致排程失效；Make/Zapier 遷移到 n8n 需手動重建；Google 憑證需另外在 Google Cloud Console 建立 — 同上
- 第三方 API 停止服務的風險：LINE Notify 在 2025 年停止服務 — 同上
- 維護迭代占導入總成本 15–25%，內容包括模型更新、工作流調整、bug 修復；API 用量在上線後可能大幅增加 — [恆遠數位](https://foreverwebs.com/blog/ai-budget-breakdown-100k-500k-2m-taiwan-sme-2026)
- 接案者常見的範圍控制寫法：限制節點數或流程數、限制修改輪數（例如 3 輪）、事先取得 API 金鑰和權限 — 搜尋摘要（[Contra](https://contra.com/s/qoYMLNrl-n8n-workflow-automation-100percent-working-automated-flows)、[Fiverr](https://fiverr.com/khatrifaiz/build-n8n-automations-and-workflows)）
- 數位成熟度：只有 15% 中小企業的關鍵數據達可視化以上等級，代表多數客戶的資料仍分散在 Excel、LINE、紙本 — [旺得富 2025-12-26](https://wantrich.chinatimes.com/news/20251226900494-420501)

### Inferences
- 每案工時推估：診斷 6–12 小時（訪談、流程盤點、報告），30 天衝刺 30–60 小時（1–3 個流程，含測試、教育訓練、文件），維護每客戶每月 2–6 小時（監控、錯誤處理、小幅調整）。
- 同時服務量推估：一人每月可用的交付時數約 100–120 小時（另扣除業務和行政時間），可同時跑 2–3 個衝刺專案，並維護 10–20 家月費客戶。維護客戶多了以後，產能會被異常處理吃掉，需要標準化監控和錯誤通知。
- 主要失敗模式：（1）資料混亂，例如料號不一致、Excel 欄位隨意，資料清理可能超過 30 天；（2）客戶 IT 限制，例如舊版 ERP 沒有 API、只用桌機版 Excel、M365 管理員權限不在老闆手上、外包 IT 不配合；（3）範圍蔓延，例如「順便幫我再做一個」；（4）第三方 API 變更，如 LINE Notify；（5）帳號所有權不清，例如用顧問的帳號建置，日後交接困難；（6）客戶內部沒有負責人，上線後無人使用。
- 「30 天衝刺」需要以合約明訂流程數上限、修改輪數、客戶提供資料和權限的時間點，延遲時間不計入 30 天。

### Gaps
- 沒有找到台灣或亞洲一人自動化顧問「同時服務客戶數」或「每案實際工時」的可靠統計，上述數字皆為推論。
- 沒有找到台灣中小企業常用 ERP（鼎新、正航、文中等）的 API 開放程度資料。

## 6. 銷售通路（GTM）、常見反對意見與案例

### Takeaway
公開資料中，台灣同業主要靠中文 SEO 內容（n8n/Make/Zapier 比較、教學、預算指南）加上免費診斷表單獲客，並搭配企業內訓與工作坊。記帳士網絡已被政府計畫用來推動財會 AI，是有政策背書的轉介通路。商會、BNI、LinkedIn 對這類服務的成效，沒有找到台灣實證資料。

### Cited Findings
- 台灣同業的獲客形式：個人網站 + 免費診斷表單（48 小時回覆）+ 案例頁 + 企業內訓與工作坊三種服務 — [Darrell TW](https://www.darrelltw.com/n8n-expert/)
- 多家台灣業者經營 2026 年中文比較文和教學（SEO 內容行銷）— [恆遠數位](https://foreverwebs.com/blog/n8n-vs-make-vs-zapier-comparison-2026)、[Leadion](https://leadion.ai/blog/n8n-zapier-make-comparison/)、[es2idea](https://blog.es2idea.com/posts/n8n-vs-make-automation-comparison/)
- 恆遠數位〈n8n + ChatGPT 企業自動化實戰：6 個真實案例〉也是以案例內容導流 — [恆遠數位](https://foreverwebs.com/blog/n8n-chatgpt-enterprise-automation-cases-2026)
- 科技新報 2026-01-27 報導 n8n 成為學習者投入數位技能的新入口，並強調可自架、重視資料隱私的企業特別有興趣 — [TechNews](https://technews.tw/2026/01/27/n8n/)
- 政府用記帳士和報稅代理人網絡推動「碳健檢與財會 AI」，對象是沒有專職財會的企業；企業可向帳務委託的財會事務所洽詢 — [工商時報 2026-02-13](https://www.ctee.com.tw/news/20260213700065-430104)、搜尋摘要（[工商時報 2026-02-12](https://www.ctee.com.tw/news/20260212701563-430104)）
- 中企署曾與 Meta 合辦 AI 行銷論壇，邀 6 家業者展示 AI 解決方案（活動展示，非供應商登錄制度）— 搜尋摘要（[Taiwan News](https://www.taiwannews.com.tw/zh/news/6352654)）
- 中企署與 13 家技術法人在 2026 年開設 AI 實作專班，涵蓋 16 個產業領域（紡織、水五金、扣件、手工具、機械、食品、印刷等）— 搜尋摘要（[工商時報 2026-04-14](https://www.ctee.com.tw/news/20260414700101-430104)）
- 可預期的反對意見（依調查障礙排序）：不知道要用在哪裡、不理解 AI、成本高、沒有人才、成效難評估 — [旺得富 2025-12-26](https://wantrich.chinatimes.com/news/20251226900494-420501)
- 國際：Goldman Sachs 引用的調查顯示 76% 美國小企業使用 AI，但只有 14% 完全整合進核心營運，可見有一段「導入落差」需要外部協助 — [Goldman Sachs 10KSB](https://www.goldmansachs.com/community-impact/10000-small-businesses-voices/insights/ai-presents-a-major-opportunity-for-small-businesses)

### Inferences
- 對應反對意見的話術：
  - 「不知道用在哪」：用付費診斷的流程地圖回應。
  - 「成本高」：用固定價格、30 天交付、工具費由客戶直接付給原廠（透明）、算給老闆看每月省幾小時人工。
  - 「沒人才」：月維護費代替聘一個工程師。
  - 「成效難評估」：衝刺前後量測處理時間和錯誤率。
  - 「政府有免費輔導」：法人輔導團聚焦製造業、名額有限、要排隊；一人顧問的賣點是速度和客製。
- 記帳士和會計事務所具雙重身分：本身就是目標客戶（大量重複的憑證、對帳、催件工作），也是通路（每家服務數十到數百家微型企業）。拿下一家事務所當案例，可以延伸成轉介來源。
- 貿易商、工程行老闆多半不看 LinkedIn。商會、扶輪社、BNI 這類面對面通路，以及 LINE 群組和 FB 社團，可能比較有效，但本次沒有找到實證。

### Gaps
- 沒有找到台灣 BNI、商會、扶輪社用於 B2B 自動化服務的成效數據或案例。
- 沒有找到台灣或其他亞洲市場一人自動化顧問公開營收或客戶數的案例研究（Darrell TW 沒有公開營收）。
- 沒有找到台灣中小企業老闆對自動化顧問的具體反對意見訪談資料，上述反對意見從調查障礙推得。

## 7. 最快拿到第一個付費客戶的路徑與早期營收

### Takeaway
沒有找到台灣一人自動化顧問早期營收的公開數據。從現有資料推估，最快路徑是：用 1–2 個免費或低價的熟人案例累積可展示的成果，再以 NT$5,000 上下的付費診斷切入同類客戶，轉換成 NT$4–10 萬的固定範圍專案，最後接 NT$3,000–8,000/月的維護約。

### Cited Findings
- 競品錨點：專案 NT$5 萬起、常見 5–15 萬；免費診斷 — [Darrell TW](https://www.darrelltw.com/n8n-expert/)
- 小型企業（5–15 人）AI 自動化總預算錨點：10 萬以下；建議每月保留 NT$3,000–5,000 維護費 — [恆遠數位](https://foreverwebs.com/blog/ai-budget-breakdown-100k-500k-2m-taiwan-sme-2026)
- 小型案例一個工作流約 3 天建成；文章自估回本期 7–10 個月（未經獨立查證）— 同上
- PRO360 規模：每月媒合 10 萬+ 案件，平均時薪 NT$646 — [Yourator PRO360](https://www.yourator.co/companies/PRO360)

### Inferences
- 早期營收情境（推論）：
  - 第 1–2 個月：1–2 個案例客戶（折扣價 NT$1.5–3 萬）。
  - 第 3–4 個月：每月 2–4 個付費診斷（每個 NT$3,000–8,000）、轉換 1–2 個衝刺專案（每個 NT$4–10 萬）。
  - 第 6 個月左右：月營收約 NT$8–20 萬（專案）＋ NT$1.5–5 萬（5–8 家維護約 × NT$3,000–6,000）。
  - 這是推論，依競品價格和工時推估，沒有實證。
- 最快的單一產業切入點，推論可選小型電商或記帳事務所：兩者都已在用雲端工具（Shopee、Shopline、Google Sheets、記帳軟體），資料比較結構化，API 可用性較高，比工程行、傳統貿易商（ERP 封閉、紙本多）更適合 30 天內交付。
- 可複製的「套裝流程」能壓低交付時數，例如：Gmail 詢價 → AI 擷取 → Sheets 報價單 → LINE 通知；發票照片 → OCR → 記帳表；電商訂單 → 出貨通知 → 每日報表。

### Gaps
- 沒有找到台灣或亞洲一人自動化顧問的早期營收、成交週期、診斷轉專案轉換率等實證數據。
- 沒有找到台灣中小企業對「付費診斷」的接受度數據。

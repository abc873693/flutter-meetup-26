---
marp: true
title: Flutter 七月大小事
description: 2025/07 有趣新知
author: Rainer Fang
keywords: Flutter, Dart
theme: default
size: 16:9
paginate: true
---

# Flutter 小聚 #26

![bg](./image/base/cover.png)

---

# 小聚說明

- 主辦社群: **GDG Taipei**、**Flutter Taipei**
- 原則上一個月會舉辦一次，時間會在當月**最後一週的週二**
- 地點：**天攏書局 2F**
- 活動主要會分成
  - 當月 Flutter 大小事: 介紹當月 Flutter 相關的大小事
  - 開發者經驗分享: 分享與 Flutter 開發的相關內容，題目不限，可洽志工報名
  - Lightning Talk: 現場/活動事前表單報名，在場有任何想法，可洽志工報名
  - 活動任何問題都可以透過 **Slido** 發問
- 小聚任何行為都參照 GDG 台灣 行為準則 https://gdg.tw/code_of_conduct/
- 下次小聚時間：**2025/08/27**

---

![bg width:75%](./image/base/gdg-taipei.jpeg)

![bg width:80%](./image/base/gdg-taipei-qr.png)

---

![bg width:90%](./image/base/flutter-taipei.avif)

![bg width:80%](./image/base/flutter-taipei-qr.png)

---

# GDG TW @ COSCUP 2025

![width:80%](./image/coscup-2025.png)

---

# Flutter Taipei 每月月報

![width:80%](./image/base/medium-post.jpeg)

---

# 上台分享可獲得一個 Pin 針 及 帽子

![bg width:75% right ](./image/base/sharing-swag.jpeg)

---

# [Slido](https://app.sli.do/event/foSqFPgdLXht2jtwsS2RQz)

![bg width:75% right](./image/slido.png)

---

# Flutter 七月大小事

## Rainer Fang 

---

# Rainer Fang 

- GDG Taipei Organizer
- Flutter Taipei Organizer
- 專注於 Flutter 的行動應用開發者

![bg height:60% right](./image/base/rainer.jpg)

---

# Unleash new AI capabilities for Flutter in Firebase Studio


--- 

## 簡介

> Flutter 開發在 Firebase Studio 中變得更加智慧！在 I/O Connect India 大會上，我們發布了由 AI 驅動的新功能，旨在提供更自動化和高效的工作流程。

- 本文將深入探討 Firebase Studio 中針對 Flutter 的 AI 增強功能。
- 展示如何使用這些功能建構強大的應用程式，就像我們在舞台上展示的範例一樣。

---

## 升級後的 AI 優化 Flutter 範本

> Firebase Studio 中的 Flutter 範本進行了重大升級，具備新的 AI 功能，可將您的工作區優化為 AI 優先體驗。

- 範本預設為自主代理模式 (Agent mode)，允許 Gemini 直接進行更改，無需等待批准。
- 我們還將 Gemini 規則納入自動生成的 `airules.md` 檔案中，進一步完善 Gemini 生成的程式碼。
- 這使您能夠以更流暢的流程添加功能或生成整個 Flutter 應用程式。

![AI-optimized Flutter template](https://cdn-images-1.medium.com/max/1024/1*lPy6kRkj2N5ybEhHIKjbVw.gif)

--- 

## 自主進行更改

> 以前，在 Firebase Studio 中處理 Flutter 專案時，您需要手動批准代理模式下的每個程式碼更改。

- 現在，透過新的代理 (自動運行) 模式，Gemini 可以自主進行更改，生成整個應用程式，並以流暢的流程添加功能。
- 例如，在開發類似 I/O Connect India 演示的應用程式時，您可以使用代理 (自動運行) 模式在單次互動中無縫整合 Firebase 後端服務和實作複雜的導航模式。
- Firebase Studio 利用 Git，讓您可以快速將更改恢復到先前的提交版本。

![Agent (Auto-run) mode with a Flutter project in Firebase Studio](https://cdn-images-1.medium.com/max/1024/1*i5KGoCCzGQXV5SuTYhbpbw.gif)

--- 

## AI 規則 (AI rules)

> 升級後的 Flutter 範本中，我們將 AI 指令納入新檔案：`airules.md`。

- 此檔案包含 Gemini 在生成程式碼時要遵循的明確規則，提高輸出的品質和相關性。
- 您可以使用預設的 AI 規則，或根據專案的特定需求進行自訂。

### 規則範例:

- 作為 Flutter 共同開發人員
- 編寫單元測試
- 主動尋找並修正錯誤
- 選擇要使用的主題、工具、擴充功能和啟動命令
- 添加和移除 Flutter 套件
- 遵守 Flutter 和 Dart 程式碼品質的最佳實踐
- 設定複雜導航

![Overview of the default Flutter AI rules (airules.md) in Firebase Studio](https://cdn-images-1.medium.com/max/1024/1*FPNH3GWzShcGYInVxc30qA.gif)

--- 

## 與 Dart MCP Server 相容

> Firebase Studio 現在包含對模型上下文協定 (Model Context Protocol, MCP) 的基礎支援，並與我們的 Dart MCP Server 協同工作。

- 與 Firebase Studio 整合後，Dart MCP Server 讓 Firebase Studio 中的 Gemini 能夠分析並自動修正專案程式碼中 Dart 和 Flutter 特定的錯誤。
- 您還可以高效地搜尋 pub.dev 以找到最佳套件、管理 `pubspec.yaml` 中的依賴關係、執行測試等等。
- Dart MCP Server 目前處於 Beta 階段。

![Dart MCP Server configuration for a Flutter app in Firebase Studio](https://cdn-images-1.medium.com/max/1024/0*CHTpeFMydBD0KQY9)

--- 

## 與我們一同建構

> 我們對 Firebase Studio 與 Flutter 的持續整合有著宏偉的計畫，並期待您在使用 Flutter 探索這些新功能時提供回饋。

---

# Supercharge Your Dart & Flutter Development Experience with the Dart MCP Server

--- 

## 簡介

> AI 開發環境正在迅速發展，強大的代理 (agents) 能夠協助開發人員完成各種任務。為了真正釋放其潛力，這些代理需要存取超出其固有能力的上下文和工具。

- 這就是模型上下文協定 (Model Context Protocol, MCP) 的作用，它作為一個標準化的外掛程式系統，將 AI 模型連接到外部系統和資料來源。
- Dart MCP Server 是我們針對 Dart 和 Flutter 生態系統實作的此標準。

---

## 介紹 Dart MCP Server

> Dart MCP Server (需要 Dart SDK 3.9/Flutter 3.35 Beta 或更高版本) 是一個強大的工具，彌合了 AI 編碼助手與 Dart/Flutter 開發生態系統之間的差距。

- 它允許 AI 模型與您的開發環境和正在運行的 Dart 或 Flutter 應用程式互動。
- 提供智慧洞察，並使用通常只能從 IDE 或 Dart & Flutter DevTools 存取的工具。

--- 

## Dart MCP Server 能為您做什麼？

> Dart MCP Server 提供不斷增長的工具列表，讓 AI 助手深入了解您的專案。

它可以：

- 分析並修復專案程式碼中的錯誤。
- 內省並與您正在運行的應用程式互動 (例如觸發熱重載、獲取選定的 widget、獲取運行時錯誤)。
- 在 pub.dev 上搜尋最適合您用例的套件。
- 管理 `pubspec.yaml` 中的套件依賴關係。
- 運行測試並分析結果。
- ...以及更多！

> 請參閱官方文件以獲取最新工具列表。

---

## Dart MCP Server 實際應用

> Dart MCP Server 的真正力量在於它如何讓 AI 助手和代理不僅能夠推斷您專案的上下文，還能透過工具採取行動。

- 大型語言模型 (LLM) 決定何時使用哪些工具，因此您可以專注於用自然語言描述您的目標。
- 讓我們透過幾個使用 VS Code 中 GitHub Copilot 代理模式的範例來看看實際應用。

--- 

## 修正運行時佈局錯誤 (Fixing a runtime layout error)

> 我們都遇到過這種情況：您建構了一個漂亮的 UI，運行應用程式，卻看到臭名昭著的 RenderFlex overflow error 黃黑條紋。現在，您可以向 AI 助手尋求幫助，而不是手動調試 widget 樹。

- **提示:** 「檢查並修復靜態和運行時分析問題。檢查並修復任何佈局問題。」
- 在幕後，AI 代理使用 Dart MCP Server 的工具來：
  1. **查看錯誤:** 使用工具從正在運行的應用程式獲取當前的運行時錯誤。
  2. **檢查 UI:** 存取 Flutter widget 樹以了解導致溢出的佈局。
  3. **應用修正:** 有了這些上下文，它會應用修正並再次檢查是否有任何剩餘錯誤。
- 您可以選擇保留或撤銷程式碼更改。

![Fixing a runtime layout error](https://cdn-images-1.medium.com/max/1024/1*3K1rgoDtIBWbIFZPp1VCEQ.gif)

--- 

## 添加新功能與套件搜尋 (Adding new functionality with package search)

> 假設您需要向應用程式添加圖表。您應該使用哪個套件？如何添加並編寫樣板程式碼？Dart MCP Server 簡化了整個過程。

- **提示:** 「尋找一個合適的套件來添加一個線圖，該線圖能映射按鈕按下的次數隨時間的變化。」
- AI 代理現在充當真正的助手：
  1. **找到正確的工具:** 使用 `pub_dev_search` 工具查找流行且評價很高的圖表庫。
  2. **管理依賴關係:** 在您確認其選擇後 (例如 `syncfusion_flutter_charts`)，它使用工具將套件添加到您的 `pubspec.yaml` 並運行 `pub get`。
  3. **生成程式碼:** 生成新的 widget 程式碼，其中包含線圖的樣板程式碼並將其放置在 UI 中。它甚至會自我修正在此過程中引入的語法錯誤。您可以從那裡進一步自訂。

![Adding new functionality with package search](https://cdn-images-1.medium.com/max/1024/1*DGTEKfS3-ZANFr66VG8MRw.gif)

---

## 與流行的 AI 驅動開發環境和工具進行配置

> 由於模型上下文協定正在迅速成為整合工具鏈和 LLM 的標準，因此可以使用 MCP Server 的工具列表不斷增長。

- Dart MCP Server 可以與任何 MCP 用戶端整合。
- 首先，Dart MCP Server 需要 Dart SDK 3.9/Flutter 3.35 beta 或更高版本，因此切換到 beta 頻道並運行 `flutter upgrade` 以確保您擁有最新版本。

---

## Gemini CLI

> Gemini CLI 是一個開源 AI 代理，將 Gemini 的強大功能直接帶到您的終端機中，提供從提示到模型的直接路徑。

- 安裝 Gemini CLI 在您的機器上。
- 確保您的環境正在運行 Dart SDK 3.9/Flutter 3.35 beta 或更高版本。
- 配置 Gemini CLI 以使用 Dart MCP Server，編輯您本地專案中的 `.gemini/settings.json` 檔案。

```json
{
  "mcpServers": {
    "dart": {
      "command": "dart",
      "args": [
        "mcp-server",
        "--experimental-mcp-server"
      ]
    }
  }
}
```

- **Pro tips:**
  - 如果您使用 `/mcp` 提示 Gemini CLI，您將能夠看到可用的 MCP 工具集。
  - 如果您的專案有您希望 LLM 了解的特定準則或規則，您可以透過在專案根目錄中添加 `GEMINI.md` 檔案來記錄這些內容。

![Gemini CLI](https://cdn-images-1.medium.com/max/1024/0*gD-O6VeS0xT6EdDh)

--- 

## Gemini Code Assist

> Gemini CLI 的底層技術也已整合到 VS Code 中的 Gemini Code Assist 中，這是一個強大的 AI 助手，直接在您的 IDE 中提供聊天和代理功能。

- 在代理模式下，您可以在聊天窗口中編寫提示，並觀察 Gemini 執行您的請求。
- 確保您的環境正在運行 Dart SDK 3.9/Flutter 3.35 beta 或更高版本。
- 配置 Gemini Code Assist 以使用 Dart MCP Server：
  1. 先安裝並配置 Gemini CLI。
  2. 按照與上面相同的說明配置 Gemini CLI 以使用 Dart MCP Server，這也會為 Gemini Code Assist 啟用它。
- 您可以透過在代理模式下的聊天窗口中輸入 `/mcp` 來驗證 MCP 服務器是否已正確配置。

![Gemini Code Assist](https://cdn-images-1.medium.com/max/1024/1*eYea3SzwoGDCQeP5Tmq-Pg.png)

--- 

## Firebase Studio

> Firebase Studio 是一個基於雲端的代理開發環境，可幫助您構建和發布生產級別的全端 AI 應用程式，包括 API、後端、前端、移動等等。

- 在 Firebase Studio 中添加 MCP 服務器：
  1. 在您的專案中建立一個 `.idx/mcp.json` 檔案 (如果尚不存在) 並將相同的 Dart MCP Server 配置添加到檔案中，如上面的 Gemini CLI 說明所示。
  2. 確保您的環境正在運行 Dart SDK 3.9/Flutter 3.35 beta 或更高版本。
  3. 透過打開命令面板 (Shift+Ctrl+P) 並輸入 `Firebase Studio: Rebuild Environment` 來重建您的工作區以完成設定。

![Firebase Studio](https://cdn-images-1.medium.com/max/1024/0*Vjo7hhpe6uDe05yS)

--- 

## GitHub Copilot in VS Code

> GitHub Copilot 是一個整合到 VS Code 中的 AI 驅動編碼助手。Dart VS Code 擴展透過向 VS Code 註冊 Dart MCP Server 來為 Copilot 提供簡單的整合。

- Copilot 或任何其他支援 VS Code MCP API 的 AI 代理會自動為您配置 Dart MCP Server，這樣您就不必手動操作。
- 確保您的環境正在運行 Dart SDK 3.9/Flutter 3.35 beta 或更高版本。
- 配置 Dart MCP Server，將以下內容添加到您的 VS Code 用戶設定中：

```json
"dart.mcpServer": true
```

- 您還可以考慮將 `"chat.mcp.discovery.enabled": true` 添加到您的 VS Code 用戶設定中，以自動發現其他工具 (如 Claude Desktop 或 Cursor) 中配置的服務器。

--- 

## Cursor

> Cursor 是一個基於 VS Code 的流行 AI 驅動程式碼編輯器。Dart 和 Flutter VS Code 擴充功能可以安裝在 Cursor 中，以提供類似於您在 VS Code 中預期的開發體驗，並提供 Cursor 提供的額外 AI 驅動功能。

- 確保您的環境正在運行 Dart SDK 3.9/Flutter 3.35 beta 或更高版本。
- 配置 Cursor 以使用 Dart MCP Server：
  - 您可以單擊 Dart MCP Server README 檔案中的 **Add to Cursor** 按鈕 (最簡單的方法)。
  - 或者按照官方 Cursor 文件中的說明安裝 MCP Server。
- 配置 Dart MCP Server 後，您的 `.cursor/mcp.json` 檔案中應該會出現以下內容：

```json
{
  "mcpServers": {
    "dart": {
      "command": "dart",
      "args": [
        "mcp-server",
        "--experimental-mcp-server", // Can be removed for Dart 3.9.0 or later
        "--force-roots-fallback" // Workaround for a Cursor issue with Roots support
      ]
    }
  }
}
```

---

## 其他工具

> Dart MCP Server 可用於任何支援 MCP 的地方。請遵循您選擇的 MCP 用戶端提供的說明來配置 Dart MCP Server。

*並非所有工具都支援，因為某些工具需要存取特定的 IDE 服務。

--- 

## 接下來會發生什麼？

> 這個實驗性發布只是第一步。我們的願景是讓 Dart 和 Flutter 開發人員透過 AI 驅動的體驗達到最高生產力，滿足他們的工作需求。

- **更深入、無縫的 IDE 整合：** 我們正在與 Firebase Studio、Android Studio 中的 Gemini、Gemini Code Assist 等團隊密切合作，使 Dart MCP Server 的使用毫不費力。
- **AI 驅動的 DevTools 功能：** 我們計劃將 AI 輔助直接引入 **Dart 和 Flutter DevTools**。
- **不斷增長的工具箱：** 我們將繼續擴展 MCP Server 的功能，例如支援更複雜的重構。

> 雖然我們的路線圖以我們的願景為指導，但您的回饋對於幫助我們優先處理對您最重要的事項至關重要。

---

## 結論

> 透過為您的編碼助手提供專案上下文和官方工具鏈的存取權，您可以更快地移動、更有效地解決問題，並專注於最重要的事情：構建美觀、高品質的應用程式。

- Dart MCP Server 代表著 Dart 和 Flutter AI 驅動開發的重大飛躍，是我們團隊致力於提供高效開發人員體驗的延續。
- 這才剛剛開始。隨著模型上下文協定變得更加普及，以及 Dart MCP Server 獲得更多功能，您與 AI 驅動開發工具和代理之間的協作只會變得更智慧、更無縫。
- **此功能仍處於實驗階段，您的回饋非常寶貴。** 立即在您喜歡的編輯器中啟用它，並透過在我們的 GitHub 儲存庫中提交問題來告訴我們您的想法。擁抱 AI 輔助開發的未來，並在您的 Dart 和 Flutter 專案中解鎖新的生產力水平。我們迫不及待地想看到您創造出什麼！

---



# ReaxDB：高性能 Flutter NoSQL 資料庫

## 介紹 ReaxDB

- 一個全新的開源套件：`reaxdb_dart`
- **快速、反應式、離線優先的 NoSQL 資料庫**，專為大型資料集和高性能需求的行動應用程式設計。

---

## 為什麼要構建 ReaxDB？

- 曾為物流客戶管理數百萬條離線包裹記錄，需要即時更新。
- Hive 缺乏查詢功能，Isar 則過於複雜且有不必要的原生依賴。
- 因此，開始構建 ReaxDB，一個輕量級、純 Dart 的資料庫引擎。

---

## ReaxDB 的核心特性

- ⚡ **21,000+ 寫入/秒**
- 🧠 **混合儲存**：LSM 樹 + B+ 樹
- 🔄 **反應式串流**：支援模式化監聽
- 🔐 **AES 加密**：開箱即用
- 📦 **零原生依賴**：純 Dart 實現
- 🔎 **二級索引、範圍查詢和複雜篩選**
- ✅ **ACID 事務**

---

## 其他主要功能

- **極速性能**：333k+ 讀取/秒，21k+ 寫入/秒
- **查詢豐富**：`whereEquals`, `whereBetween`, `orderBy`, `limit` 等
- **批次操作**：`putBatch`, `getBatch` 支援大量資料處理
- **細緻快取**：多級快取 (L1, L2, L3) 附帶性能指標
- **專為行動裝置設計**：記憶體高效、高吞吐量、離線友善

----- 

## ReaxDB 與其他資料庫的比較

- **Hive** 適用於簡單用例。
- **Isar** 強大但依賴原生程式碼。
- **ReaxDB** 介於兩者之間：
  - ✅ 像 Hive 一樣簡單，
  - ✅ 像 Isar 一樣強大，
  - 但採用**混合引擎**（LSM + B+ 樹）且**無需原生設定**。

---

## 基準測試（在行動裝置上）

- 讀取：**333k 操作/秒**
- 寫入：**21k 操作/秒**
- 快取命中：**555k 操作/秒**
- 支援 10+ 並發操作

---

## 如何試用 ReaxDB

1. **添加依賴**：
   ```yaml
   dependencies:
     reaxdb_dart: ^1.1.0
   ```

2. **使用範例**：
   ```dart
   final db = await ReaxDB.open('my_database');
   await db.put('user:123', {'name': 'Alice', 'age': 30});
   final user = await db.get('user:123');
   print(user); // {name: Alice, age: 30}
   ```

---

# 自製 TLDraw 替代品：15 天 Flutter 開發筆記

## 動機：Eraser.io 的限制

- 幾週前，使用 Eraser.io 草擬產品和技術圖，但很快達到免費方案的三個檔案限制。
- 決定自行構建一個替代方案。

---

## 開發過程與功能

- 在 15 天內，使用 Flutter 構建了一個完整的繪圖應用程式。
- **靈感來源**：TLDraw 和 Excalidraw。
- **工具集**：移動、鉛筆、矩形、橢圓、箭頭、線條和文字。
- **互動功能**：
  - 多選和 Shift-click 支援。
  - Shift-拖曳創建完美方形或圓形。
  - 使用 Shift 時，箭頭鎖定在固定角度。
- **資料處理**：可將整個專案和所有物件序列化和反序列化為 JSON。
- **圖標庫**：內含超過 2500 個圖標（Postgres, Google, DB 圖標等），用於設計架構圖、流程圖等。

---

## 現況與心得

- 該專案將整合到我正在開發的更大 AI 內容工作區產品中，暫不開源。
- 這次開發再次提醒我為何熱愛開發——它賦予你創造所需事物的能力。

---

## 歡迎提問

- 如果有人好奇如何在 Flutter 中構建其架構或處理特定的 UI 互動，我很樂意回答。

![Flutter 構建的繪圖應用程式](https://i.ibb.co/JR8fjc6z/Build-using-Flutter.png)

---

# Relic：Dart 的高效能 Web 伺服器

## Relic 簡介

- 歷經 9 個月的開發，**Relic** 即將穩定發布。
- 一個低階 Web 伺服器，**受 `shelf` 啟發，但具有顯著的性能和架構改進。**
- 可視為 `shelf` 的現代、更高效且靈活的替代方案。

---

## 期待您的回饋

- 隨著 Relic 接近 1.0 版本，我們非常期待收到您的想法、回饋和建議。

- **試用 Relic**：[https://pub.dev/packages/relic](https://pub.dev/packages/relic)

---

# fldraw：Flutter 的開源 tldraw 替代方案

## 簡介 fldraw

- **Fldraw** 是一個高性能、開源的 Flutter 繪圖庫，旨在輕鬆將無限畫布和節點編輯器功能帶入您的應用程式。
- 開發重點：穩固基礎，並優先考慮性能和開發者體驗。

---

## 核心功能

- **無限畫布**：流暢、GPU 加速的畫布，具有響應式平移和縮放。
- **智能節點系統**：創建複雜、互動式節點，並用智能吸附到最近邊緣的箭頭連接它們。
- **文字轉圖表語言**：可透過定義的 DSL (Diagram Scripting Language) 描述整個圖表，fldraw 會自動解析、布局並渲染。非常適合版本控制和程式化生成。

---

## 其他功能與資源

- **強大控制器 API**：乾淨、高階的控制器，可程式化管理工具、添加物件、處理撤銷/重做，並監聽應用程式中的狀態變化。
- **即用型工具**：預建工具欄、強大的撤銷/重做歷史面板和鍵盤快捷鍵，提供出色的開箱即用體驗。
- 更多功能請參閱 GitHub 倉庫中的 `CHANGELOG.md`。

---

## 適用場景與呼籲

- 無論您是構建流程圖應用程式、協作白板，還是視覺編輯器，Fldraw 都能提供所需基礎。
- 歡迎任何回饋、功能請求或貢獻！

- **套件連結**：[https://pub.dev/packages/fldraw](https://pub.dev/packages/fldraw)
- **GitHub 倉庫**：[https://github.com/fldraw/fldraw](https://github.com/fldraw/fldraw)
- **線上演示**：[https://fldraw.vercel.app/](https://fldraw.vercel.app/)
  - **注意**：Flutter Web 首次載入可能需要約 30 秒，開發者正在尋求優化。

---

# Forui 0.13.0：模糊、流暢動畫及更多

## Forui 簡介

- Forui 是一個 Flutter UI 庫，提供了一組簡約的部件 (widgets)。
- 在 Forui 0.13.0 版本中，對整個庫的動畫進行了優化，使其感覺更流暢。

---

## 0.13.0 版本新功能

- 💨 **極致流暢的動畫**
- 🔎 **支援疊加層模糊效果**
- 🎨 **改進的樣式設計**

---

## 資源連結

- GitHub：[https://github.com/forus-labs/forui](https://github.com/forus-labs/forui)
- 路線圖：[https://github.com/orgs/forus-labs/projects/9](https://github.com/orgs/forus-labs/projects/9)
- 演示影片：[https://x.com/kawaijoe/status/1943275148465016838](https://x.com/kawaijoe/status/1943275148465016838)

---

# 兩年後重返 Flutter 開發：Riverpod + Freezed + Go_Router 仍是主流嗎？

## 背景

- 在中斷兩年後，準備重返 Flutter 開發。
- 離開前，業界趨勢是結合使用 **Riverpod** 和 **Freezed** 進行狀態和模型管理，而 **go_router** 是路由套件的領跑者。

---

## 核心問題

- 這種套件組合在現今是否仍然是業界領先（或接近領先）的堆疊？
- 目前有哪些新興或正在取代上述組合的流行套件？

---

# 我該放棄 Flutter 回歸原生 Android 嗎？

## Flutter 開發的困境

- 熱重載、組件結構和 Dart 的簡潔性令我喜愛，但開始遇到一些令人沮喪的限制：
  - 訪問原生功能時，平台通道 (Platform channels) 感覺笨拙。
  - 複雜的 UI/動畫有時與框架衝突。
  - 依賴性膨脹和破壞性更新（尤其是插件）。
  - 一些原生層的性能問題。
  - Material 3 在 Flutter 上仍然感覺不夠完善。

---

## 回歸原生 Android 的考量

- 我來自原生 Android (Kotlin) 背景，有時覺得回歸原生可以更快、更有掌控力。
- 但這樣會失去跨平台支援，而我的客戶喜歡這點。

## 尋求社群經驗

- 有沒有人也遇到過類似的兩難局面？

---

# 有人覺得 Provider 比 Riverpod 更好嗎？

## 背景

- 兩年來一直使用 Provider 進行開發，最近嘗試 Riverpod。

---

## 對 Riverpod 的質疑

- 雖然 Riverpod 使單一狀態（如整數、布林值等）更容易管理，但其他一切都感覺過度設計且不必要。
- **為什麼 Riverpod 有這麼多種 Provider 類型？**
- **為什麼會有非同步 (async) 的混亂？**
- 任何有 Flutter 經驗的人都很容易理解 Provider。
- `notifyListeners` 非常有用，在某些情況下，不依賴每次狀態變更都更新是有益的。
- 也不太關心不可變性 (immutability)。

---

## 核心疑問

- **能否清楚解釋 Riverpod 的核心優勢是什麼？**
- **為什麼這麼多人推崇它，而我看到的只是一個過度設計、不必要複雜的解決方案？**

---


# build_runner 2.6 版本

- 變更預設輸出格式為 **asset graph v3**
- 改進增量建置效率
- 更精確的無效快取辨識
- 改善 builder config 的錯誤訊息

---

# 對開發者的影響 🛠️

## ✅ 好處

- 更快的開發編譯速度
- 更少不必要的重新產生
- 更容易偵錯與排錯

## ⚠️ 注意事項

- 舊版 builder 可能不相容，需同步更新
- 自訂 builder 使用 `buildExtensions` API 的邏輯可能需調整
- 建議清除 `.dart_tool` 後重建以避免奇怪錯誤


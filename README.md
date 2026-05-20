# 1131437_TSVFile
# TSV 資料檔讀取程式 (TSV File Reader)

這是元智大學「視窗程式設計 (II)」課程的上課練習專案。本專案使用 C# Windows Forms 開發，主要功能為讀取以 Tab 分隔的 TSV 文字檔（例如英文單字卡），並透過自訂類別將資料解析後，結構化地顯示於 ListView 介面中。

## ✨ 功能特色 (Features)
* **檔案讀取**：支援透過 `OpenFileDialog` 選擇本機端的 TSV 或 TXT 檔案。
* **資料解析**：實作 `WordItem` 與 `WordCollection` 類別，將讀取的字串陣列切割並封裝為物件。
* **表格呈現**：使用 `ListView` (Details 模式) 動態顯示「單字、音標、音檔路徑、解釋」四個欄位。
* **防呆機制**：實作 `FormClosing` 事件，在使用者關閉視窗前跳出確認對話方塊。
* **關於視窗**：點擊選單的 About 可查看程式版本與開發者資訊。

## 🚀 執行說明 (How to Run)
1. 將專案複製到本機：
   ```bash
   git clone [https://github.com/fatdog180/TSVFile.git](https://github.com/fatdog180/TSVFile.git)
   ```
2. 使用 Visual Studio 開啟專案方案檔。

3. 點擊「啟動」或按下 F5 進行編譯與執行。

4. 程式啟動後，點選左上角選單 File -> Open。

5. 選擇隨附的 WordCards.txt 檔案即可成功載入並顯示單字列表。

## 📸 執行截圖 (Screenshot)
<img width="795" height="475" alt="TSVFile_example" src="https://github.com/user-attachments/assets/7c134600-14e3-43c5-8a4e-f89f807eeea9" />

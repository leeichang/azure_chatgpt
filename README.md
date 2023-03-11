[English Version](./README-en.md) ｜[中文版](./README.md)

# azure_chatgpt

我想用chatgpt來協助軟件開發！ 所以有這個項目的溝想！ 同時也使用如何將個人和公司信息導入chatgpt來訓練自己的聊天機器人來呈現這個過程！

所有的內容我都用英文問chatgpt！ 並回答！ 對話我是用chatgpt請他 『in Chinese』翻譯中文版！ 我寫的內容部分是用google translate翻譯的！

這個 Repositorie 的所有內容
Ｑ:代表我提出的問題
Ａ:代表chtpgt回复！

# 如何做！
## 詢問chatgpt
Q：如何使用azure OpenAi ChatGPT訓練自己或公司的數據，建立自己領域知識的聊天機器人
A:To use Azure OpenAI ChatGPT to train a chatbot with your own domain knowledge, follow these steps:

要使用 Azure OpenAI ChatGPT 訓練自己的數據集並創建具有自己領域知識的聊天機器人，請按照以下步驟操作：

1.如果您尚未擁有 Azure 帳戶，請註冊 Azure 帳戶。

2.創建 Azure OpenAI ChatGPT 服務的實例。

3.準備您的訓練數據。您的訓練數據應包括一系列問題和答案，您的聊天機器人將使用這些數據來生成響應。您可以從各種來源收集這些數據，例如您網站的常見問題解答、客戶支持電子郵件和聊天記錄。

4.格式化您的訓練數據。您的訓練數據應以 JSON 格式呈現，每個問題和答案對應一個對象。您可以使用 Microsoft Excel 或 Google Sheets 等工具來組織您的數據，並將其導出為 JSON 格式。

5.將您的訓練數據上傳到 Azure OpenAI ChatGPT 服務。您可以使用 Azure 門戶或 Azure CLI 進行上傳。

6.訓練您的聊天機器人。一旦您的訓練數據上傳完畢，您就可以使用 Azure OpenAI ChatGPT 服務開始訓練您的聊天機器人。此過程可能需要幾個小時，具體取決於您的訓練數據的大小和聊天機器人的複雜性。

7.測試您的聊天機器人。訓練完成後，您可以使用 Azure OpenAI ChatGPT 服務的測試工具來測試您的聊天機器人。確保您的聊天機器人能夠生成準確和有用的響應。

8.部署您的聊天機器人。一旦您滿意聊天機器人的性能，您可以使用 Azure OpenAI ChatGPT 服務的部署工具將其部署到您的網站或其他渠道。

9.監控和改進您的聊天機器人。隨著您的聊天機器人與客戶互動，您可能會收到反饋或發現改進的空間。不斷監控和改進您的聊天機器人，以確保為客戶提供最佳的體驗。

## Google
  ### found three youtube vedios
  Use 『Glarity-Summary for Google/YouTube (ChatGPT) 』to generate a summary before deciding whether to watch the video content carefully
  
  https://chrome.google.com/webstore/detail/glarity-summary-for-googl/cmnlolelipjlhfkhpohphpedmkfbobjc
  
  1. Azure Open AI in Bot Framework 
  
  https://www.youtube.com/watch?v=1MqpdFGUYxc
  
  本影片介紹了如何在 Azure 的 Bot composer 應用程式中整合 Azure Open AI。首先介紹了 Azure Open AI 的概述與其提供的三種模組，其中焦點放在目前非常知名的 GPT-3 模型上。但要使用此模型需先申請授權及付費，影片中也介紹了詳細的授權申請流程，及如何在 Azure Cognitive Service 建立該服務的資源。接著示範了如何使用 GPT-3 模型在 Bot 應用程式中提供自然語言處理相關的功能。
  
  
  2. ChatGPT & OpenAI powering your apps | OpenAI Studio in Microsoft Azure
  
  https://www.youtube.com/watch?v=3t3qZu1Dy1k
    
  Azure的OpenAI服務可以利用在Azure中基於自然語言和程式碼的深度理解，提供大規模生成式AI模型，以協助開發者建構新的應用程式。透過Azure OpenAI Studio進行實驗和測試模型，然後將其引入你的程式碼中，提供差異化的應用體驗，同時擁有Azure的企業級安全。模型具有為應用程式提供自然語言體驗的能力，如GPT-3和Codex。Azure OpenAI還具備支持負責任AI的工具，例如對內容進行篩選，以檢測和減輕有害用途。模型通常使用文字作為交互方式，建立好提示後可以直接在模型上進行零/幾次訓練即可。OpenAI可用於創建許多新體驗，例如將應用程式的整個界面轉換為自然語言交互，還可以在應用程式中使用自然語言命令，如操作Minecraft。  
    
    
  3. Exploring Chat GPT-3 via Microsoft Azure Open AI Studio
  
  https://www.youtube.com/watch?v=tu7qZ8W-HEQ

本影片介紹了如何在Microsoft Azure Open AI Studio中探索Chat GPT-3服務。Chat GPT-3是一款基於人工智慧的聊天機器人，可以根據輸入的文本生成類似人類的回答。Azure Open AI Studio提供了GPT3基於系列，Codex系列和嵌入系列三種模型，GPT3系列可以用於對話模型，生成模型，文本摘要和語言預測等。欲使用此服務需填寫申請表格，並等待Microsoft的電子郵件確認訪問權限。本篇主要介紹如何在Azure Open AI Studio中使用Chat GPT-3 Playground來嘗試和測試自己的應用。

### 文章(在搜尋的第一頁)
#### <p><a href="https://towardsdatascience.com/custom-informed-gpt-3-models-for-your-website-with-very-simple-code-47134b25620b" >Build custom-informed GPT-3-based chatbots for your website with very simple code</a></p>

- OpenAI 的 GPT-3 是一種專門用於語言處理的機器學習模型，可以使用簡單的 PHP 和 JavaScript 代碼將其整合到網頁中。
- GPT-3 是可定制的，可用於構建“了解”他們接受培訓的特定主題的聊天機器人。
- GPT-3 的臨時訓練可以使用“小樣本學習”方法完成，該方法涉及在提示中添加相關信息。
- 教授 GPT-3 事實數據可以使其響應更加準確。
- PHP 庫可用於連接到 OpenAI 的 GPT-3 API，PHP 文件可用於與 JavaScript 代碼交互以運行 GPT-3

#### <p><a href="https://pub.towardsai.net/build-chatgpt-like-chatbots-with-customized-knowledge-for-your-websites-using-simple-programming-f393206c6626" >Build ChatGPT-like Chatbots With Customized Knowledge for Your Websites, Using Simple Programming</a></p>

- GPT-3 是一種用於語言處理的機器學習模型，可以根據輸入輸出新文本。
- GPT-3 是可定制的，可用於各種應用。
- 可以使用 GPT-3 構建一個聊天機器人，該機器人經過特定主題的訓練，可以準確回答與該主題相關的問題。
- 可以使用 PHP 和 JavaScript 將 GPT-3 集成到網頁中。
- 需要一個允許 PHP 和 JavaScript 的服務器、一個來自 OpenAI 的 API 密鑰，以及一個連接到 GPT-3 的 PHP 庫，以便將 GPT-3 集成到網頁中。
- GPT-3 可以通過少樣本學習進行訓練，這涉及使用相關信息擴展輸入提示，以教授模型關於特定主題的知識。

#### <p><a href="https://openai.com/blog/customizing-gpt-3" >Customizing GPT-3 for your application</a></p>
- 開發人員現在可以根據自己的數據自定義 GPT-3，以創建適合其應用程序需求的版本。
- 微調 GPT-3 可提高其可靠性，減少錯誤和延遲，並使其更便宜、更快。
- 自定義 GPT-3 只需要幾個示例，並且可以產生比使用提示設計更好的結果。
- GPT-3 的定製版本提高了多家公司的業績，例如 Keeper Tax、Viable、Sana Labs 和 Elicit。
- API 客戶可以按照微調文檔立即定制 GPT-3。

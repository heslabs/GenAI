# OpenAI Whisper

線上免費用 OpenAI Whisper 幫影片上字幕 🚀 而且不限次數！
想用 AI 快速製作多部影片字幕，但經費有點拮据，電腦又跑不動大模型？今天要來介紹架設在 Hugging Face 上的 Whisper Web，能完全免費，且不限次數執行語音轉文字(Speech to Text, STT)，用的模型還是準確率超高的 OpenAI Whisper🔥

💫 Whisper Web
Hugging Face 連結🔗 
https://huggingface.co/spaces/Xenova/whisper-web  

提供多種 Whisper 模型，包含從 whisper-tiny.en 到 whisper-medium.en 系列模型，還有 distil-medium.en、distil-large-v2。

💡 打開網站直接用
1. 上傳影片音訊、貼上影片 YouTube 網址或直接錄音
2. 點擊齒輪圖示進入 Settings
3. 選取「Multilingual」，設定原始語言為 Chinese。如果需要英文字幕，可選擇翻譯任務
4. 勾選「Quantized」使用更多模型，但 distil 系列模型不支援多語言，中文最大模型為 whisper-medium.en。較大模型準確度較高，但需要更多處理時間
5. 點擊「Transcribe Audio」開始處理，喝杯咖啡等待
6. 可輸出 TXT 及有時間標記的 JSON 檔，如果需要 SRT 字幕檔，可上網搜尋 JSON 轉 SRT 工具。最後就能導入影片編輯軟體了🌟
7. 小編實測後，覺得準確率不錯，中文夾雜英文也能精確轉換！
🎯 因為是在 Hugging Face 上與別人共用運算資源，處理較長音檔時要稍微耐心等待。但想想這麼強大的功能完全免費，等等也值得
👋 分享給同樣為上字幕感到困擾的朋友吧

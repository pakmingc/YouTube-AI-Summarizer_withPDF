# YouTube-AI-Summarizer_withPDF
# YouTube Video Subtitle Summarization Tool

This repository contains a Python script for downloading YouTube video subtitles, generating summaries using OpenAI's GPT models, and optionally saving those summaries in text or PDF format. It's designed to work seamlessly with Google Colab and integrates with Google Drive for easy storage and access to files.

## Features

- **Download Subtitles:** Automatically fetches and downloads subtitles from a given YouTube video.
- **AI-Generated Summaries:** Utilizes OpenAI's GPT-3.5 Turbo or GPT-4 to create concise summaries of the downloaded subtitles.
- **Flexible Output Formats:** Allows users to save summaries as either plain text files or PDFs, directly to Google Drive.
- **Interactive Workflow:** Through user prompts, the script offers choices for model selection, summary language, and output format, tailoring the process to individual needs.
- **Multi-Language Support:** Capable of generating summaries in multiple languages, accommodating a broad user base.

## How to Use

1. **Setup Environment:** Run `!pip install youtube_transcript_api yt_dlp openai fpdf` in a Google Colab notebook to install necessary packages.
2. **Mount Google Drive:** This script uses Google Drive to save subtitles and summaries. Mount your Google Drive by following the prompted instructions.
3. **API Key Input:** You will be prompted to enter your OpenAI API key. Please ensure you have this key beforehand.
4. **YouTube Video Input:** Enter the URL or ID of the YouTube video you want to process.
5. **Summary Generation:** Decide whether you want to generate a summary. If yes, choose the summary's language and format (text or PDF).
6. **Save and Download:** The script saves subtitles and summaries directly to your Google Drive. If chosen, PDF summaries can be downloaded immediately after generation.

## 注意事項

- **環境設置:** 在 Google Colab 筆記本中運行 `!pip install youtube_transcript_api yt_dlp openai fpdf` 安裝所需的包。
- **掛載 Google 雲端硬盤:** 此腳本使用 Google Drive 來保存字幕和摘要。請按照提示的指示進行掛載。
- **API 密鑰輸入:** 您將被提示輸入您的 OpenAI API 密鑰。請確保事先擁有此密鑰。
- **YouTube 影片輸入:** 輸入您想要處理的 YouTube 影片的 URL 或 ID。
- **生成摘要:** 決定是否要生成摘要。如果是，請選擇摘要的語言和格式（文本或 PDF）。
- **保存和下載:** 腳本直接將字幕和摘要保存到您的 Google Drive 中。如果選擇了 PDF 摘要，生成後可以立即下載。

## Future Enhancements

- **Improved Language Support:** Expanding the list of languages for subtitle translation and summary generation.
- **User Interface:** Developing a web interface for easier interaction without the need for coding.
- **Automatic Video Download:** Adding functionality to download the video alongside its subtitles and summaries.

This tool is intended for educational and research purposes, helping users to quickly summarize video content for study or review. For any issues, suggestions, or contributions, please feel free to open an issue or a pull request.

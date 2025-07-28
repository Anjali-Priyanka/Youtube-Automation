# 📺 YouTube Automation with n8n

Automate your YouTube content workflow using **n8n**, the open-source workflow automation tool.

## 🚀 Features

* ✅ Auto-upload videos to YouTube
* ⏰ Schedule publishing
* 🧠 Generate titles/descriptions with AI (e.g., OpenAI)
* 📊 Store video analytics in Google Sheets
* 📢 Post updates to social media (Twitter, LinkedIn, etc.)

## 🛠️ Requirements

* n8n account/self-hosted instance
* Google Cloud project with YouTube Data API enabled
* OAuth2 credentials for YouTube
* Optional: OpenAI API key for content generation

## 🧩 Workflow Overview

1. **Trigger**: Manual/Scheduled
2. **Video Input**: Upload from cloud or local path
3. **Metadata Generation**: Use OpenAI for title/desc/tags
4. **YouTube Upload**: Via YouTube Data API
5. **Social Sharing**: Post to other platforms
6. **Analytics Logging**: Save views/likes/comments to Google Sheets

## 📦 Setup Instructions

1. Clone this repo
2. Import the `.json` workflow into n8n
3. Set up required credentials in n8n
4. Customize nodes as needed (paths, descriptions, hashtags, etc.)
5. Trigger and enjoy automated uploads!

## 📸 Screenshot

> *(Insert a screenshot of the workflow in n8n UI here)*
>
> ##

---



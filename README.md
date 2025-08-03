# Feedback-Analyzer
An automated n8n workflow that collects student feedback, stores it in Google Sheets, analyzes sentiment using OpenAI GPT, highlights suggestions, and sends personalized email responses to students—streamlining feedback handling for educational institutions.

**Feedback Analyzer** is an automated workflow built using [n8n](https://n8n.io/) that collects, stores, and analyzes student feedback with the help of **Google Sheets** and **OpenAI GPT**.

## 🚀 Features

- 📥 Collects feedback via a custom student form
- 🧾 Stores responses in Google Sheets
- 🤖 Performs sentiment analysis using GPT-4
- 💡 Highlights improvement suggestions
- 📧 Sends personalized thank-you emails to students
- 🔁 Automates the feedback loop for institutions

## 🧠 How It Works

1. **Form Submission**  
   Students fill out a feedback form with fields like name, email, phone, comments, and suggestions.

2. **Data Storage**  
   Responses are appended to a connected Google Sheet.

3. **AI Analysis**  
   OpenAI GPT-4 analyzes the feedback for sentiment and extracts key points.

4. **Response Generation**  
   A polite, personalized message is generated to acknowledge the feedback.

5. **Email Delivery**  
   The message is automatically emailed to the student using Gmail.

## 📂 Technologies Used

- [n8n](https://n8n.io/) – Workflow automation
- [Google Sheets](https://www.google.com/sheets/about/) – Data storage
- [OpenAI GPT-4](https://openai.com) – Natural language analysis
- [Gmail API](https://developers.google.com/gmail/api) – Email automation

## 🛠 Setup Instructions

> Note: Assumes you have n8n installed and running.

1. Clone this repository.
2. Open your n8n editor and import the `Feedback_Analyzer.json` workflow.
3. Set up the required credentials for:
   - Google Sheets
   - Gmail
   - OpenAI API
4. Deploy the form and connect it to your site or internal portal.
5. Test by submitting sample feedback.

## 📌 Use Case

Ideal for schools, colleges, training centers, or any institution seeking to automate and improve their feedback collection and response system.


---

> An automated n8n workflow that collects student feedback, stores it in Google Sheets, analyzes sentiment using OpenAI GPT, highlights suggestions, and sends personalized email responses.


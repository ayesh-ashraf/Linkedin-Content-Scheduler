# Linkedin-Content-Scheduler
An n8n workflow that automatically schedules and posts content to LinkedIn using Google Sheets.
## How It Works

1. **Trigger:** The workflow runs automatically on a schedule (daily, weekly, etc.).
2. **Read Sheet:** It reads post data (date, content, status) from Google Sheets.
3. **If Condition:** It checks if a post is due to be published.
4. **HTTP Request:** It sends the content to LinkedIn via API.
5. **Update Sheet:** It marks the post as “Published”.

## Files in This Repository

- `Linkedin_Content_Scheduler.json` — the exported n8n workflow.
- `README.md` — documentation of the project.

## Usage

1. Download the `.json` file.
2. Open n8n → click **Import** → upload the file.
3. Add your **LinkedIn API credentials** and **Google Sheets credentials**.
4. Activate the workflow and schedule it.

## 📸 Screenshot

<h2 align="center">📸 Workflow Screenshots</h2>

<p align="center">
  <b>1️⃣ Main Workflow</b><br>
  <img src="https://github.com/ayesh-ashraf/Linkedin-Content-Scheduler/blob/main/Linkedin%20content%20scheduler%20workflow.jpg?raw=true" width="600"><br><br>

  <b>2️⃣ LinkedIn Post Workflow</b><br>
  <img src="https://github.com/ayesh-ashraf/Linkedin-Content-Scheduler/blob/main/Linkedin%20workflow%20as%20Linkedin%20post.jpg?raw=true" width="600"><br><br>

  <b>3️⃣ Google Sheet Scheduler</b><br>
  <img src="https://github.com/ayesh-ashraf/Linkedin-Content-Scheduler/blob/main/Linkedin%20scheduler%20Google%20sheet.jpg?raw=true" width="600">
</p>

### **Demo Video**
[Watch the demo video here](https://youtu.be/bMi5evGlqmM)

### **Author""
Ayesha Ashraf



# 🔧 Lead Capture & Email Nurturing Automation

An automated lead management system built with **n8n** that captures form submissions, logs them to Google Sheets, and sends personalized emails — all without any manual work.

---

## 📌 What It Does

1. **Form Submission** — Prospect fills out a custom n8n form (name, product interest, intent)
2. **Google Sheets Logging** — Data is instantly appended to a Google Sheet as a lead record
3. **Conditional Logic** — IF node checks whether the lead expressed interest
4. **Automated Email** — If interested → personalized welcome email sent via Gmail automatically
5. **Passive Lead Capture** — If not interested → lead is still saved for future follow-up

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| n8n | Workflow automation engine |
| n8n Form Trigger | Lead capture form |
| Google Sheets | Lead database |
| Gmail | Automated email outreach |
| IF Node | Conditional logic |

---

## 🔁 Workflow Structure

```
On Form Submission
       ↓
Append Row in Google Sheet
       ↓
IF (interested = "yes")
       ↓              ↓
  Send Gmail      (captured, no email)
```

---

## 📈 Business Impact

- ⚡ Response time reduced from hours → seconds
- 📋 Zero leads lost — every submission is logged
- 🤖 Runs 24/7 with zero human involvement
- 💸 Replaces the need for expensive CRM tools

---

## 🚀 How to Use

1. Import `workflow.json` into your n8n instance
2. Connect your Google Sheets and Gmail credentials
3. Update the Sheet name and email template
4. Activate the workflow
5. Share the form URL with your audience

---

## 📂 Files

- `workflow.json` — n8n workflow export (import directly into n8n)
- `screenshot.png` — Workflow canvas preview

---

## 👤 Author

**Ankush** — Automation Developer  
🔗 [Fiverr](https://www.fiverr.com/ankush_automate) • [Upwork](https://www.upwork.com)

---

*Built as part of my automation portfolio. Open to freelance projects.*

# 📧 Phishing Email Analysis Task

## 🎯 Objective

The goal of this task is to **analyze a sample phishing email** and identify common phishing indicators. This exercise helps build awareness of **email-based threats** and strengthens basic cybersecurity analysis skills.

---

## 🧪 Task Overview

### Task Name: **Analyze a Phishing Email Sample**

In this task, you will:
- Examine a suspicious email.
- Identify signs of phishing.
- Use online tools to analyze headers.
- Document findings in a report.

---

## 🛠️ Tools Required

- A sample phishing email (text format).
- An email header analyzer:
  - 🔗 [MXToolbox Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
  - 🔗 [Google Message Header Analyzer](https://toolbox.googleapps.com/apps/messageheader/)

---

## 📝 Instructions (Step-by-Step)

### 🔹 Step 1: Obtain a Phishing Email Sample

You can use real examples from trusted educational sources:
- https://www.phishing.org/phishing-examples
- https://www.malware-traffic-analysis.net/

Or use this sample email below:

From: Amazon Security account-verification@amaz0n-security.com
Subject: Your Account Has Been Suspended

Dear Customer,

We have detected suspicious activity on your Amazon account.
To avoid suspension, please verify your information now.
Failure to do so will result in permanent closure of your account.

Click here to verify: http://amaz0n-security.com/verify

Thank you,
Amazon Security Team


---

### 🔹 Step 2: Analyze the Email for Phishing Indicators

Use the checklist below to analyze the content:

| Indicator | Description |
|----------|-------------|
| 📛 **Spoofed Sender Address** | Email is from `@amaz0n-security.com`, not `@amazon.com` |
| 🔗 **Suspicious or Mismatched Links** | Hovering reveals a fake domain |
| 🧨 **Urgent or Threatening Language** | "Your account will be suspended in 24 hours" |
| 🧾 **Unusual Request** | Asking to click a link and submit credentials |
| 🧹 **Spelling and Grammar Errors** | "Failure to do so" sounds awkward |
| 🕵️ **No Personalization** | Uses "Dear Customer" instead of your name |
| 📦 **Unexpected Attachment or Link** | Contains a clickable link to unknown site |

---

### 🔹 Step 3: Check Email Header (Optional but Recommended)

Use an online tool to analyze email headers:
1. Get the full headers from your email client.
2. Paste them into:
   - [MXToolbox](https://mxtoolbox.com/EmailHeaders.aspx)
   - [Google Header Analyzer](https://toolbox.googleapps.com/apps/messageheader/)
3. Look for:
   - IP address of the sender
   - SPF, DKIM, and DMARC authentication results
   - Domain mismatches

---

## 📄 Sample Report Format (for `report.txt`)

Sample Subject: Your Account Has Been Suspended
Sender: account-verification@amaz0n-security.com
Link Target: http://amaz0n-security.com/verify
Header Analysis:

Sender IP: 192.0.2.5 (not Amazon)

SPF: Fail

DKIM: Missing

DMARC: Fail

Phishing Indicators Found:

Spoofed sender domain

Suspicious URL

Urgency in language

No personalization

Poor grammar

Failed authentication in email header

---

## 📚 Interview Q&A Highlights

See `interview_questions.md` for full answers.

| Question | Summary Answer |
|---------|----------------|
| What is phishing? | A scam email designed to steal data |
| How to identify one? | Fake address, urgency, grammar issues |
| What is spoofing? | Forging a sender address |
| What tools help? | Header analyzers like MXToolbox |
| What to do? | Don’t click, report it, delete it |
| Why is it dangerous? | Can steal info, install malware |
| Role of social engineering? | Tricks people using emotion or authority |

---

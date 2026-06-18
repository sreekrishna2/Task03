# 🔐 Phishing Detection System

## 📌 Overview

This project is a rule-based phishing detection system that analyzes messages to identify potential phishing attacks.

## 🎯 Objective

To detect suspicious messages based on common phishing patterns and protect users from scams.

## ⚙️ Working

The system checks for:

* Urgency words (e.g., "urgent", "act now")
* Account-related threats (e.g., "account suspended")
* Financial bait (e.g., "claim prize")
* Suspicious links (http/https)
* Email/domain patterns
* Social engineering phrases (e.g., "send me OTP")

It also intelligently differentiates between:

* Legitimate OTP messages ✅
* Suspicious OTP requests ❌

## 💡 Example

Input:

```
Send me the OTP now
```

Output:

```
Suspicious Message ❌
```

## ▶️ How to Run

```bash
python phishing_mails_detector_p3.py
```

## 🛠 Technology Used

* Python

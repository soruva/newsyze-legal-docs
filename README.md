# 🧾 Newsyze Legal Documents

Official legal documentation for **Newsyze – AI News, Learning & Multilingual Summary App**.

This repository hosts all public-facing legal pages used in the **Newsyze** app and on Google Play.  
Each document is published via **GitHub Pages** and linked directly from the in-app Legal Center.

---

## 📂 Structure

| File | Purpose | Published URL |
|------|----------|----------------|
| `privacy-policy.html` | User data, AI usage, and privacy compliance | https://soruva.github.io/newsyze-legal-docs/privacy-policy.html |
| `terms.html` | Terms of use and user responsibilities | https://soruva.github.io/newsyze-legal-docs/terms.html |
| `faq.html` | Common questions and clarifications | https://soruva.github.io/newsyze-legal-docs/faq.html |
| `index.html` | Legal Center – links to all the above pages | https://soruva.github.io/newsyze-legal-docs/ |

---

## 🧠 App Overview

**Newsyze** is an AI-powered, multilingual news and learning app that combines:
- 🧠 **AI Summaries:** concise key points for every article  
- 🌍 **Translations:** English, Spanish, German, French, Portuguese  
- 📚 **Vocabulary & Flashcards:** learn directly from what you read  
- 🎯 **Gamified Streaks & Badges:** turn news reading into a habit  
- 🔈 **Text-to-Speech:** pronunciation and listening practice  
- 🔒 **Privacy-by-Design:** no login, no tracking, GDPR/CCPA compliant  

All AI features are designed for educational purposes only.

---

## ⚖️ Compliance Notes

- **Last updated:** Oct 13, 2025  
- Fully aligned with Google Play’s *Privacy Policy* and *Data Safety* requirements.  
- No personal or financial data is collected, shared, or transmitted to external servers.  
- All processing (AI summaries, translations) occurs via trusted APIs under strict usage limits.  
- Data is stored locally on the user’s device unless explicitly saved by the user.  

---

## 🛠️ Maintenance

To update document timestamps or minor text edits:

```bash
# Update "Last updated" date in both key documents
sed -i 's/Sep 24, 2025/Oct 13, 2025/g' /workspaces/newsyze-legal-docs/{terms.html,privacy-policy.html}

# Preview the affected lines
grep "Last updated" /workspaces/newsyze-legal-docs/*.html
````

Always commit and push after updates:

```bash
git add .
git commit -m "Update Last updated date to Oct 13, 2025"
git push origin main
```

---

## 🪪 License & Attribution

© 2025 **SoruvaLab**.
All documents in this repository are intended for public compliance use within the **Newsyze** application.
Unauthorized redistribution or misrepresentation of these materials is prohibited.

**Maintained by:**
📧 **[support@soruvalab.com](mailto:support@soruvalab.com)**
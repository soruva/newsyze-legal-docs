# 🌐 Newsyze – Multilingual AI News & Learning App  
### Learn Languages Through Real-World News. Fast. Smart. Beautiful.

Newsyze is an AI-powered multilingual news reader designed for **language learners, global professionals, and curious readers**.  
Read worldwide news, get instant AI summaries, translate into 5 languages, save vocabulary, track streaks, earn badges — all inside one minimal app.

No login. No tracking. No ads.  
Just smart learning.

---

## 🚀 Features

### 🧠 **AI Summary (OpenAI/Gemini)**
Every article comes with a clean, concise AI-generated summary.

### 🌍 **5 Languages Supported**
- English (UI + content)
- Spanish
- French
- German
- Portuguese 

UI switches instantly.  
Translation engine supports full-article multilingual translation.

### 📚 **Word Bank + Smart Vocabulary**
Long-press any word → AI translation → saved to Word Bank.

Includes:
- Part of speech (auto-detected)
- Source article tracking
- “Mastered” toggles
- Word review screen

### 🔊 **Advanced TTS (Text-to-Speech)**
- Speed slider  
- Pitch slider  
- High-quality voice toggle  
- Auto-selects accurate voice per language  

Perfect for pronunciation & listening practice.

### 🎮 **Gamification: Streaks & Badges**
Turn news reading into a daily habit.

You earn badges for:
- Article count (1, 10, 50, 100…)
- Reading streaks (3, 7, 30, 100 days)
- Premium unlock
- Language milestones

### 🎨 **Themes (Light / Dark / AMOLED / System)**
Modern UI with:
- Navy brand theme  
- AMOLED pure-black  
- Dynamic theme switching  

### 🖼️ **Safe Pexels AI Image Filtering**
Articles use safe, high-resolution images from Pexels.

No unsafe content.  
No unpredictable AI image calls.

### ⚡ **Fast Caching & Offline Tolerance**
- Hive-based smart caching  
- 24-hour freshness windows  
- Minimal API calls to stay fast & reduce load  

### 🔒 **Privacy-First**
- No login  
- No analytics SDK  
- No ads  
- No external tracking  
- All saved data stays local (Hive + SharedPreferences)

---

## 📥 Install Newsyze

Google Play Store:  
https://play.google.com/store/apps/details?id=com.soruvalab.newsyze

iOS version coming soon.

---

## 📂 Repository Structure

```

/assets/i18n/          → 5-language translations
/lib/models/           → Hive models (NewsArticle, WordModel)
/lib/screens/          → UI screens
/lib/services/         → AI, translation, caching, TTS, WordBank
/lib/widgets/          → Shared UI components
/theme.dart            → Brand theme + AMOLED theme
/main.dart             → App root

````

---

## ⚖️ Legal & Compliance

All legal documents are hosted at:

https://soruva.github.io/newsyze-legal-docs/

| Document | URL |
|---------|------|
| **Privacy Policy** | https://soruva.github.io/newsyze-legal-docs/privacy-policy.html |
| **Terms of Service** | https://soruva.github.io/newsyze-legal-docs/terms.html |
| **FAQ** | https://soruva.github.io/newsyze-legal-docs/faq.html |
| **Legal Center** | https://soruva.github.io/newsyze-legal-docs/ |

### 🔐 Google Play Data Safety (Compliant)

- **Collected:** None  
- **Shared:** None  
- **Stored locally:**  
  - Word Bank vocabulary  
  - Theme preferences  
  - App language  
  - Translation language  
  - Streak & badge progress  
- **Transmitted only on request:**  
  - Article text → AI API (summary/translation)  
- **No persistent user identifiers**  
- **No analytics / tracking**  
- **GDPR & CCPA aligned**

---

## 🛠️ Development

### Install dependencies

```bash
flutter pub get
````

### Generate splash/icons

```bash
flutter pub run flutter_native_splash:create
flutter pub run flutter_launcher_icons:main
```

### Run the app

```bash
flutter run
```

### Release build for Android

```bash
flutter build appbundle --release
```

---

## 📝 Updating Legal Docs

Documents live in a separate repo:

```
newsyze-legal-docs/
```

To update timestamps:

```bash
sed -i 's/Last updated:.*/Last updated: November 2025/g' ./*.html
```

Push to publish:

```bash
git add .
git commit -m "Update legal docs"
git push origin main
```

GitHub Pages updates instantly.

---

## 📧 Contact

Maintained by **SoruvaLab**
📩 [soruvalab@gmail.com](mailto:soruvalab@gmail.com)
© 2025 SoruvaLab. All rights reserved.

```

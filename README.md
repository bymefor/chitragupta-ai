# 👑 Chitragupta — All-in-One Student Power Portal

India's smartest student portal — AI homework help, calculators, quizzes, notes & career guidance.
**100% Free. No credit card. No backend. Just GitHub Pages + Google Gemini.**

---

## 🚀 Deploy in 5 Minutes — Completely Free

You only need:
- A free [GitHub](https://github.com) account
- A free [Google account](https://google.com) (for the Gemini API key)

---

### Step 1 — Get Your Free Gemini API Key (2 minutes)

1. Go to **[aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)**
2. Sign in with any Google account
3. Click **"Create API Key"**
4. Copy the key — it looks like `AIzaSy...`

> ✅ **Completely free** — Google gives you a generous free tier  
> ✅ **No credit card** required  
> ✅ **No billing setup** needed

---

### Step 2 — Add Your Key to the HTML File

1. Open `index.html` in any text editor (Notepad, VS Code, etc.)
2. Find this line near the top of the `<script>` section:
   ```js
   const GEMINI_API_KEY = 'YOUR_GEMINI_API_KEY_HERE';
   ```
3. Replace `YOUR_GEMINI_API_KEY_HERE` with your key:
   ```js
   const GEMINI_API_KEY = 'AIzaSyXXXXXXXXXXXXXXXXXXX';
   ```
4. Save the file

---

### Step 3 — Push to GitHub Pages (3 minutes)

1. Go to [github.com](https://github.com) → **New repository**
2. Name it `chitragupta` (or anything you like)
3. Make it **Public**
4. Upload `index.html` and `README.md` to the repo
5. Go to **Settings → Pages**
6. Under **Source** → select **Deploy from a branch**
7. Branch: `main`, Folder: `/ (root)` → **Save**
8. Wait ~1 minute → your site is live at:
   ```
   https://YOUR-USERNAME.github.io/chitragupta/
   ```

That's it! 🎉

---

## ✅ How It Works

```
Student's Browser  ──────────────────────────────►  Google Gemini AI
  (GitHub Pages)        Direct API call (free)        (Free tier)
                    ◄──────────────────────────────
                              AI Answer
```

Unlike other setups, **no proxy server is needed** — Google's Gemini API allows direct browser requests (CORS is open). Your API key is in the HTML file.

---

## 🔒 Is It Safe to Put the API Key in the HTML?

**Partially safe** — here's the honest answer:

| Risk | Level | Explanation |
|---|---|---|
| Someone stealing your key | Low-Medium | Anyone who views your source code can see it |
| Unexpected charges | Very Low | Gemini free tier has rate limits that prevent abuse |
| Data privacy | Low | Requests go directly from user → Google |

**For a student project on GitHub Pages, this is absolutely fine.** The free tier limits protect you from unexpected costs. If you ever want more security, you can add a Cloudflare Worker proxy later.

---

## 💰 Cost Breakdown

| What | Cost |
|---|---|
| GitHub Pages hosting | **Free** |
| Google Gemini API | **Free** (generous daily limits) |
| Domain name | **Free** (github.io subdomain) |
| **Total** | **₹0 / month** |

---

## ✨ Features

| Feature | Description |
|---|---|
| 🧠 AI Homework Solver | Step-by-step solutions for any subject |
| 📸 Photo Solver | Upload a photo of your question |
| 📖 Explain | Topics explained in Hindi/English/Hinglish |
| 📋 Summarizer | Turn long chapters into smart revision notes |
| ✍️ Answer Writer | Board exam format (CBSE/ICSE) model answers |
| ✏️ Essay AI | Essays, letters, speeches, stories |
| 📅 Study Planner | Personalised weekly study plans |
| 🔮 Exam Predictor | Likely exam questions based on syllabus |
| 💬 Doubt Chat | Multi-turn AI conversation |
| 📝 Quiz & Tests | AI-generated MCQs on any topic |
| 🧮 Calculators | Scientific, CGPA, Age, Physics, Chemistry |
| ⏱️ Pomodoro Timer | Focus sessions + exam countdown |
| 📖 Smart Notes | Save, organise, AI-improve your notes |
| 🎯 Career Guide | Stream advice & entrance exam info |
| 📊 Dashboard | XP, badges, streaks, progress tracking |
| 📜 Activity History | Searchable log of everything you've done |
| 👤 Username System | Personalised, remembered for 10 days |

---

## 🛠 Troubleshooting

**Yellow banner shows "API Key Required"**
→ You haven't set `GEMINI_API_KEY` yet. Follow Step 2 above.

**AI gives "403 Forbidden" or "API key not valid"**
→ Your API key is wrong. Go back to [aistudio.google.com](https://aistudio.google.com/app/apikey) and create a fresh one.

**AI gives "429 Too Many Requests"**
→ You've hit the free tier limit for today. Wait a few hours — it resets daily.

**GitHub Pages shows blank page**
→ Make sure the file is named exactly `index.html` (not `chitragupta.html`)

**Changes not showing after push**
→ Wait 1–2 minutes, then hard-refresh (Ctrl+Shift+R or Cmd+Shift+R)

---

Made with ❤️ by **Munish Mishra**  
Powered by **Google Gemini AI** — Free forever 🚀

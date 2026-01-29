# 🖱️ Right Click AI

A lightweight browser extension that adds a **powerful AI menu to your right‑click**. Instantly summarize, rewrite, explain, or ask questions about **selected text or entire web pages** using **Google’s Gemini AI**.

---

## ✨ What You Get

* ⚡ **Instant AI actions** via right‑click
* 📝 Writing tools: Fix Grammar, Rewrite, Change Tone
* 🧠 Understanding tools: Explain, Simplify, Summarize
* 📚 Study tools: Notes, Flashcards, Quiz generation
* 🌐 Page‑level Q&A: *Ask about this page*

---

## 🔑 Step 1: Add Your Gemini API Key (Required)

> If you see the error **“API key not valid. Please pass a valid API key.”**, this step is missing or incorrect.

### How to add the key

1. Open **`content.js`** in a text editor.
2. Locate the line (around line ~1016):

   ```js
   const GEMINI_API_KEY = 'YOUR_GOOGLE_API_KEY_HERE';
   ```
3. Replace it with your real key:

   ```js
   const GEMINI_API_KEY = 'AIzaSy...your...actual...key';
   ```
4. **Save** the file.

🔗 Get a free API key from **Google AI Studio**:
[https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
<img width="1866" height="585" alt="{218D4847-3710-4F84-8630-8B0D16EC8DAE}" src="https://github.com/user-attachments/assets/7db0462e-9027-4956-80ef-df128f5fb071" />

⚠️ **Important**

* Do **not** share your API key publicly.
* Reload the extension after changing the key.

---

## 🧩 Step 2: Install the Extension (Developer Mode)

This extension is loaded manually in Chromium‑based browsers.

### Supported browsers

* ✅ Chrome
* ✅ Edge
* ✅ Brave
* ✅ Opera

### Installation steps

1. Open the Extensions page:

   * Paste `chrome://extensions` into the address bar.
2. Enable **Developer mode** (top‑right toggle).
3. Click **Load unpacked**.
4. Select the project folder (e.g. `Right-Click-AI/`).
5. The extension will appear as **Right Click AI**.
<img width="822" height="420" alt="{B267DBCB-D7EC-4A03-9D16-296BC2AF1455}" src="https://github.com/user-attachments/assets/f1059546-2521-49fb-8057-f21c2918260d" />

---

## 🚀 Step 3: How to Use Right Click AI

### Basic usage

1. Open **any webpage**.
2. **Double right‑click** anywhere on the page.
3. The **AI menu** appears.

### If text is selected ✍️

You’ll see options like:

* Fix Grammar
* Rewrite
* Change Tone
* Simplify
* Explain
* Summarize
* Generate Notes
* Create Flashcards
* Generate Quiz
<img width="215" height="494" alt="{1A1D57AD-1CAE-4B0B-99C5-472AEFDD74A7}" src="https://github.com/user-attachments/assets/f5372151-c6cc-43d1-a952-ec4bb599296e" />

### If no text is selected 🌐

You can:

* **Ask about this page** (page‑level understanding)
  
---

## 🧠 Example Use Cases

* 📖 Studying articles or documentation
* ✍️ Improving writing quality instantly
* 🧩 Understanding complex technical pages
* 📝 Turning webpages into notes or flashcards
* 🧪 Quick self‑testing with quizzes

---

## 🛠️ Troubleshooting

### ❌ “API key not valid” error

✔ Confirm the API key is correctly pasted
✔ Ensure quotes are not removed
✔ Reload the extension from `chrome://extensions`
✔ Check that the key is enabled in Google AI Studio

### ❌ Menu not appearing

✔ Make sure you **double right‑click**
✔ Refresh the page
✔ Ensure the extension is enabled

---

## 📌 Notes

* This extension runs **locally in your browser**.
* Requests are sent directly to **Google Gemini APIs**.
* Performance depends on page size and API limits.

---

## 🧠 Summary

**Right Click AI** turns your browser into a contextual AI workspace.
Right‑click → choose action → get results.

Simple. Fast. Powerful.

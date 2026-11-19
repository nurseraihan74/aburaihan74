# Abu Raihan - Personal Portfolio Website

Portfolio website of **Abu Raihan**, Registered Nurse & Healthcare AI Specialist.

## 🚀 Quick Start

### Option 1: Open Directly in Browser
Double-click `index.html` to open it in any modern browser (Chrome, Edge, Firefox, Safari).

### Option 2: Run with Local Node.js Server
If you have Node.js installed:
```bash
node server.js
```
Then navigate to: **http://localhost:3000**

---

## 📁 Project Structure

- `index.html` - The complete single-page portfolio containing all HTML5 markup, Tailwind CSS via CDN, Google Fonts, Font Awesome icons, and Vanilla JavaScript interactions.
- `server.js` - Lightweight Node.js HTTP server for local development.

---

## ⚙️ Contact Form Configuration

To connect the contact form to your own Google Sheet and Telegram bot:
Open `index.html` and edit lines near the top of the `<script>` tag:

```javascript
const TELEGRAM_BOT_TOKEN = "YOUR_TELEGRAM_BOT_TOKEN";
const TELEGRAM_CHAT_ID = "YOUR_TELEGRAM_CHAT_ID";
const GOOGLE_SCRIPT_URL = "https://script.googleusercontent.com/macros/echo?user_content_key=AUkAhnQQMZebqfzuP8X2nUKYny1w6RitQ7Jb1mkwvWaY1FwkpVSsIy6m72tyr4GMuB5a16vuzq2cW-_fAD0eghGcAfySi25MtaUz8KJotFaiPHHr8_uITshyRmuzPu6LVipdjhxuYmaLoJF6tbDiVNcmzXX7_DlLKUptcvAQlqj-AFAw2SQmbzEWJfaQeeX62LqMM43fbQDBfyVE6NlQZ7sjWKdtSHSja37JDOuQKWQb-HasyPwpFwTeGIwCJtj2YAcFKSQKu8pGfKLU3vpAsl0YJXvPGlXRDw&lib=M0RcsODpC92MHOOHMwvYKvSJ51K4EHMtn";
```

---

## 🌐 Free 1-Click Deployment

- **GitHub Pages**: Upload `index.html` to a GitHub repository, go to **Settings > Pages**, and select the `main` branch.
- **Netlify / Vercel**: Drag and drop the folder directly onto Netlify Drop or Vercel.

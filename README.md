# Personal Journal App (MVP)

A simple **password-protected personal journal app** built with **HTML, TailwindCSS, and JavaScript**.  
Entries are saved in **localStorage** so they stay even after refreshing the page.

---

## ✨ Features
- 🔑 Password-protected login (hardcoded password).
- 📝 Add journal entries with title, content, and mood emoji.
- 📅 Filter entries by date.
- 🔍 Search entries by text.
- 💾 Data persists in the browser using localStorage.
- 🚪 Logout to lock the journal.

---

## 🚀 Getting Started
1. Clone this repository or download the `index.html` file.
2. Open `index.html` in your browser.
3. Enter the password (**default: `journal123`**).
4. Start writing your entries!

---

## 🔧 Customization
- To change the password, edit:
  ```js
  const JOURNAL_PASSWORD = "journal123";

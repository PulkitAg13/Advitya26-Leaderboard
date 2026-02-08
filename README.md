# 🎮 PlayTopia Referral Leaderboard

A live, auto-updating **Referral Leaderboard** for the **PlayTopia** event organized by **BitByBit Club** at **Advitya ’26**.  
The leaderboard dynamically ranks club members based on the number of registrations received through referrals.

---

## 📌 Features

- 📊 Live leaderboard synced with Google Forms
- 🔄 Automatic refresh every hour
- 🏅 Medal-based ranking for Top 3
- 📱 Fully responsive (mobile & desktop)
- ⚡ No backend or database required
- ☁️ Uses Google Sheets as the data source

---

## 🧠 How It Works

1. **Registrations** are collected via a Google Form.
2. Each form response contains a **Referral Code** and **Team Member details**.
3. Google Sheets:
   - Counts total registrations per referral
   - Supports **team-based entries (1–4 members per registration)**
4. The leaderboard webpage:
   - Fetches the processed data as **TSV**
   - Sorts and displays it in real time

---

## 🗂️ Data Source

The leaderboard reads data from a **published Google Sheet** (TSV format):

### Required Sheet Format

| Referral Code | Registrations |
|--------------|---------------|
| Aritra       | 7             |
| Pulkit       | 3             |

- Referral Code → Column A
- Total Registrations → Column B

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **Google Sheets (Published as TSV)**
- **Font Awesome (Icons)**

---

## 🚀 Setup Instructions

1. Clone or download the project
2. Open `index.html` in a browser  
   **OR**
3. Host it using:
   - GitHub Pages
   - Netlify
   - Vercel
   - Any static hosting service

No build steps required.

---

## ⏱️ Auto Refresh

- Leaderboard refreshes automatically every **1 hour**
- Manual refresh happens on page reload

---

## 🎨 Customization

You can easily modify:
- Event name
- Club name
- Color theme
- Refresh interval
- Ranking styles

All styles are defined inside `index.html`.

---

## 🔐 Privacy & Security

- The Google Sheet is **read-only**
- No personal user data is exposed
- No authentication or API keys required

---

## 📸 Preview

Top 3 referrals are highlighted with:
- 🥇 Gold
- 🥈 Silver
- 🥉 Bronze

---

## 👥 Organized By

**BitByBit Club**  
Event: **PlayTopia**  
Festival: **Advitya ’26**

---

## 📬 Support

If you face issues or want to extend this leaderboard (dark mode, search, real-time updates), feel free to reach out to the BitByBit Club tech team.

---

✨ *Built for BitByBit Club, by Pulkit Agrawal.*



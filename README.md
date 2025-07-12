
# 💸 Samk's Cash

**Smart. Simple. Spoken.**  
A voice- and photo-powered income & expense tracker for small traders.

## 🎯 About the Project

Samk’s Cash is a human-centered, joy-driven mobile/web app built for small-scale traders and informal business owners. Many of them don't track their daily earnings or purchases — which makes it hard to know whether they’re making a profit.

This app makes it effortless to **track income and expenses** using **voice input or photos**, eliminating the need for typing or complex bookkeeping.

> “Talk. Snap. Track. Grow.”

## 🔍 Problem Statement

**Challenge:** Small traders struggle to keep financial records due to lack of time, literacy, or digital access.

**Goal:** Build a lightweight solution that uses voice/photo input to help them track their income and expenses in real-time — with zero hassle.

## ✨ Features

- 🎙️ **Voice Input** – Speak your sales/purchases in simple language  
- 📸 **Photo Input** – Take a picture of receipts or product tags
- 📊 **Profit/Loss Dashboard** – Real-time income vs expenses summary
- 📂 **Offline-First** – Use the app even with poor connectivity
- 🌍 **Multi-Language Ready** – Easy to adapt for Swahili, Somali, etc.

## 🛠️ Tech Stack

| Layer        | Tool / Tech              |
|--------------|---------------------------|
| Frontend     | MGX / Rork.app (prototype) |
| Backend      | Supabase / Lovable.dev     |
| AI Processing| Claude.ai / Whisper API    |
| Code Assist  | Cursor AI                  |
| Design       | MGX                        |
| Hosting      | Netlify / Vercel (optional)|

## 🧠 Prompt Engineering

We use AI prompts to:
- Convert voice to structured sales data
- Extract totals from receipt photos
- Automatically categorize transactions

**Example Prompt:**
> "Sold 3 tomatoes at 10 each."  
→ **Output:** Income Entry | Item: Tomato | Qty: 3 | Total: 30 KES

## 🚀 Getting Started (For Developers)

### 1. Clone the repo
```bash
git clone https://github.com/your-username/samks-cash.git
cd samks-cash
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the app locally
```bash
npm run dev
```

## 📦 Folder Structure

```
samks-cash/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── utils/
├── supabase/
├── assets/
└── README.md
```

## 🧪 Testing

- [ ] Voice entry works
- [ ] Photo entry works (receipt reading)
- [ ] Offline mode functionality
- [ ] Dashboard updates correctly
- [ ] Secure storage and backup

## 🧑‍💼 Target Users

- Small-scale shopkeepers
- Market vendors
- Mama mbogas
- Kiosk and hawker owners

## 💰 Business Model

- **Free Tier** – Up to 20 entries/month
- **Pro Tier** – Unlimited entries, insights, and backups

## 📈 Scalability & Growth

- Expand to East Africa (Swahili support)
- Add MPESA sync, bulk CSV export, and AI-powered business tips
- Web and USSD version for offline traders

## 👤 Developer

**Name:** Samira Hassannoor Sheikh Ahmed  
**Project:** Vibe Coding Hackathon — For the #1MillionDevs Movement

## 🙌 Acknowledgements

Thanks to:
- **Power Learn Project** for the opportunity  
- **Supabase, Lovable.dev, MGX, Cursor AI** for tools  
- The local traders inspiring this build 💚
- My Pitch Deck:https://www.canva.com/design/DAGo1Yi-f-I/o3Mdf5yNGzSEfvKCY0RoEA/edit?utm_content=DAGo1Yi-f-I&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

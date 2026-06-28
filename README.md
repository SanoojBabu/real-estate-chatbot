# 🏛️ Confident Group — AI Property Assistant (Priya)

> **Stage 2 Technical Assessment · Task 2**
> AI Automation & Integration Executive · Bangalore Technology Team

![AI](https://img.shields.io/badge/AI-Google%20Gemini%202.5%20Flash-blue?style=flat-square)
![Deployed](https://img.shields.io/badge/Deployed-GitHub%20Pages-222?style=flat-square&logo=github)
![HTML](https://img.shields.io/badge/Built%20with-HTML%20%2F%20JS-orange?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)
![Cost](https://img.shields.io/badge/API%20Cost-Free-success?style=flat-square)

---

## 🌐 Live Demo

**👉 [https://sanoojbabu.github.io/real-estate-chatbot](https://sanoojbabu.github.io/real-estate-chatbot/)**

---

## 📌 Overview

**Priya** is a branded AI property assistant built for Confident Group, a premium real estate developer in Kerala, India.

Deployed as a single HTML file on GitHub Pages, Priya provides **24/7 intelligent customer engagement** — answering property FAQs, sharing project brochures, guiding NRI investors, and helping customers book site visits — all without any human involvement.

The chatbot is powered by **Google Gemini 2.5 Flash** (free API tier), trained on Confident Group's project knowledge base via a detailed system prompt, and requires **no backend server, no database, and no paid hosting**.

---

## ✨ Features

| Feature | Details |
|---|---|
| 🤖 AI-powered responses | Google Gemini 2.5 Flash — fast, accurate, context-aware |
| 🏠 Real estate knowledge base | 5 projects, pricing, locations, amenities, brochures |
| 💬 Conversation memory | Full chat history maintained within the session |
| ⚡ 8 quick-topic buttons | Apartments, Villas, Locations, Pricing, Brochures, NRI, Site Visit, Home Loans |
| 📄 Instant brochure links | AI shares direct PDF links when projects are discussed |
| ✈️ NRI guidance | Dedicated responses for NRI investors across UAE, UK, US, AU |
| 🕐 Timestamps | Every message timestamped for professionalism |
| 🗑️ Clear chat | Reset conversation with one click |
| 📱 Mobile responsive | Sidebar hides on mobile — full chat view |
| 🎨 Branded UI | Confident Group navy & gold / red & white theme |
| 🔒 API key stored locally | Key saved in browser localStorage — never sent to any server |
| 🆓 Zero cost | Google Gemini free tier — 1,500 requests/day |

---

## 🖥️ Screenshots

### Desktop View
```
┌─────────────────────┬────────────────────────────────────────┐
│                     │  🏛️ Priya — Property Assistant         │
│  🏛️ Confident Group │  ● Online · Powered by Google Gemini   │
│  Premium Properties │                                        │
│                     │  Welcome to Confident Group! I'm       │
│  Find your ideal    │  Priya, your AI property assistant.    │
│  property with AI   │                                        │
│                     │  I can help you with:                  │
│  ── Quick topics ── │  • Residential & commercial projects   │
│                     │  • Pricing, locations & floor plans    │
│  🏙️ Apartments      │  • Project brochures                   │
│  🌿 Villa Projects  │  • NRI investment guidance             │
│  📍 Locations       │  • Booking a site visit                │
│  💰 Pricing         │                                        │
│  📄 Brochures       │  What kind of property are you         │
│  ✈️ NRI Investment  │  looking for today?          14:32     │
│  🗓️ Book Visit      │                                        │
│  🏦 Home Loans      │  ┌─────────────────────────────┐  [▶] │
│                     │  │ Ask about projects, pricing… │      │
│  25+  50+  4        │  └─────────────────────────────┘      │
│  Yrs  Proj Cities   │                                        │
└─────────────────────┴────────────────────────────────────────┘
```

---

## 🏗️ Architecture

```
Customer opens chatbot URL (GitHub Pages)
              │
              ▼
    ┌─────────────────────┐
    │  Single HTML File   │  ← No server, no framework, no build step
    │  (index.html)       │
    └────────┬────────────┘
             │  User types message
             ▼
    ┌─────────────────────┐
    │  JavaScript fetch() │  ← Sends to Gemini API with:
    │                     │     - System prompt (knowledge base)
    └────────┬────────────┘     - Full conversation history
             │
             ▼
    ┌─────────────────────────────────────────┐
    │  Google Gemini 2.5 Flash API            │
    │  generativelanguage.googleapis.com      │
    │                                         │
    │  System prompt contains:                │
    │  ✓ Confident Group company info         │
    │  ✓ 5 current projects with full details │
    │  ✓ Pricing, locations, amenities        │
    │  ✓ Brochure URLs                        │
    │  ✓ Contact & booking info               │
    │  ✓ Home loan bank tie-ups               │
    │  ✓ NRI desk details                     │
    │  ✓ Response rules & persona (Priya)     │
    └────────┬────────────────────────────────┘
             │  AI response
             ▼
    ┌─────────────────────┐
    │  Render in chat UI  │  ← Markdown formatted, timestamped,
    │                     │     links clickable, animations applied
    └─────────────────────┘
```

---

## 🏠 Knowledge Base — Confident Group Projects

Priya is trained on the following project data via the system prompt:

| # | Project | Location | Type | Price Range | Status |
|---|---|---|---|---|---|
| 1 | Confident Tranquil Villas | Kakkanad, Kochi | 3BHK & 4BHK Villas | ₹1.8Cr – ₹3.2Cr | Under construction |
| 2 | Confident Skyline Residences | Edapally, Kochi | 2BHK & 3BHK Apartments | ₹75L – ₹1.4Cr | Ready to occupy |
| 3 | Confident Heritage Homes | Thrissur | Kerala-style Villas | ₹1.2Cr – ₹2.1Cr | Ready to occupy |
| 4 | Confident Greenfields | Kozhikode | Plots + 2BHK Villas | From ₹45L | New launch |
| 5 | Confident Corporate Park | Marine Drive, Kochi | Commercial offices | ₹95L – ₹3.5Cr | Possession Q1 2027 |

**Additional knowledge included:**
- Sales contact numbers and office address
- Home loan tie-ups (SBI, HDFC, ICICI, Axis, Federal Bank)
- NRI desk contact and FCNR loan guidance
- Site visit booking process (free, 7 days/week, 9AM–6PM)
- WhatsApp and email enquiry channels

---

## 📂 Repository Structure

```
confident-group-chatbot/
│
├── index.html       ← Complete chatbot (single file — UI + AI + logic)
├── .nojekyll        ← Disables Jekyll build on GitHub Pages
└── README.md        ← You are here
```

> The entire application is **one self-contained HTML file**. No `npm install`, no build process, no dependencies to manage.

---

## 🚀 Setup & Deployment

### Step 1 — Get a Free Google Gemini API Key

1. Go to **[aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)**
2. Sign in with your Google account
3. Click **Create API Key** → Copy and save it
4. Free tier: **1,500 requests/day** — no credit card required

---

### Step 2 — Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `confident-group-chatbot`)
2. Upload these two files:
   - `index.html` (rename from `confident_group_chatbot_FINAL.html`)
   - `.nojekyll` (empty file — prevents Jekyll build errors)
3. Go to **Settings → Pages**
4. Under **Build and deployment** → Source: **Deploy from a branch**
5. Branch: `main` | Folder: `/ (root)` → click **Save**
6. Wait 60–90 seconds → your live URL appears:

```
https://YOUR-USERNAME.github.io/confident-group-chatbot/
```

---

### Step 3 — Use the Chatbot

1. Open the live URL (or `index.html` locally in Chrome)
2. Paste your **Google Gemini API key** in the gold bar at the top
3. Click **Connect**
4. Start chatting with Priya!

> The API key is stored in your browser's `localStorage` — it persists across page refreshes so you only enter it once per device.

---

### Local Development (No Deployment Needed)

```bash
# No installation required — just open the file
# Option 1: Double-click index.html in your file explorer
# Option 2: Run a local server
npx serve .
# Then open http://localhost:3000
```

---

## 💬 Sample Conversations

**Lead qualifying through chat:**
```
Customer: I'm looking for a 3BHK apartment in Kochi under 1.5 crore
Priya:    Confident Skyline Residences in Edapally is a great match!
          It offers 3BHK apartments from ₹95L – ₹1.4Cr with rooftop
          infinity pool, smart home tech and Metro connectivity.
          Here's the brochure: https://confidentgroup.com/skyline-brochure
          Would you like to book a free site visit this weekend?
```

**NRI investor enquiry:**
```
Customer: I'm an NRI in Dubai looking for investment property
Priya:    Welcome! For NRI investors, I'd recommend two options:
          • Confident Heritage Homes (Thrissur) — cultural living,
            Vastu-compliant, strong rental demand — from ₹1.2Cr
          • Confident Greenfields (Kozhikode) — best ROI,
            plotted development — from ₹45L
          Our dedicated NRI desk can assist with FCNR loans and
          legal paperwork: nri@confidentgroup.com | +91-484-123-4568
          Shall I help you schedule a video call with our NRI advisor?
```

**Brochure request:**
```
Customer: Can I get a brochure for the villa project?
Priya:    Of course! Here are our villa projects:
          🌿 Tranquil Villas (Kakkanad, Kochi):
             https://confidentgroup.com/tranquil-villas-brochure
          🏡 Heritage Homes (Thrissur):
             https://confidentgroup.com/heritage-homes-brochure
          Which location interests you more?
```

---

## 🛡️ AI Persona & Rules

Priya follows strict response rules defined in the system prompt:

| Rule | Behaviour |
|---|---|
| Identity | Always responds as "Priya from Confident Group" |
| Accuracy | Never fabricates project details not in knowledge base |
| Brochures | Always shares URL when a specific project is discussed |
| Pricing | Gives listed range; refers negotiation to sales team |
| Unknown projects | "Let me connect you with our team for the latest list" |
| NRI customers | Highlights Heritage Homes + Greenfields; mentions NRI desk |
| Ready buyers | Proactively offers to help book a site visit |
| Tone | Warm, professional, never pushy |

---

## ⚙️ Technical Details

| Detail | Value |
|---|---|
| AI model | `gemini-2.5-flash` |
| API endpoint | `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash:generateContent` |
| Max output tokens | 1,024 per response |
| Temperature | 0.7 (balanced creativity + accuracy) |
| Context window | Full conversation history sent each request |
| Hosting | GitHub Pages (free, static) |
| Dependencies | None — vanilla HTML/CSS/JS only |
| Browser support | Chrome, Firefox, Safari, Edge |
| Mobile | Fully responsive |

---

## 🔒 Privacy & Security

- The Gemini API key is stored only in the **user's browser localStorage**
- No user data is sent to any third-party server other than Google's Gemini API
- No backend, no database, no cookies
- Conversation history exists only in browser memory — cleared on page refresh or "Clear chat"

---

## 🆓 Cost Breakdown

| Resource | Cost |
|---|---|
| GitHub Pages hosting | Free |
| Google Gemini 2.5 Flash API | Free — 1,500 requests/day |
| Domain (github.io subdomain) | Free |
| **Total monthly cost** | **₹0** |

> For production scale (10,000+ conversations/day), the Gemini API paid tier starts at approximately ₹0.01 per request — still significantly cheaper than hiring a customer support agent.

---

## 🔮 Future Enhancements

| Enhancement | Description |
|---|---|
| WhatsApp integration | Route chatbot to WhatsApp Business API |
| Lead capture form | Collect name/email/phone within chat flow |
| CRM sync | Auto-create HubSpot contact from chat conversation |
| Multi-language | Malayalam + English responses for local customers |
| Voice input | Web Speech API for voice-to-text queries |
| Analytics | Track most asked questions via Google Analytics |

---

## 🧠 Built By

**Sanooj Babu Kakkoth**

AI Automation & Integration Executive Candidate
Confident Group — Bangalore Technology Team · 2026

---

## 📄 Licence

This project was built as part of a technical assessment for Confident Group and is intended for demonstration purposes.

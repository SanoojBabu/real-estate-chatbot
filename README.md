# 🏛️ Confident Group — AI Property Assistant (Priya)

> **Stage 2 Technical Assessment · Task 2**
> AI Automation & Integration Executive · Bangalore Technology Team

![AI](https://img.shields.io/badge/AI-Google%20Gemini%202.5%20Flash-blue?style=flat-square)
![Deployed](https://img.shields.io/badge/Deployed-GitHub%20Pages-222?style=flat-square&logo=github)
![HTML](https://img.shields.io/badge/Built%20with-HTML%20%2F%20JS-red?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)
![Cost](https://img.shields.io/badge/API%20Cost-Free-success?style=flat-square)
![Projects](https://img.shields.io/badge/Projects-14%20across%204%20regions-darkred?style=flat-square)

---

## 🌐 Live Demo

**👉 [https://YOUR-USERNAME.github.io/real-estate-chatbot](https://sanoojbabu.github.io/real-estate-chatbot)**

> Replace `YOUR-USERNAME` with your GitHub username after deployment.

---

## 📌 Overview

**Priya** is a branded AI property assistant built for Confident Group — a premium international real estate developer with projects across **Kerala, Bangalore, Dubai (UAE), and the USA**.

Deployed as a single HTML file on GitHub Pages, Priya provides **24/7 intelligent customer engagement** — answering property FAQs, sharing project brochures, guiding NRI investors across four countries, and helping customers book site visits or video calls — all without any human involvement.

The chatbot is powered by **Google Gemini 1.5 Flash** (free API tier), trained on Confident Group's full international project portfolio via a detailed system prompt, and requires **no backend server, no database, and no paid hosting**.

---

## ✨ Features

| Feature | Details |
|---|---|
| 🤖 AI-powered responses | Google Gemini 2.5 Flash — fast, accurate, context-aware |
| 🌍 International knowledge base | 14 projects across Kerala, Bangalore, Dubai & USA |
| 💬 Conversation memory | Full chat history maintained within the session |
| ⚡ 8 region-based quick chips | Kerala, Bangalore, Dubai, USA, Pricing, Brochures, NRI, Book Visit |
| 📄 Instant brochure links | AI shares direct PDF links when projects are discussed |
| ✈️ Smart NRI routing | Asks which country customer is in → recommends relevant projects |
| 🇦🇪 UAE Golden Visa guidance | Flags eligibility for Dubai properties above AED 2 million |
| 🇺🇸 US mortgage assistance | H1B & Green Card holder guidance for NJ & California properties |
| 🕐 Timestamps | Every message timestamped for professionalism |
| 🗑️ Clear chat | Reset conversation with one click |
| 📱 Mobile responsive | Sidebar hides on mobile — full chat view |
| 🎨 Branded UI | Confident Group red, white & maroon color theme |
| 🔒 Secure API key handling | Key saved in browser localStorage — never hardcoded in code |
| 🆓 Zero hosting cost | Google Gemini free tier — 1,500 requests/day |

---

## 🖥️ Interface Preview

```
┌──────────────────────┬──────────────────────────────────────────┐
│                      │  🏛️ Priya — Property Assistant           │
│  🏛️ Confident Group  │  ● Online · Kerala · Bangalore ·        │
│  Premium Properties  │          Dubai · USA                     │
│                      │                                          │
│  Find your ideal     │  Welcome to Confident Group! I'm Priya. │
│  property anywhere   │                                          │
│  in the world        │  Properties across:                      │
│                      │  🌴 Kerala — Kochi, Thrissur, Kozhikode  │
│  ── Quick topics ──  │  🏙️ Bangalore — Whitefield, Sarjapur    │
│                      │  🇦🇪 Dubai — Downtown, Marina, Bay       │
│  🌴 Kerala Projects  │  🇺🇸 USA — New Jersey & California       │
│  🏙️ Bangalore        │                                          │
│  🇦🇪 Dubai           │  What kind of property are you looking   │
│  🇺🇸 USA Properties  │  for today?                   12:44 PM  │
│  💰 Pricing          │                                          │
│  📄 Brochures        │  ┌──────────────────────────────┐  [▶]  │
│  ✈️ NRI Investment   │  │ Ask about projects, pricing… │       │
│  🗓️ Book a Visit     │  └──────────────────────────────┘       │
│                      │                                          │
│  25+  80+  4         │   Kerala · Bangalore · Dubai · USA © 2026│
│  Yrs  Proj Countries │                                          │
└──────────────────────┴──────────────────────────────────────────┘
```

---

## 🏗️ Architecture

```
Customer opens chatbot URL (GitHub Pages)
              │
              ▼
    ┌──────────────────────┐
    │   Single HTML File   │  ← No server, no framework, no build step
    │   (index.html)       │    Red / White / Maroon brand theme
    └────────┬─────────────┘
             │  User types message / clicks quick chip
             ▼
    ┌──────────────────────┐
    │  JavaScript fetch()  │  ← Sends to Gemini API with:
    │                      │     · System prompt (full knowledge base)
    └────────┬─────────────┘     · Full conversation history
             │
             ▼
    ┌───────────────────────────────────────────────┐
    │  Google Gemini 1.5 Flash API                  │
    │  generativelanguage.googleapis.com            │
    │                                               │
    │  System prompt trains Priya with:             │
    │  ✓ 14 projects across 4 regions               │
    │  ✓ Full pricing, sizes, features per project  │
    │  ✓ Brochure URLs for every project            │
    │  ✓ Regional contact offices (India/UAE/USA)   │
    │  ✓ Home loan & mortgage partners per country  │
    │  ✓ UAE Golden Visa & US visa guidance         │
    │  ✓ NRI smart routing by country               │
    │  ✓ Response rules & Priya persona             │
    └────────┬──────────────────────────────────────┘
             │  AI response
             ▼
    ┌──────────────────────┐
    │  Render in chat UI   │  ← Markdown formatted, timestamped,
    │                      │     links clickable, animations applied
    └──────────────────────┘
```

---

## 🌍 Project Portfolio — All 14 Properties

### 🌴 Kerala Projects (5)

| # | Project | Location | Type | Price Range | Status |
|---|---|---|---|---|---|
| 1 | Confident Tranquil Villas | Kakkanad, Kochi | 3BHK & 4BHK Villas | ₹1.8Cr – ₹3.2Cr | Under construction |
| 2 | Confident Skyline Residences | Edapally, Kochi | 2BHK & 3BHK Apartments | ₹75L – ₹1.4Cr | Ready to occupy |
| 3 | Confident Heritage Homes | Thrissur | Kerala-style Villas | ₹1.2Cr – ₹2.1Cr | Ready to occupy |
| 4 | Confident Greenfields | Kozhikode | Plots + 2BHK Villas | From ₹45L | New launch |
| 5 | Confident Corporate Park | Marine Drive, Kochi | Commercial offices | ₹95L – ₹3.5Cr | Possession Q1 2027 |

### 🏙️ Karnataka Projects (3)

| # | Project | Location | Type | Price Range | Status |
|---|---|---|---|---|---|
| 6 | Confident Urban Heights | Whitefield, Bangalore | 2BHK & 3BHK Apartments | ₹85L – ₹1.8Cr | Under construction |
| 7 | Confident Serene Valley | Sarjapur Road, Bangalore | Villas + Row Houses | ₹1.6Cr – ₹3.8Cr | Ready to occupy |
| 8 | Confident Tech Square | Electronic City, Bangalore | Commercial IT offices | ₹70L – ₹2.8Cr | New launch |

### 🇦🇪 Dubai (UAE) Projects (3)

| # | Project | Location | Type | Price Range | Status |
|---|---|---|---|---|---|
| 9 | Confident Pearl Residences | Downtown Dubai | 1–3BHK Luxury Apartments | AED 950K – 4.2M | Under construction |
| 10 | Confident Marina Cove | Dubai Marina | Studio, 1BHK & 2BHK | AED 650K – 2.8M | Ready to move |
| 11 | Confident Business Bay Tower | Business Bay | Commercial offices | AED 1.2M – 8.5M | Ready to occupy |

### 🇺🇸 USA Projects (3)

| # | Project | Location | Type | Price Range | Status |
|---|---|---|---|---|---|
| 12 | Confident Metro Living | Jersey City, NJ | 1–3BR Condominiums | USD 450K – 1.2M | Under construction |
| 13 | Confident Silicon Homes | Edison, NJ | Townhouses & Homes | USD 650K – 1.5M | Ready to occupy |
| 14 | Confident Innovation Park | Fremont, CA | 2–3BR Condominiums | USD 800K – 1.8M | New launch |

---

## 🤖 AI Intelligence by Region

| Region | Special AI Capabilities |
|---|---|
| 🌴 Kerala | FCNR loan guidance, NRI return family focus, Vastu compliance info |
| 🏙️ Bangalore | IT corridor proximity, rental yield analysis, tech professional focus |
| 🇦🇪 Dubai | UAE Golden Visa eligibility (AED 2M+), freehold info, 7–9% rental yield |
| 🇺🇸 USA | H1B & Green Card mortgage guidance, school district info, Silicon Valley proximity |
| ✈️ NRI Global | Asks which country customer is in → routes to most relevant projects automatically |

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
2. Sign in with your Google account — no credit card required
3. Click **Create API Key** → copy and save it
4. Free tier: **1,500 requests/day**

> ⚠️ **Security rule:** Never paste your API key into the HTML file itself. Always enter it via the in-browser input bar. This prevents exposure on GitHub and key invalidation by Google.

---

### Step 2 — Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `real-estate-chatbot`)
2. Upload both files to the repository root:
   - `index.html`
   - `.nojekyll` ← empty file, prevents Jekyll build errors
3. Go to **Settings → Pages**
4. Source: **Deploy from a branch** → Branch: `main` → Folder: `/ (root)` → **Save**
5. Wait 60–90 seconds → live URL appears:

```
https://YOUR-USERNAME.github.io/confident-group-chatbot/
```

---

### Step 3 — Connect and Use

1. Open the live URL (or `index.html` locally in Chrome)
2. Paste your **Google Gemini API key** into the red input bar at the top
3. Click **Connect** — a confirmation toast appears
4. Start chatting with Priya!

> The API key is stored in your browser's `localStorage` — it persists across page refreshes so you only need to enter it once per device.

---

### Local Testing (No Deployment Needed)

```bash
# No installation required
# Option 1: Double-click index.html — opens directly in Chrome/Edge
# Option 2: Run a quick local server
npx serve .
# Open http://localhost:3000
```

---

## 💬 Sample Conversations

**Kerala buyer:**
```
Customer: I'm looking for a 3BHK apartment in Kochi under 1.5 crore
Priya:    Confident Skyline Residences in Edapally is a great match!
          3BHK apartments from ₹95L – ₹1.4Cr with rooftop infinity pool,
          smart home tech and direct Metro connectivity.
          Brochure: https://confidentgroup.com/skyline-brochure
          Would you like to book a free site visit this weekend?
```

**NRI from Dubai:**
```
Customer: I'm an NRI based in Dubai looking for investment property
Priya:    Since you're in Dubai, I have options in both UAE and India!
          🇦🇪 Marina Cove (Dubai Marina) — 7–9% rental yield, ready to move
          🌴 Heritage Homes (Thrissur) — ideal for NRI families returning home
          Which interests you more — UAE investment or India?
```

**US-based H1B buyer:**
```
Customer: I'm on H1B in New Jersey, looking to buy a home
Priya:    Confident Silicon Homes in Edison NJ is perfect for you!
          Top-rated Edison schools, Indian community neighbourhood,
          from USD 650K. Our mortgage partners have H1B-specific programs.
          A few units remaining — shall I arrange a viewing?
```

**Dubai Golden Visa enquiry:**
```
Customer: Can I get UAE Golden Visa with a property purchase?
Priya:    Yes! Confident Pearl Residences in Downtown Dubai qualifies.
          Properties above AED 2 million are eligible for the UAE
          10-year Golden Visa. Our Dubai team manages the full process.
          Shall I connect you with our Dubai advisor?
```

---

## 🛡️ AI Persona & Response Rules

| Rule | Behaviour |
|---|---|
| Region detection | Identifies customer's country/city → leads with relevant projects |
| NRI smart routing | Asks which country customer is in before recommending |
| Brochures | Always shares URL when a specific project is discussed |
| Pricing | Gives listed range; refers negotiation to regional sales team |
| Golden Visa | Flags UAE Golden Visa eligibility for Dubai properties AED 2M+ |
| US visa | Mentions H1B/Green Card mortgage eligibility for USA projects |
| Unknown projects | Refers customer to the relevant regional team |
| Ready buyers | Offers site visit (India) or video call (Dubai/USA) |
| Accuracy | Never fabricates project details not in the knowledge base |
| Tone | Warm, professional, never pushy |

---

## ⚙️ Technical Specifications

| Detail | Value |
|---|---|
| AI model | `gemini-1.5-flash` |
| API endpoint | `https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent` |
| Max output tokens | 1,024 per response |
| Temperature | 0.7 (balanced creativity + accuracy) |
| Context window | Full conversation history sent with each request |
| Hosting | GitHub Pages (free, static) |
| Framework | None — pure vanilla HTML / CSS / JavaScript |
| Total file count | 1 self-contained file |
| Browser support | Chrome, Firefox, Safari, Edge |
| Mobile | Fully responsive — sidebar collapses on small screens |

---

## 🔒 Security & Privacy

- API key entered via **in-browser UI bar only** — never hardcoded in the file
- Key stored in **browser localStorage** on user's own device only
- No user data sent to any server other than Google's Gemini API
- No backend, no database, no third-party analytics, no cookies
- Conversation history clears on page refresh or "Clear chat"

---

## 🏢 Regional Contact Details

| Region | Phone | Email |
|---|---|---|
| Kerala HQ | +91-484-123-4567 | sales@confidentgroup.com |
| Bangalore | +91-80-123-4567 | bangalore@confidentgroup.com |
| Dubai | +971-4-123-4567 | dubai@confidentgroup.com |
| USA — New Jersey | +1-732-123-4567 | usa@confidentgroup.com |
| NRI Desk (Global) | +91-484-123-4568 | nri@confidentgroup.com |

---

## 🆓 Cost Breakdown

| Resource | Cost |
|---|---|
| GitHub Pages hosting | Free |
| Google Gemini 2.5 Flash API | Free — 1,500 requests/day |
| Domain (github.io subdomain) | Free |
| **Total monthly cost** | **₹0 / AED 0 / USD 0** |

> For production scale (10,000+ conversations/day), Gemini API paid tier costs approximately ₹0.01 per request — a fraction of hiring multilingual support staff across four countries.

---

## 🔮 Future Enhancements

| Enhancement | Description |
|---|---|
| WhatsApp integration | Route chatbot to WhatsApp Business API for all four regions |
| Lead capture in chat | Collect name/email/phone → auto-feed into Task 1 Lead Qualification workflow |
| CRM sync | Auto-create HubSpot contact from every chat conversation |
| Currency switcher | Toggle between ₹, AED, and USD dynamically per region |
| Multi-language | Malayalam, Kannada, Arabic alongside English |
| Voice input | Web Speech API for voice-to-text queries |
| Video call booking | Calendly integration for Dubai and USA consultations |

---

## 🧠 Built By

**Sanooj Babu Kakkoth**
AI Automation & Integration Executive Candidate
Confident Group — Bangalore Technology Team · 2026

---

## 📄 Licence

This project was built as part of a technical assessment for Confident Group and is intended for demonstration purposes.

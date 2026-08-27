## Hi, I am Karen

I work between the business and the data team. Listening to the problem, working out what is actually needed, and turning it into something a technical team can build — that is the thread through my career in product management and data.

Most of my attention goes to structure. Tools get replaced every few years, but if the data underneath is modelled badly, no amount of clever technology saves it. So I care about getting the data structure and the business logic right, and about whether people actually end up using what gets built.

I am not a software engineer by training. I am a product and data person who learned to build by building — mostly to find out first-hand what these tools can and cannot do. Everything here is a working prototype rather than a production system, and I would rather be honest about that than oversell it.

### Things I have built

**Sift** — Job-search automation platform. Pulls listings from email alerts, direct ATS APIs and third-party search into a Notion database, scores each role against user preferences and past triage decisions using Claude, auto-filters low-fit roles, and generates a tailored resume and cover letter when a role is marked to apply. Runs three times a day on GitHub Actions at ~$5 a month. I am using it live for my current job hunt.

**MyEpitaph** — End-of-life planning platform. Zero-knowledge, client-side AES-256 encryption so the server never sees plaintext. Executor verification protocol, dead-man's-switch heartbeat, scheduled recurring messages, and a 3D casket designer with Stripe pre-order. Built for a domain where privacy and trust have to be design decisions, not settings added at the end.

**TrailMates** — Real-time social fitness app for runners, cyclists and hikers. Live GPS recording, GPX import and export, an augmented-reality proximity radar rendered over the phone camera, and a Challengers-vs-Mates model that separates training partners from public competitors. Falls back to a self-drawn compass canvas when the maps API key is absent, so nothing blocks testing.

**Beanology** — Coffee and mixology sensory matching platform. Recommends specialty beans from ambient weather and mood, then generates dual-extraction brewing specs (hot and cold) and paired global gastronomy that deliberately avoids the usual protein tropes. Includes an admin panel that live-searches roasters and one-click syncs bean profiles into Firestore.

**HungryJury** — Real-time multi-user group dining decision engine. Socket.IO synchronizes cravings, weather context and votes across devices in a live "jury" session; Gemini deliberates a Top 10 verdict. Hong Kong sessions auto-enrich with OpenRice ratings and links. Packaged for native Android and iOS via Capacitor.

**Serene Pause** — Collaborative emotional-support sanctuary. Up to four friends can join a shared session where any participant can switch the AI's temperament on the fly — "Ride or Die" validation, "Devil's Advocate" reframing, "Warm Presence" counselling, or "Ancient Soul" stoicism. Includes a guided meditation space and a bubble-popping stress mini-game with synchronized scores.

**CryptoPredict AI** — Cryptocurrency market intelligence dashboard. Live technical indicators (RSI, SMA 50/200, MACD) alongside multi-horizon Gemini forecasts for next-day, next-week and next-month, each with confidence rating and support/resistance levels. What makes it different: a persistent accuracy audit engine backed by Firestore that benchmarks every past prediction against live market prices, plus MetaMask integration for AI portfolio allocation advice.

**HK Mark 6 Analytics** — Statistical dashboard and number generator for the Hong Kong Mark 6 lottery. The app opens with a disclaimer that every draw is an independent random event and no algorithm can predict future results — because that is true. It is built for people who would otherwise pick birthdays or quick-picks and would prefer to see 15 years of historical distribution, hot/cold intervals, sum ranges and parity ratios instead. Fifteen statistical and machine-learning models (frequency analysis, ARIMA, Monte Carlo, XGBoost, and others) run on that data. Purely for fun — no signal in the numbers, only in the visualisation.

**Fervent Prayer Curator** — AI-powered prayer companion. Generates biblically grounded prayers inspired by different theological voices (Apostle Paul, King David, and others), paired with 5–7 supporting scripture references and contextual commentary. Supports 16+ languages including Chinese, Japanese, Arabic and Hindi. Installable as a Progressive Web App with native share to WhatsApp and email.

**Mahjong Faan Calculator** — Native Android app that scores mahjong hands from a photo. Gemini Vision reads the tiles, then one of five deterministic rule engines (Hong Kong, Taiwanese, Vietnamese, Shanghainese, Shenzhen) calculates the faan/tai/phán count and works out who owes what to whom — seat winds, self-draw versus discard liability, half-spicy or full-spicy stake progressions. Kotlin with Jetpack Compose, MVVM. The first native Android build in this list; the others are web or PWA.

### What I work with

**Building:** React, TypeScript, Tailwind CSS, Google AI Studio, Copilot Studio, Kotlin & Jetpack Compose

**Data:** SQL, Power BI, Tableau, Alteryx, data modelling and governance

**Thinking about:** data structure, master data, open standards, privacy by design, and why good platforms still fail to get adopted

### A few things I believe

- The platform matters far less than the structure underneath it.
- A well-built system nobody uses has failed.
- Privacy is a design decision, not a setting added at the end.
- The hard skills are cheaper than they have ever been. Judgment, an opinion about what is worth building, and the persistence to finish are not.

---

Based in Hong Kong. I like messy data problems and clear explanations.

[LinkedIn](https://linkedin.com/in/lamkaren)

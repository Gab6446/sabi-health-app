# Sabi Health: Pitch Deck Outline
**Cavista Hackathon 2026**

This document provides a slide-by-slide structure to help your team build a winning presentation that hits every aspect of the Judging Criteria. 

*Remember: The Presentation is worth **4/20 points** on its own, and influences how the judges score the Business and Technology aspects!*

---

## Slide 1: Title Slide
* **Visual:** Sabi Health logo / catchy imagery
* **Content:** 
  * "Sabi Health: Your Proactive AI Health Companion"
  * Team Name
  * Names of the 3-5 undergraduate members

## Slide 2: The Problem (Business/Real-world Need)
* **Visual:** Statistics on preventable diseases in Nigeria or a relatable scenario.
* **Content:**
  * Rural and underserved urban communities in Nigeria face high mortality rates from preventable diseases (malaria, cholera, etc.).
  * Reactive healthcare puts massive strain on limited hospital resources.
  * Public health warnings are often too broad and not accessible to those without internet or smartphones.

## Slide 3: The Solution (Tech & Creativity)
* **Visual:** High-level diagram of the app flowing from Data -> AI -> Voice Call -> User.
* **Content:**
  * Sabi Health proactively monitors environmental data (e.g., rainfall) and disease hotspots.
  * It generates culturally resonant, localized health advice using **Gemini 1.5 Flash**.
  * It delivers this advice directly to standard feature phones via automated voice calls (synthetic local accents).

## Slide 4: Target Audience & Market Potential (Business)
* **Visual:** Icons representing local communities, government health agencies, and NGOs.
* **Content:**
  * **Primary Users:** At-risk individuals in specific Local Government Areas (LGAs).
  * **Customers (B2B/B2G):** State Ministries of Health, NGOs (like WHO or local charities), and telecom providers as CSR.

## Slide 5: Core Features & UI/UX (Design)
* **Visual:** Screenshots of the Dashboard, Active Outbreak Banner, and File Reports.
* **Content:**
  * Clean, analytics-focused dashboard for health administrators.
  * Real-time risk heatmaps and tracking.
  * Comprehensive file reports for monitoring campaign success and tracking symptom feedback.

## Slide 6: Technical Architecture (Technology)
* **Visual:** Stack logos (React, Tailwind, Gemini, Twilio/Spitch).
* **Content:** 
  * Frontend built with React, Vite, and modern Tailwind CSS UI (Shadcn).
  * Backend interactions simulated to use Open-Meteo API for real-time weather triggers.
  * Voice synthesis architecture designed for local accents.

## Slide 7: Live Demo / Walkthrough (Presentation)
* **Visual:** *[Switch to screen sharing the live app running `npm run dev`]*
* **Action:**
  1. Show the Dashboard and Risk factors.
  2. Trigger a Call Simulation.
  3. Show the resulting detailed log in the "Reports" tab.

## Slide 8: Responsible AI & Data Privacy (Compliance)
* **Visual:** Secure lock icon or privacy shield.
* **Content:** 
  * Mention compliance with Hackathon Rule 5.
  * Emphasize that AI is used safely to generate health scripts, not to diagnose. 
  * All user data is simulated or secured; no private health records are exposed to public LLMs.

## Slide 9: Future Roadmap & Impact
* **Visual:** Timeline or rocket icon.
* **Content:**
  * Multi-language support (Hausa, Igbo, Yoruba).
  * Direct API integration with local clinics for automatic appointment booking.
  * SMS fallbacks for broader reach.

## Slide 10: Conclusion & Q&A
* **Visual:** "Thank You" and link to GitHub Repo.
* **Content:**
  * Reiterate the mission: "Saving lives before the sickness strikes."
  * Open the floor to the judges.

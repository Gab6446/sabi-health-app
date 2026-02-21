# Sabi Health - Proactive Voice AI for Disease Prevention

## Overview
Sabi Health is a comprehensive health monitoring and alert system designed for Nigeria. It uses AI to generate culturally appropriate health messages in Nigerian Pidgin/English and simulates proactive voice calls to at-risk individuals.

## Features

### 1. User Registration
- Simple form to register users with name, phone, and LGA
- Supports 20+ Local Government Areas across Nigeria
- Instant registration with success feedback

### 2. Risk Monitoring Dashboard
- Real-time risk assessment for each registered user
- Color-coded risk levels (HIGH, MEDIUM, LOW)
- Displays rainfall data and disease hotspot information
- Quick statistics overview

### 3. AI-Generated Health Messages
- Culturally appropriate messages in Nigerian Pidgin/English
- Personalized based on user's location and risk factors
- Addresses specific diseases: Lassa Fever, Malaria, Cholera, Typhoid
- Includes practical preventive advice

### 4. Call Simulation
- Immersive incoming call interface
- Animated call states (incoming, active, ended)
- Audio playback simulation
- Interactive response options ("I have fever" / "I'm fine")

### 5. Health Center Referral
- Automatic referral when fever is reported
- Displays nearest health center address for user's LGA
- 20+ health facilities mapped across Nigeria

### 6. Activity Logging
- Complete call history with timestamps
- User responses tracked
- Statistical analysis (total calls, fever reports, healthy reports)
- Exportable data for public health analysis

### 7. Information Panel
- Detailed project documentation
- Technology stack overview
- Responsible AI disclosure
- How-it-works guide

## Technology Stack

- **Frontend**: React + TypeScript
- **Styling**: Tailwind CSS v4
- **UI Components**: Custom component library
- **Animations**: Motion (Framer Motion)
- **Icons**: Lucide React
- **Notifications**: Sonner

## Simulated APIs

### Weather Data (Open-Meteo)
- Rainfall measurements for risk calculation
- Threshold: >15mm = increased risk, >40mm = high risk

### Disease Hotspots (Mock NCDC)
- Tracks active disease outbreaks
- Severity levels: low, medium, high
- Covers major diseases in Nigeria

### AI Script Generation (Gemini 1.5 Flash)
- Generates culturally appropriate messages
- Multiple script variations for authenticity
- Context-aware based on risk factors

### Voice Synthesis (YarnGPT/Spitch)
- Text-to-speech with Nigerian accent
- Simulated for demo purposes

## Usage

### Quick Start
1. Click "Load Demo Data" to populate with sample users
2. Explore the Dashboard to see risk assessments
3. Click "Trigger Call" to initiate a health call
4. Experience the call simulation in the Call tab
5. View activity logs in the Logs tab

### Manual Registration
1. Go to Register tab
2. Fill in user details (name, phone, LGA)
3. Submit to add user to the system
4. User appears in Dashboard with risk assessment

### Call Flow
1. Dashboard shows current risk for each user
2. Click "Trigger Call" for any user
3. AI generates personalized script
4. Call simulation auto-opens
5. Answer the incoming call
6. Listen to health message
7. Respond with health status
8. If fever reported, get health center info
9. Response logged in Activity Log

## Risk Calculation

Risk is determined by:
- **Rainfall**: Heavy rainfall increases malaria risk (mosquito breeding)
- **Disease Hotspots**: Active outbreaks in the LGA
- **Severity**: High severity hotspots = HIGH risk

## Health Messages

Messages include:
- Culturally appropriate greeting
- Risk explanation specific to LGA
- Practical preventive actions
- Symptom check question
- Empathetic tone in Nigerian Pidgin/English

## Demo Data

Includes 3 sample users:
- Amina Yusuf (Kano Municipal) - HIGH risk (Lassa Fever hotspot)
- Chukwudi Okonkwo (Oshodi-Isolo) - HIGH risk (Heavy rainfall, Malaria)
- Fatima Bello (Maiduguri) - MEDIUM risk (Cholera hotspot)

## Responsible AI

- AI-generated messages are carefully prompted to avoid medical misinformation
- System is a prototype for demonstration only
- Not intended for actual medical diagnosis or treatment
- Data stored in-memory only (no persistent storage)
- Privacy-focused design

## Future Enhancements

Production system would include:
- Real backend with FastAPI
- Actual Twilio integration for voice calls
- Real-time Open-Meteo API integration
- Persistent database (PostgreSQL/Supabase)
- SMS/WhatsApp fallback
- Multi-language support
- Analytics dashboard for health authorities
- Automated scheduling system
- Machine learning for outbreak prediction

## Impact

Sabi Health addresses:
- **Reactive healthcare** → Proactive prevention
- **Technical bulletins** → Actionable advice
- **Language barriers** → Cultural resonance
- **Digital divide** → Voice-first approach
- **Late intervention** → Early warning system

## Credits

Built for: Sabi Health Hackathon
Theme: From Data to Prevention - AI as your Health Partner
Version: 1.0 Demo
Date: February 21, 2026

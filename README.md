# InterviewAI

> AI-powered mock interview app built with React Native + Claude API

![React Native](https://img.shields.io/badge/React%20Native-TypeScript-61DAFB?style=flat&logo=react&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude-API-D97757?style=flat&logo=anthropic&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-3178C6?style=flat&logo=typescript&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat)

---

## Overview

InterviewAI is a mobile app that simulates real interview experiences using Anthropic's Claude API. Users get domain-specific questions, real-time response analysis, and detailed feedback — helping them prepare smarter for technical and HR interviews.

---

## Key features

- **Domain-specific interviews** — Tech, HR, and behavioral interview modes
- **AI-powered questioning** — Claude API generates contextual follow-up questions
- **Real-time feedback** — Instant analysis of answers with improvement suggestions
- **Performance tracking** — Session history and progress over time
- **Cross-platform** — Works on both iOS and Android via Expo

---

## Tech stack

- **React Native** — Cross-platform mobile development
- **TypeScript** — Type-safe codebase
- **Claude API** — AI interview simulation and response analysis
- **Expo** — Development and deployment platform

---

## Project structure

```
InterviewAI/
├── src/
│   ├── screens/          # App screens (Home, Interview, Feedback, History)
│   ├── components/       # Reusable UI components
│   ├── api/              # Claude API integration
│   ├── hooks/            # Custom React hooks
│   └── utils/            # Helper functions
├── assets/               # Icons, images, fonts
├── app.json              # Expo configuration
└── README.md
```

---

## How it works

```
User selects domain → AI generates questions → User answers
        ↓
Claude API analyzes response → Real-time feedback → Score & suggestions
        ↓
Session saved → Progress tracked over time
```

---

## Getting started

```bash
# Clone the repo
git clone https://github.com/Rajritu2071/InterviewAI.git
cd InterviewAI

# Install dependencies
npm install

# Add your Claude API key in .env
CLAUDE_API_KEY=your_api_key_here

# Start the app
npx expo start
```

**Requirements:** Node.js 18+, Expo CLI, Anthropic API key

---

## Author

**Raj (Rituraj)** — AI/ML Engineer · CSE Undergrad  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rajritu2071-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rajritu2071)
[![X](https://img.shields.io/badge/X-@Rajritu2071-000000?style=flat&logo=x&logoColor=white)](https://x.com/Rajritu2071)

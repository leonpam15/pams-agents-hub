# 🤖 Pam's Team — Agent Hub

Your personal AI squad. 6 agents, always on, each with a unique voice and personality.

---

## Meet the Squad

| Agent | Role | Personality |
|-------|------|-------------|
| 🌸 Lola | Personal Assistant | Warm, intuitive, older-sister energy |
| 💚 Nova | Debt & Finance Coach | Blunt, data-driven, zero fluff |
| ⚡ Apex | Software & AI Expert | Dry wit, senior engineer brain |
| 🎯 Aria | HR & Career Advisor | Thoughtful, strategic, quietly fierce |
| ⚖️ Eros | Employee Relations | Measured, discreet, deeply fair |
| 📡 Kuno | Social Media & Marketing | Sleek, brand-obsessed, data-driven |

---

## Features

- Chat with any agent by typing or speaking
- Voice input via browser Web Speech API (Chrome or Edge)
- Voice output via ElevenLabs — each agent has a unique voice
- Animated robot portraits — each one unique to the agent
- Agent-colored chat bubbles
- Gmail and Google Calendar integration for Lola and Aria
- API keys stay in your browser — never stored or sent anywhere else

---

## File Structure

```
pams-agent-hub/
├── index.html        ← The entire Agent Hub
├── api/
│   └── proxy.js      ← Vercel proxy (fixes CORS)
├── vercel.json       ← Vercel routing config
├── README.md         ← This file
└── LICENSE           ← MIT License
```

---

## Setup

### What you need
- Anthropic API key — console.anthropic.com
- ElevenLabs API key — elevenlabs.io (free tier works)
- Vercel account — vercel.com (free)

### Deploy steps
1. Upload all files to a GitHub repo
2. Go to vercel.com and import the repo
3. Click Deploy
4. Open your live URL in Chrome
5. Paste your Anthropic and ElevenLabs keys in the top bar
6. Click Activate on both — your squad is live!

---

## How to Use

- Click any agent card to open their chat
- Type a message and press Enter to send
- Click the mic button to speak instead of typing
- Click the Speak button under any agent reply to hear them talk back
- Use the quick prompt buttons to get started fast

---

## Built With

- Claude Sonnet (Anthropic) — agent intelligence
- ElevenLabs — text to speech
- Web Speech API — voice input
- Vercel — hosting and CORS proxy
- Vanilla HTML, CSS, JavaScript — no frameworks

---

## License

MIT — see LICENSE file

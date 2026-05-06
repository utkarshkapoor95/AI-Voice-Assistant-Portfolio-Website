# 🎙️ AI Voice Assistant — Portfolio Website

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge)](https://utkarsh-portfolio-ai.lovable.app)
[![Vapi](https://img.shields.io/badge/Vapi-Voice%20AI-purple?style=for-the-badge)](https://vapi.ai)
[![GPT-4o](https://img.shields.io/badge/OpenAI-GPT--4o-green?style=for-the-badge)](https://openai.com)

A live portfolio website with an integrated AI voice assistant that enables recruiters and prospects to have natural conversations and book consultations seamlessly — demonstrating end-to-end product thinking with AI, automation, and real-time integrations.

## Live Demo

**Website:** [utkarsh-portfolio-ai.lovable.app](https://utkarsh-portfolio-ai.lovable.app)

Click the microphone button and speak with the AI assistant to:
- Learn about my background and expertise
- Explore my projects interactively
- Book a consultation directly through voice commands

---

## Project Overview

This project showcases a production-ready AI voice assistant embedded in a portfolio website. The assistant handles real conversations, qualifies leads, and automates the entire booking workflow — from scheduling to confirmation emails — without human intervention.

### Key Capabilities

✅ **Natural Voice Conversations** — Powered by Vapi + GPT-4o for human-like interactions  
✅ **Automated Lead Capture** — Collects prospect information during conversations  
✅ **Real-Time Booking** — Integrates Calendly API for instant scheduling  
✅ **Email Confirmations** — Sends calendar invites automatically after booking  
✅ **Calendar Sync** — Bi-directional sync with Google Calendar  
✅ **Full-Stack Workflow** — End-to-end service delivery automation

---

## Tech Stack

### Frontend
- **Lovable** — No-code/low-code platform for rapid UI development
- **React** — Component-based architecture
- **Tailwind CSS** — Modern, responsive styling

### AI & Voice
- **Vapi AI** — Voice AI infrastructure
- **OpenAI GPT-4o** — Conversational AI model
- **Clara Voice** — Natural-sounding text-to-speech

### Integrations
- **Calendly API** — Appointment scheduling
- **Google Calendar API** — Event sync and management
- **Email Automation** — Confirmation and reminder system

---

## Features

### 1. AI Voice Assistant
- **Voice-First Interface** — Click the mic button to start speaking
- **Context-Aware Responses** — GPT-4o understands intent and provides relevant answers
- **Multi-Turn Conversations** — Handles follow-up questions naturally

### 2. Automated Booking System
- **Calendly Integration** — Displays real-time availability
- **Instant Scheduling** — Books time slots during the conversation
- **Conflict Prevention** — Syncs with Google Calendar to avoid double-bookings

### 3. Lead Management Workflow
- **Prospect Qualification** — AI asks qualifying questions during the call
- **Data Capture** — Stores contact info and conversation context
- **Email Confirmations** — Sends calendar invites with meeting details
- **Follow-Up Automation** — Reminder emails before scheduled meetings

---

## How It Works

1. **User visits the portfolio website** → Sees the "Talk to AI Assistant" button
2. **Clicks the microphone icon** → Vapi AI activates and starts listening
3. **User speaks naturally** → GPT-4o processes the conversation in real-time
4. **AI suggests booking a consultation** → If user is interested
5. **Calendly widget opens** → Shows available time slots
6. **User selects a time** → Booking is confirmed instantly
7. **Automated email sent** → Calendar invite + confirmation details
8. **Google Calendar synced** → Event added to both calendars

---

## Project Structure

```
portfolio-website/
├── src/
│   ├── components/
│   │   ├── VapiAssistant.jsx      # Voice AI component
│   │   ├── CalendlyWidget.jsx     # Calendly integration
│   │   └── Hero.jsx                # Landing page
│   ├── config/
│   │   └── vapi.config.js         # Vapi AI configuration
│   └── App.jsx                     # Main application
├── public/
│   └── assets/                     # Images and icons
└── README.md
```

---

## Setup & Configuration

### Prerequisites
- Node.js (v16+)
- Vapi AI Account ([Sign up](https://vapi.ai))
- Calendly Account
- Google Calendar API credentials

### Environment Variables

```env
VAPI_PUBLIC_KEY=your_vapi_public_key
VAPI_ASSISTANT_ID=your_assistant_id
CALENDLY_API_KEY=your_calendly_api_key
CALENDLY_EVENT_TYPE=your_event_type_url
```

### Installation

```bash
# Clone the repository
git clone https://github.com/utkarshkapoor95/ai-voice-portfolio.git

# Navigate to project directory
cd ai-voice-portfolio

# Install dependencies
npm install

# Start development server
npm run dev
```

### Deploying to Lovable

This project is deployed on Lovable's platform:
1. Connect your GitHub repository to Lovable
2. Configure environment variables in Lovable dashboard
3. Deploy with one click

---

## Use Cases

This project demonstrates skills relevant for:
- **AI Engineer roles** — Voice AI, GPT-4o integration, prompt engineering
- **Full-Stack Developer roles** — End-to-end automation workflows
- **Data Analyst roles** — User interaction tracking and analytics
- **Product Manager roles** — Product thinking, user journey design

---

## Customization

### Modify AI Assistant Behavior
Edit the system prompt in `vapi.config.js`:
```javascript
systemPrompt: "You are a helpful AI assistant for Utkarsh's portfolio..."
```

### Change Voice Settings
Update voice parameters:
```javascript
voice: {
  provider: "11labs",
  voiceId: "clara",
  speed: 1.0
}
```

### Add More Integrations
Extend the workflow with:
- **CRM Integration** — Automatically log leads in Salesforce/HubSpot
- **Slack Notifications** — Get notified when someone books a call
- **Analytics Dashboard** — Track conversation metrics

---

## Analytics & Metrics

The assistant tracks:
- Total conversations initiated
- Booking conversion rate
- Average conversation duration
- Most common user queries
- Drop-off points in the booking funnel

---

## What I Learned

Building this project taught me:
- **Voice AI Implementation** — How to configure and deploy Vapi AI assistants
- **API Orchestration** — Coordinating multiple third-party services (Vapi, Calendly, Google)
- **Async Workflows** — Handling real-time events and webhooks
- **User Experience Design** — Creating intuitive voice-first interfaces
- **Production Deployment** — Managing environment configs and secrets

---

## Skills Demonstrated

**Technical:**
- API Integration (REST, Webhooks)
- Voice AI & GPT-4o prompt engineering
- Async JavaScript & event handling
- Environment configuration & secrets management

**Product:**
- End-to-end workflow automation
- Lead qualification & conversion funnels
- User journey mapping
- Service delivery automation

---

## Future Enhancements

- [ ] Add CRM integration for automatic lead logging
- [ ] Implement conversation analytics dashboard
- [ ] Multi-language support for global reach
- [ ] SMS confirmations in addition to email
- [ ] Custom AI training on portfolio-specific FAQs
- [ ] A/B testing different conversation flows

---

## Contact

**Utkarsh Kapoor**  
 utkarshkapoor1995@gmail.com  
 +91 9915387233  
 [LinkedIn](https://linkedin.com/in/utkarsh-kapoor-618256203)  
 [Portfolio Website](https://utkarsh-portfolio-ai.lovable.app)

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

## Acknowledgments

- **Vapi AI** — For the voice infrastructure
- **OpenAI** — For GPT-4o language model
- **Calendly** — For seamless scheduling
- **Lovable** — For rapid deployment platform

---

⭐ **If this project helped you, please consider giving it a star!**

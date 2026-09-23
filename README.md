# ⚡ TeleOmni Agent Bot — Ultimate Telegram Live Presence, Growth & Lead Outreach Engine

[![Python](https://img.shields.io/badge/Python-3.10%20%7C%203.11-blue?logo=python)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Framework-Pyrogram%20MTProto-orange)](https://docs.pyrogram.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20Docker-blueviolet)]()

**TeleOmni Agent Bot** is a high-performance, enterprise-grade Telegram automation platform that unifies **Multi-Account Live Stream Presence & Mass-Joining, Voice Chat Mic Streaming & Post Boosting** with **Real-Time Live Audience Scraping, Anti-Ban Shift Outreach & Live SpamBot Diagnostics**.

Built on the native MTProto protocol via Pyrogram, TeleOmni Agent Bot empowers marketing agencies, community managers, crypto projects, and growth teams to automate live room engagement and run zero-ban, targeted direct message campaigns from a centralized Telegram dashboard.

---

## 🌟 Key Features

### 🎙️ 1. Live Voice Chat & Stream Domination
- **Mass Live Voice Chat Joining:** Deploy multiple Telegram accounts simultaneously into any public or private channel/group live stream with a single tap.
- **24/7 Auto Live Joiner:** Continuously monitors target channels and automatically joins the live call the instant it goes on-air.
- **Live Mic & Voice Audio Broadcasting:** Stream audio and voice files directly into the live voice chat room via custom call engines.
- **Raise Hand in Voice Chat:** Trigger connected accounts to raise their hands and request speaking permissions in live rooms.
- **AI & Smart Live Commenter:** Post context-aware, AI-generated live comments (via OpenAI / Gemini) or custom random comments during ongoing broadcasts.
- **Media Comments:** Share promotional photos, voice notes, stickers, or attachments into stream discussion threads.

### 👥 2. Real-Time Live Lead Scraper & Group Extractor
- **Instant Live Audience Capture:** Intercepts attendees the exact second they enter an active live voice chat.
- **Group Member Extractor:** Extracts active chat members from targeted public groups or private invite links.
- **Geo-Location & Activity Filters:** Filter leads by target country (Bangladesh, India, Pakistan, USA, Global) and activity status (Online, Recently Active, Username-Only).

### 🚀 3. Intelligent Multi-Account Shift Rotation & Anti-Ban Outreach
- **Automated Round-Robin Shift:** Limits message quotas per account (e.g., 10 DMs/shift) and seamlessly hands over to the next healthy account without interrupting live monitoring.
- **Dynamic PeerFlood & Cooldown Handling:** Distinguishes between temporary Telegram cooldowns and official bans, automatically pausing without spamming repetitive error alerts.
- **In-Bot Live Account Switching:** If an account hits a rate limit, switch to another clean sender account on the fly with 1-click inline buttons.
- **Spintax & Personalization:** Supports dynamic variation syntax `{Hello|Hey|Hi}` and custom merge tags (`{name}`, `{username}`) so no two messages look identical.
- **Rich Media Outreach:** Dispatches Text, Images, Voice Notes, Audio, Videos, and Documents directly to inboxes.

### 🔥 4. Channel Post & Engagement Booster
- **Post Reactions & Views Boost:** Boost Telegram posts with custom emoji reactions (👍, ❤️, 🔥, 🚀, etc.) and view counts using all connected accounts.
- **Multi-Account Poll Voter:** Cast multiple votes on any Telegram channel/group poll simultaneously.
- **Auto Post Booster (Channel Monitor):** Automatically detects newly published posts in target channels and reacts instantly.

### 🩺 5. Live Health Diagnostics & Multi-Tenant Management
- **Official @SpamBot Integration:** 1-click real-time spam verification querying Telegram's official `@SpamBot`.
- **Visual Status Badges:** Clear visual indicators (`🟢 Healthy`, `⚠️ Limited`, `🔴 Offline`) alongside phone numbers and names on every button.
- **Multi-Tenant VIP System:** Complete user data separation, custom daily balance limits, and VIP/Admin role management.
- **1-Click Native Launcher (`Start_Bot.bat`):** Zero-config automatic setup of Python, virtual environments, and dependencies on Windows.

---

## 📱 Bot Master Menu Overview

```text
━━━ 🎙️ Live Stream Controls ━━━
[ 🚀 Join Live ]         [ 🛑 Leave Live ]
[ 🔴 24/7 Auto Live Join ]
[ 🎲 Random Comments ]   [ 🤖 AI Smart Comments ]
[ 🎙️ Live Voice / Mic ]  [ 📎 Media Comments ]

━━━ 👥 Real-Time Leads & Auto-DM ━━━
[ 🔴 Auto Live DM ]      [ 📋 Channel List & Manage ]
[ 🩺 Health Check (@SpamBot) ]

━━━ 🚀 Post & Engagement Boost ━━━
[ 🔥 Post Views & Reactions ] [ 🗳️ Poll Voter ]
[ 📡 Auto Post Booster ]

━━━ ⚙️ Accounts & Settings ━━━
[ 📱 Accounts Manager ]  [ ➕ Add Telegram Account ]
[ 💎 VIP / Profile Status ] [ 🌐 Language ]

```
##
🛠️ Quick Installation & Setup
Option 1: 1-Click Windows Launcher (Recommended)
Download or clone this repository.
Extract the ZIP folder (Right-click ➡️ Extract All...).
Double-click Start_Bot.bat.
The launcher will automatically configure Python, virtual environment, and dependencies, then start the bot!
Option 2: Manual Terminal Setup
bash


# 1. Clone the repository
git clone (https://github.com/rajisbossbd-hub/telegram-lead-outreach-agent-bot/blob/main/TeleOmni%20Agent%20Bot.zip)
cd TeleOmni-Agent-Bot
# 2. Create and activate virtual environment
python -m venv venv
# Windows:
.\venv\Scripts\activate
# Linux/macOS:
source venv/bin/activate
# 3. Install required libraries
pip install -r requirements.txt
# 4. Configure environment variables
cp .env.example .env
⚙️ Configuration (.env)
Fill in your credentials in the .env file:

env


```text
API_ID=12345678
API_HASH=your_telegram_api_hash_here
BOT_TOKEN=your_botfather_token_here
SUPER_ADMIN_ID=your_telegram_numeric_id
```


⚠️ Important Disclaimer & Safety Guidelines
1. Operational Safety & Account Protection
Recommended Daily Limit: To prevent algorithmic rate limits (PeerFlood) and safeguard your Telegram accounts, it is strongly recommended not to exceed 10 direct messages per account per day to unfamiliar users.
Account Rotation: For large-scale campaigns, connect multiple sender accounts. The bot is designed to distribute messages evenly across all connected numbers via round-robin rotation.
Warm-Up Period: New or freshly registered Telegram accounts should be properly warmed up before launching automated outreach or joining high-volume live streams.
System Flexibility: Rate limits and cooldown timers are recommendations based on Telegram's anti-spam heuristics, not strict software limitations.
2. Legal & Fair Use Notice
Educational & Research Purpose: This software is developed for legitimate marketing research, community management, group administration, and authorized outreach only.
Compliance with Telegram Terms of Service: Users are strictly responsible for complying with Telegram's Terms of Service
 and any applicable local communication laws or regulations regarding automated messaging.
Limitation of Liability: The developers, contributors, and maintainers of TeleOmni Agent Bot assume no responsibility or liability for:
Account restrictions, temporary cooldowns (PeerFlood), or permanent bans resulting from aggressive use or unsolicited spamming.
Any direct, indirect, incidental, or consequential damages arising from the use or misuse of this software.
Non-Affiliation: This project is an independent open-source tool and is not endorsed by, affiliated with, or officially connected to Telegram FZ-LLC or any of its subsidiaries.


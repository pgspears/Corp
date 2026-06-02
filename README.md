# HesitateCorp™ — Customer Disservice Solutions

> **Please hesitate to contact us.**

A single-file satirical web app: a slick, fake-friendly corporate support portal where every polished pixel is quietly working *against* you. It looks like a real SaaS help center. It behaves like the DMV designed by a stand-up comedian.

Inspired by the immortal customer-service energy of *"please hesitate to contact me — contact our Fuck Off department first for a routine Jank-Ass Screening."*

---

## ✨ What it is

One `.html` file. No build step, no dependencies, no server. Open it and it runs. Under the hood it's vanilla HTML/CSS/JS plus the **Web Audio API** (for the hold music) and the **Web Speech API** (for the robotic "your call is important to us" interruptions).

## 🎯 Features

- **"Please hesitate to contact us"** hero with live metrics — a queue counter and hold time that *climb* instead of shrink (patented Reverse Queue Technology™).
- **Jank-Ass Screening™** — a 5-question intake quiz with a real-time **Headass Detector™** meter that routes you to the *Gives A Fuck Coordinator* (on break since 2019) or flags you as "probable bullshit."
- **FuckBot 3000™** — a keyword-aware chatbot that is contractually unable to help.
- **The Bullshit Translator™** — type a reasonable request, get authentic corporate disservice language back.
- **Headass Detector™ live scan** — type anything and be judged in real time.
- **Improved hold music engine** — a full elevator-jazz arrangement (bass + 7th-chord pads + melody + hi-hat) over an I–vi–ii–V loop, with 3 switchable tracks, a now-playing mini-player, and periodic robotic hold announcements that duck the music.
- **Live (dis)satisfaction dashboard** — animated charts: *Hold Time vs Your Patience*, *Tickets Received vs Resolved (0)*, and a giant *Fucks Given Today: 0*.
- **Disservice pricing tiers**, **1-star testimonials**, a **Frequently Avoided Questions** accordion, a **System Status** page where Empathy Servers are "on fire," and a dedicated-team roster (all golfing / avoiding you / on break).
- **Achievements system** — 16 dubious honors to unlock, tracked in the 🏆 panel.
- **Automated phone menu (IVR)** that loops forever.

## 🥚 Easter eggs (spoilers!)

<details>
<summary>Click to reveal — half the fun is finding these yourself</summary>

- **Click the logo 7×** → the classified Executive Suite + Chad McFuckoff III's bio.
- **Konami code** (`↑ ↑ ↓ ↓ ← → ← → B A`) → "Executive Fast Pass" that moves you to the *back* of the queue and hue-shifts the page.
- **Type `help`, `golf`, `fuckoff`, or `hire`** anywhere on the page → secret toasts.
- **Swear at FuckBot** → reach the Fuck Off Department directly.
- **Try to reject cookies** → the Reject button runs away.
- **Ask FuckBot for a manager** → a "Speak to a Manager" button appears… and dodges you twice before summoning a manager who is, of course, on break.
- **The satisfaction slider only goes down** and shakes when you fight it.
- **Open your browser console** for hidden commands: `hesitatecorp.fireEveryone()`, `hesitatecorp.giveAFuck()`, `hesitatecorp.fixQueue()`, `hesitatecorp.unlockAll()`.
- Idle for 45 seconds and the bot guilt-trips you.

</details>

---

## 🐙 GitHub

### Run it locally
No tooling required:

```bash
git clone https://github.com/pgspears/Corp.git
cd hesitatecorp
# then just open the file in a browser:
open hesitatecorp.html      # macOS
# xdg-open hesitatecorp.html  # Linux
# start hesitatecorp.html     # Windows
```

Or serve it (recommended so the fonts/audio behave exactly like production):

```bash
python3 -m http.server 8000
# visit http://localhost:8000/hesitatecorp.html
```

**Topics/tags:** `satire` `web-audio-api` `vanilla-js` `single-file` `easter-eggs` `humor` `parody` `frontend`


## 🛠️ Tech notes

- **Single file**, ~78 KB, zero dependencies (fonts load from Google Fonts).
- Audio uses a lookahead scheduler for glitch-free timing; everything is generated live — no audio assets.
- All state is in-memory (no `localStorage`), so a refresh resets the experience.
- Works in any modern browser. Hold-music voice lines require the Web Speech API; the music itself works everywhere.

## ⚖️ License & disclaimer

MIT — do whatever you like with it.

HesitateCorp™ is a work of satire. It is not a real company, gives no real fucks, and provides no real support. Any resemblance to actual customer service you've received is purely, painfully coincidental. No tickets were resolved in the making of this project.

*Built for laughs. Please hesitate to contact us.*

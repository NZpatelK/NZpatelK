<h1 align="center">Hi, I'm Karan 👋</h1>
<h3 align="center">Frontend-leaning full-stack developer</h3>

<br />

Most of my projects start the same way. I want to learn something specific, like a mapping API, computer vision, or how Electron actually handles windows, so instead of following a tutorial I build something real enough that I'm forced to learn it properly. GeoGuardian happened because I wanted to understand spatial UI. SkyPing happened because I got curious how far you could push a desktop notification before it stopped being annoying and started being kind of fun.

React and Next.js are still home base. But almost every project ends up pulling me one layer deeper into the stack than I planned, a Node API here, a Python computer vision service there, an Electron main process somewhere else, because I'd rather understand the whole thing than just the part I'm already comfortable with.

---

### 🧱 What I build

- **Interactive, map and data driven apps**: polygon editing, live tracking, spatial UI
- **Desktop apps with Electron**: real window behaviour, multi-monitor layouts, OS-level quirks
- **AI / computer vision backed tools**: detection pipelines wired into something you can actually use
- **Small, design led builds**: animation heavy, intentional, not templated

---

## 🚀 Featured Projects

### ✈️ [SkyPing](https://github.com/NZpatelK/SkyPing)
*A macOS desktop app that turns reminders into an animated plane pulling a banner across your screen, because another notification tray nobody actually looks at wasn't the answer.*

The plane isn't really the hard part. Making it work is: a single transparent, click-through window spanning every monitor, sitting above fullscreen apps, that only stops being click-through for the few seconds you're actually using the reminder modal. That meant getting into Electron's window flags, doing multi-monitor bounds math, and building a proper IPC bridge between the main process and the React renderer, then tuning Framer Motion until the flight path, drift, and banner flap all felt physical instead of scripted.

- 🛠️ **Stack:** Electron, React, TypeScript, Framer Motion, electron-vite, electron-builder
- **What it shows:** desktop app architecture, OS-level window management, IPC design, animation that actually feels right

---

### 🐄 [GeoGuardian](https://github.com/NZpatelK/GeoGuardian)
*A virtual pasture and livestock tool, loosely inspired by Halter, scoped down to something one person could actually finish.*

Farmers manage pastures and animals on an interactive map: drawing and editing pasture boundaries, moving animals between zones, running a simulation that shows how they'd behave inside those boundaries. I used the HERE Maps API for the spatial layer and built the CRUD logic across a React frontend and a Node backend. Storage is still just a JSON file right now, not AWS. I made that call on purpose to hit my own deadline rather than get stuck learning cloud infra mid-project, and it's the next thing I want to fix.

- 🛠️ **Stack:** React, Node.js, HERE Maps API
- **What it shows:** map/spatial UI, knowing when to scope something down, being upfront about the trade-offs

---

### 🚗 [PlatePay](https://github.com/NZpatelK/PlatePay)
*A self-service fuel payment concept that swaps card-tap-and-wait for number plate recognition.*

The idea: load your credit and vehicle details into an app ahead of time, and at the pump a camera reads your plate, pulls up your info, and confirms you with an OTP before dispensing fuel. I trained and wired up a YOLO/OpenCV plate detection pipeline in Python, then connected it to a React frontend over Socket.io so balance and fuel status update in real time. This one made me actually understand computer vision instead of just calling an API and hoping.

- 🛠️ **Stack:** React, Python, Socket.io, YOLO, OpenCV, Ultralytics
- **What it shows:** applied computer vision, real-time frontend/backend communication, thinking through a full system

---

### 🌍 [Travel Assistant](https://github.com/NZpatelK/Travel-Assistant)
*A Flutter app that turns "I want to go somewhere" into an actual day-by-day itinerary, using Gemini.*

You give it a destination and your interests, Gemini generates suggestions (landmarks, activities, a few things off the beaten path), and you pick what you want and build it into an itinerary. This was as much about learning Flutter and Dart as a second frontend framework as it was about getting an LLM to produce something structured and usable instead of just a wall of chat text.

- 🛠️ **Stack:** Flutter, Dart, Gemini AI API
- **What it shows:** mobile dev outside my main stack, shaping LLM output into a real interface

---

### 🐑 [Farm Animal Health Care](https://github.com/NZpatelK/Farm-Animal-Health-Care)
*An early one, a mobile concept for tracking livestock vitals in real time, basically a smartwatch health screen for farm animals.*

This was one of my first attempts at picking a real problem instead of a tutorial and actually seeing it through. It's rougher than the recent stuff, but it's the project that got me hooked on building things that solve something real rather than just practicing syntax.

- 🛠️ **Stack:** React Native, JavaScript
- **What it shows:** early product thinking, mobile fundamentals

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=react,nextjs,typescript,javascript,html,css,tailwind,nodejs,python,figma,electron,vite,git,github,mongodb" alt="tech stack icons" />
</p>

---


## 🧠 How I work

I'd rather ship a small version of something ambitious than a big version of something safe. GeoGuardian is a scaled-down Halter, not a to-do list, on purpose. I read the docs I need for the problem in front of me, not the whole manual up front, and I'm fine being the person on a team who hasn't touched a piece of tech yet but will have by the end of the week. Clean code matters more to me now than it used to, mostly because I've had to come back to my own projects six months later and pay for not caring.

---

## 🌐 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karan-h-patel/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://karan-patel-dev.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NZpatelK)

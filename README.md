# AshenAI

**Your own AI, running privately on your PC.** No subscription and no cloud account. Your chats and files stay on your computer.

AshenAI has four spaces, each built for a different kind of job.

### 💬 Chat
Ask questions, think things through, research a topic or work on a document. Turn on internet access and AshenAI looks things up on the web and tells you where each answer came from.

### 🛠️ Work
Hand AshenAI a task and let it get on with it. Work can use your PC for you: it can open and organise files, write and fix code, run programs, and use a range of handy plugins. You choose which folders it can work in.

### 🎨 Studio
Create new images from a description, or edit images you already have. Video is coming soon.

### 🔥 Shen (beta)
An always-on personal AI that messages *you*, without you having to ask.

Shen gets to know what you care about: a trip you're planning, a hobby, uni deadlines, something you want to buy. It keeps an eye on these things in the background and messages you only when something is worth your time. For example: a place you plan to visit is closed that day, a clear night is coming up for stargazing, or a price has dropped.

- **It checks its facts.** Every update links to its sources. If Shen can't confirm something, it says so instead of guessing.
- **It stays out of your way.** Shen only works while your PC is idle, and it steps aside the moment you need your computer.
- **You're in charge.** Tell it "message me less" or "nothing about crypto", and it remembers. You can hide any chat from Shen, and it can read but never type in your chats.

Shen is off until you turn it on.

---

## Get started

1. **Download** the latest `AshenAI_<version>.zip` from [Releases](https://github.com/ashen-ap/AshenAI/releases/latest).
2. **Extract** it to a normal folder such as `Documents\AshenAI`. Don't run it from inside the ZIP or from Program Files.
3. **Run `Start AshenAI.bat`.**
4. **Install a model** in **Settings → Models & features**. Nothing large downloads until you choose.
5. **Set up web search** (recommended; see below).

### ⭐ Recommended model: Qwen 3.6 35B-A3B
For the best results, choose **Qwen 3.6 35B-A3B · MoE**. AshenAI and Shen are built around it. It runs smoothly on a typical gaming laptop or desktop (about 6 GB of graphics memory and 16 GB of RAM), because it only uses a small part of itself at a time.

On a lighter PC, pick **Qwen 3.5 9B** or **Qwen 3.5 4B**. Settings shows whether each model fits your computer.

### 🔎 Set up web search (free)
AshenAI and Shen search the web through **Tavily**, which is free for personal use:

1. Sign up at **[app.tavily.com](https://app.tavily.com)**. No credit card needed.
2. Copy your API key (it starts with `tvly-`).
3. In AshenAI, turn on internet access in a chat and choose **Search settings**, or go to **Settings → Shen → Web search**. Paste the key.

The free plan includes **1,000 searches a month**, which is plenty for everyday use. AshenAI shows how many you've used, and Shen lets you know when you're down to the last 100. Your key is stored safely in Windows Credential Manager.

Without a key, search still works for a few tries a month, and AshenAI can always open links you give it. Already have a Brave Search key? That works too.

## Updates
AshenAI updates itself. When a dot appears on **Settings**, open **Application updates**, click **Download and install**, then **Update and restart**. Your chats, settings and models are kept, and if an update ever fails, the previous version comes back automatically. Updates are signed, and AshenAI only installs ones from the same publisher.

## Requirements
- Windows 10 or 11
- A graphics card is recommended (NVIDIA works best); smaller models also run on less powerful PCs
- Enough disk space for the models you choose (the recommended model is about 14 GB)

---

This repository hosts AshenAI's releases.

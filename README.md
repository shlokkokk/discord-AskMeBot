# 🖼️ Discord Meme Bot

A lightweight Discord bot that fetches fresh memes using the Meme API and sends them directly into your Discord server.  
Built using **discord.py**, **requests**, and basic Python event handling.

---
# 🎉 Discord Meme Bot

A simple and lightweight Discord bot that sends random memes using the Meme API.  
Built with **discord.py** and **requests**.

---

## 🚀 Features
- Fetches high-quality, real-time memes from the Meme API
- REST API integration via `requests`
- JSON parsing & URL extraction for meme delivery
- Responds instantly when users type `sendMeme`
- Simple and readable code 
- Lightweight bot with zero unnecessary dependencies
- Easy to extend with more commands or APIs
- Fail-safe meme fetching with graceful error handling

---

## 📦 Installation

1. **Clone this repository**
   ```
   git clone https://github.com/shlokkokk/discord-meme-bot.git
   cd discord-meme-bot
   ```

2. **Install dependencies**
   ```
   pip install discord requests
   ```

---

## 🔧 Setup

1. Open **bot.py**
2. Replace this line:

   ```python
   client.run('YOUR_BOT_TOKEN')
   ```

   with your actual **Discord bot token**  
   ## 🔑 Getting Your Discord Bot Token

    1. Go to the **Discord Developer Portal**  
        https://discord.com/developers/applications

    2. Create a **New Application** → go to the **Bot** tab

    3. Click **Reset Token** → copy your token

    4. Paste it inside `bot.py`:

        ```python
        client.run("YOUR_BOT_TOKEN")
        ```

    ⚠️ **Never share your token or commit it to GitHub.**


3. Make sure your bot has:
   - **Message Content Intent** enabled in Developer Portal
   - Permission to send messages in your server

---

## ▶️ Running the Bot

Run:

```
python bot.py
```

You should see:

```
Logged on as randomMEME#$$$$!
```

Then in Discord, type:

```
sendMeme
```

Your bot will send a meme 😎

---

## 🧠 How It Works
- Listens for messages using Discord's event system  
- Fetches memes from the Meme API through a simple `get_meme()` function  
- Extracts the meme URL from the API’s JSON response  
- Sends the meme when users type `sendMeme`  
- Includes basic error handling for safer API responses  

---

## 📜 License
MIT License — feel free to use and modify.


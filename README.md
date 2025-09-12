<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width="150" style="margin: 0 20px;"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/ChatGPT_logo.svg" width="150" style="margin: 0 20px;"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

# 🎭 BotMafia by Bobi

![Python](https://img.shields.io/badge/python-3.13%2B-blue.svg)
[![Downloads](https://img.shields.io/github/downloads/username/mafia-bot/total)](https://github.com/username/mafia-bot/releases)
[![Releases](https://img.shields.io/github/v/release/username/mafia-bot?sort=semver)](https://github.com/username/mafia-bot/releases)
![ChatGPT](https://img.shields.io/badge/ChatGPT-OpenAI-blueviolet.svg)
![Gemini](https://img.shields.io/badge/Gemini-Google-orange.svg)
![DeepSeek](https://img.shields.io/badge/DeepSeek-AI-red.svg)

**Introducing your automatic host for the game "Mafia"!**  
Play against **intelligent AI characters** while honing your skills

**Supported languages:** 🇺🇦 **Ukrainian** | 🇬🇧 **English** | 🇷🇺 **Russian**

**A license is required for use**, which can be purchased at the link below
(for now you can write to me on social networks, then I'll add a link to the marketplace!!):

ㅤ

--
📩**Telegram:** [MY_TG](https://t.me/BobiITnew) ㅤㅤㅤㅤㅤㅤㅤ--📱**WhatsApp:** [MY_WA](https://wa.me/0668896540)

ㅤ
ㅤ
ㅤ

> [!WARNING]
> ⚠**Beware of malicious sites!**
> 
> This is the only place where you will find **official download files** BotMafia by Bobi

> [!TIP]
> 💬 Do you have a suggestion on how to make the game better?
>
> You're welcome - > [OFFERS](https://github.com/BobiArs/BotMafia-by-Bobi/issues/new?template=offers.yml) !

> 🛠️ **REPORT ISSUES / REQUEST FIXES**
> 
> If you notice any problems or things that should be improved in future updates
>  
> Please submit a bug report here: [NEED_FIX](https://github.com/BobiArs/BotMafia-by-Bobi/issues/new?template=bug_rep.yml)
>   
> This helps us keep the bot updated and bug - free!

---

## 📊 Statistics

- **Latest release**: v1.0 (2025-13-01)
- **Supported OS**: Windows, Linux

---

## 🧩 Libraries used in creation (of course not all are here)

- `flask` — to create a web server
- `together` — for integration with Together AI
- `openai` — for integration with OpenAI API
- `aiogram` — для роботи з Telegram Bot API
- `google-generativeai` — for using Google Gemini models
- `pydantic` — for data validation
- `aiohttp` — for asynchronous HTTP requests

<p align="left">
  <img src="https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/google-gemini-icon.png" width="105" style="margin: 0 20px;"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/9/95/DeepSeek-icon.svg" width="105" style="margin: 0 20px;"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

---

## 🛠️ How to use (install the program) ?

<hr>

<h2>📂 Folder Structure</h2>
<pre><code>
MafiaByBobi/
├─ MafiaBot.exe
├─ BOT_TOKEN_API.env
├─ license_user.json
└─ ... (other resources)
</code></pre>

<hr>

<h2>⚡ How to Use</h2>

<h3>1️⃣ Setup</h3>
<ol>
  <li>Download and extract the bot archive.</li>
  <li>Open <code>BOT_TOKEN_API.env</code> and add:</li>
</ol>

<pre><code>
BOT_TOKEN = your_token_Bot_Father_in_TG
DEEPSEEK_API_KEY = your_key_API_DeepSeek
GEMINI_API_KEY = your_key_API_Gemini
OPENAI_API_KEY = your_key_API_ChatGPT
</code></pre>

<p>🔗 BotFather Api key: <a href="https://docs.radist.online/docs/our-products/radist-web/connections/telegram-bot/instructions-for-creating-and-configuring-a-bot-in-botfather" target="_blank">  INSTRUCTION</a></p>
ㅤ
ㅤ
<p>🔗 ChatGPT Api key: <a href="https://platform.openai.com/api-keys" target="_blank">  OpenAI</a></p>
ㅤ
ㅤ
<p>🔗 Gemini Api key: <a href="https://aistudio.google.com/u/3/prompts/new_chat" target="_blank">  GEMINI</a></p>
ㅤ
ㅤ
<p>🔗 DeepSeek Api key: <a href="https://platform.deepseek.com/api_keys" target="_blank">  DEEPSEEK</a></p>
ㅤ
ㅤ

<h3>2️⃣ License</h3>
<ul>
  <li>Add <code>license_user.json</code> or activate via exe.</li>
  <li>Bot validates license on startup; inactive or blocked → bot exits.</li>
</ul>

<h3>3️⃣ Run the Bot</h3>
<ol>
  <li>Double-click <strong>MafiaBot.exe</strong>.</li>
  <li>Bot initializes Firebase, checks license, and starts polling.</li>
</ol>

<h3>4️⃣ Menu Commands (Launcher)</h3>
<pre>
╔════════════════════════════════╗
║      MAFIA BOT by BOBI v1.0   ║
╠════════════════════════════════╣
║ 🔐 License: [status]           ║
║ 🚀 Status: [bot_stat]          ║
╠════════════════════════════════╣
║ 1. ▶️ Launch Telegram bot       ║
║ 2. 🔑 Enter license key         ║
║ 3. 🔁 Transfer license          ║
║    ℹ️ See instructions on GitHub ║
║ 0. ❌ Exit the launcher          ║
╚════════════════════════════════╝
</pre>

<p><strong>Note:</strong></p>
<ul>
  <li>Choose <strong>1</strong> to start the bot</li>
  <li>Choose <strong>2</strong> to enter a license key(if necessary!)</li>
  <li>Choose <strong>3</strong> transfer your license to another device, instructions:</li>
  <li>Choose <strong>0</strong> to exit the launcher</li>
</ul>


<h3>5️⃣ Updates</h3>
<ul>
  <li>Bot checks GitHub for the latest release and notifies users.</li>
</ul>

<hr>

<h2>🤩 Have a good time with this bot (っ＾▿＾)۶🍸🌟🍺٩(˘◡˘ )</h2>

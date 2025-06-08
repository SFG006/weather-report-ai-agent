# ☁️ Weather Report AI Agent (n8n)

This repository contains an **AI-powered weather report agent** built using **n8n** and the **Open-Meteo API**. The agent automatically fetches weather data for **Lucknow** and sends a concise, natural-language report to your Gmail using an AI Agent.

---

## 🔧 Features

- 🌤 **Real-Time Weather** for Lucknow (via Open-Meteo API)
- 🤖 **AI-Powered Responses** using n8n's AI Agent node
- ✉️ **Automated Gmail Reports** with a catchy subject & human-like message
- 🔗 Uses **Google Gemini Model** for natural language generation
- ⚙️ Modular design, easy to extend for other cities or data types

---

## 📸 Screenshots

![Screenshot 2025-06-08 133950](https://github.com/user-attachments/assets/3d88a014-07e3-4239-aac8-7aebf994eee2)


## 🧠 How It Works

1. **Chat Trigger** activates the workflow.
2. The **AI Agent** interprets the user prompt.
3. The agent uses a tool that hits the **Open-Meteo API** for Lucknow.
4. Weather data is summarized by the **Google Gemini model**.
5. The final report is emailed via **Gmail** with a natural-sounding message.

---

## 🚀 Getting Started

1. Clone the repo or download the workflow file: `WEATHER_REPORT_AI_AGENT.json`
2. Import the JSON file into your **n8n instance**.
3. Add your credentials:
   - Open-Meteo doesn’t require an API key (public API).
   - Connect your **Gmail** and **Google Gemini API** accounts.
4. Trigger the workflow using the **chat node** or schedule it.
5. Receive an email with a smart weather report!

---

## 📦 Files Included

- `WEATHER_REPORT_AI_AGENT.json` – n8n workflow file

---

## 📝 Notes

- Currently designed for **Lucknow**, India.
- You can change the latitude and longitude in the HTTP request node to target another location.
- Works best with n8n's **AI Agent + Gemini + HTTP + Gmail** setup.

---

## 📍 Example Output

**Subject:** `Hot, Cold, or Stormy?`  
**Body:**

> Hey there!  
> Here’s your quick weather update for today:
>
> 🌡️ Temperature: 27°C  
> 🌤️ Mostly sunny with light clouds  
> 💨 Wind: 12 km/h NW  
> ☔ Chance of Rain: 10%  
>
> It’s a good day to step out—just don’t forget your shades! 😎

---

## 🧑‍💻 Author

Made by SFG006


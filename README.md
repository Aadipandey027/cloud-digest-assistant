# ☁️ CloudDigest — AWS Serverless Daily Personalized Assistant

A production-ready full-stack serverless application that delivers personalized daily morning updates (Weather, AQI, Crypto Rates, Tech News, Python Tips) straight to users' email inboxes every day at 8:00 AM IST.

🚀 **Live Demo:** https://cloud-digest-assistant.vercel.app/

---

## ✨ Features
- ⛅ **Real-Time Weather & AQI Alerts:** Live location-based weather tracking.
- 📈 **Crypto & Financial Market Updates:** Live Bitcoin and Ethereum prices.
- 📰 **Trending Tech News:** Top stories fetched dynamically via HackerNews Live API.
- 🐍 **Daily Python Tips:** Automated tips rotation for developers.
- ⏰ **Automated Cron Pipeline:** Zero manual trigger required, runs daily at 8:00 AM IST.

---

## 🛠️ Tech Stack & Architecture
- **Frontend:** HTML5, Tailwind CSS, Google Maps Location Embed
- **Backend & Serverless Engine:** AWS Lambda (Python 3.12)
- **Database:** AWS DynamoDB (`UserSubscriptions` table)
- **Automation Cron:** AWS EventBridge Scheduler
- **Hosting & CI/CD:** Vercel + GitHub Pipeline
- **Email Delivery:** Python `smtplib` with custom HTML responsive templates

---

## 👨‍💻 Developer
Developed with ❤️ by **Aditya Kumar Pandey**

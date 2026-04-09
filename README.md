<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,50:16213e,100:0f3460&height=220&section=header&text=complete-telegram-group-bot&fontSize=40&fontColor=ffffff&fontAlignY=40&desc=✘%20𝙍𝘼𝙑𝙀𝙉%20|%20@P_X_24&descAlignY=62&descSize=20&animation=twinkling" />

<br/>

<a href="https://t.me/P_X_24">
  <img src="https://img.shields.io/badge/المطور-✘%20𝙍𝘼𝙑𝙀𝙉-0d0d0d?style=for-the-badge&logo=telegram&logoColor=white" />
</a>
<a href="https://t.me/P_X_24">
  <img src="https://img.shields.io/badge/Telegram-@P__X__24-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" />
</a>
<a href="https://www.python.org/">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</a>
<a href="https://github.com/eternnoir/pyTelegramBotAPI">
  <img src="https://img.shields.io/badge/pyTelegramBotAPI-Latest-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" />
</a>
<a href="LICENSE">
  <img src="https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge&logo=opensourceinitiative&logoColor=white" />
</a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=2CA5E0&center=true&vCenter=true&width=700&lines=complete-telegram-group-bot+%F0%9F%A4%96;Full+Telegram+Group+Management+Bot;Ranks+%7C+Lock+%7C+Games+%7C+Replies;Built+by+%E2%9C%98+%F0%9D%99%8D%F0%9D%98%BC%F0%9D%99%91%F0%9D%99%80%F0%9D%99%89" />

</div>

---

<div dir="rtl">

## 🌐 اللغة | Language

**[العربية](#-نظرة-عامة)** &nbsp;|&nbsp; **[English](#-overview)**

---

## 📌 نظرة عامة

بوت تيليجرام متكامل لإدارة المجموعات بشكل احترافي، يوفر نظام رتب متعدد المستويات، وأوامر قفل وفتح شاملة، وردود تلقائية، وألعاب، وإدارة كاملة للأعضاء — مبني بـ **Python** و **pyTelegramBotAPI**.

---

## ✨ المميزات

| الميزة | الوصف |
|--------|-------|
| 👑 **نظام رتب متعدد** | 10 رتب: عضو، مميز، مشرف، ريف، منشئ، مالك، مطور وأكثر |
| 🔒 **قفل وفتح شامل** | قفل الصور، الفيديو، الصوت، الروابط، الملفات، الملصقات وأكثر |
| 🚫 **إدارة المخالفين** | طرد، كتم، حظر مع قاعدة بيانات كاملة |
| 💬 **ردود تلقائية** | ردود محلية وعامة قابلة للتخصيص |
| 🎮 **ألعاب** | ألعاب تفاعلية داخل المجموعات |
| 📊 **نقاط ورتب** | نظام نقاط تلقائي بناءً على النشاط |
| 📢 **ردود القنوات** | التحكم في ردود القنوات العامة |
| 🔐 **اشتراك إجباري** | التحقق من اشتراك الأعضاء |
| ⬆️ **رفع وتنزيل** | أوامر رفع وتنزيل الملفات |
| 🆔 **معرفة الهويات** | عرض معرفات المستخدمين والمجموعات |

---

## 📋 المتطلبات

- Python **3.10** أو أحدث
- بوت تيليجرام من [@BotFather](https://t.me/BotFather)

---

## ⚙️ متغيرات البيئة

| المتغير | الوصف | المصدر |
|---------|-------|--------|
| `BOT_TOKEN` | توكن البوت | [@BotFather](https://t.me/BotFather) |

---

## 🚀 طريقة التشغيل

**1. استنساخ المشروع**
```bash
git clone https://github.com/hsh34811-hash/-.git
cd complete-telegram-group-bot
```

**2. تثبيت المكتبات**
```bash
pip install -r requirements.txt
```

**3. إعداد المتغيرات**
```bash
cp .env.example .env
# عدّل ملف .env وضع توكن البوت
```

**4. تشغيل البوت**
```bash
python main.py
```

---

## 🗂️ هيكل المشروع

```
📁 complete-telegram-group-bot
├── 📄 main.py                      # نقطة الدخول الرئيسية
├── 📄 config.py                    # إعدادات البوت
├── 📄 database_main.py             # قاعدة البيانات الرئيسية
├── 📄 Ranks.py                     # نظام الرتب
├── 📄 Cick_Mute_Block.py           # الطرد والكتم والحظر
├── 📄 Lock_and_unlock_commands.py  # أوامر القفل والفتح
├── 📄 Local_replies.py             # الردود المحلية
├── 📄 Public_response_channel.py   # ردود القنوات
├── 📄 gamesBot.py                  # الألعاب
├── 📄 cmdGbot.py                   # أوامر المجموعة
├── 📄 functions_to_my_bots.py      # دوال مساعدة
├── 📄 performance_bot_private.py   # الخاص
├── 📄 Bot_join_commands.py         # أوامر الانضمام
├── 📄 Upload_and_download_commands.py # رفع وتنزيل
├── 📄 Identification_id.py         # معرفة الهويات
├── 📄 messagesBots.py              # رسائل البوت
├── 📄 requirements.txt
└── 📄 README.md
```

---

## 👑 نظام الرتب

| الرتبة | الصلاحيات |
|--------|-----------|
| `member` | عضو عادي |
| `distinct` | مميز |
| `admin` | مشرف |
| `reeve` | ريف |
| `creator2` | منشئ مساعد |
| `creator` | منشئ |
| `owner2` | مالك مساعد |
| `owner` | مالك |
| `devloper2` | مطور مساعد |
| `devloper` | مطور |
| `bulder` | باني |
| `programmer` | مبرمج |

---

## 👨‍💻 المطور

<div align="center">

| | |
|--|--|
| **الاسم** | ✘ 𝙍𝘼𝙑𝙀𝙉 |
| **تيليجرام** | [![Telegram](https://img.shields.io/badge/@P__X__24-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/P_X_24) |

</div>

---

</div>

## 📌 Overview

A full-featured Telegram group management bot with a multi-level rank system, comprehensive lock/unlock commands, auto-replies, games, and complete member management — built with **Python** and **pyTelegramBotAPI**.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 👑 **Multi-Level Ranks** | 10 ranks: member, distinct, admin, reeve, creator, owner, developer and more |
| 🔒 **Comprehensive Lock/Unlock** | Lock photos, videos, audio, links, files, stickers and more |
| 🚫 **Violation Management** | Kick, mute, ban with full database |
| 💬 **Auto Replies** | Customizable local and global replies |
| 🎮 **Games** | Interactive games inside groups |
| 📊 **Points & Ranks** | Automatic points system based on activity |
| 📢 **Channel Replies** | Control public channel responses |
| 🔐 **Forced Subscription** | Verify member subscriptions |
| ⬆️ **Upload & Download** | File upload and download commands |
| 🆔 **ID Identification** | Display user and group IDs |

---

## 📋 Requirements

- Python **3.10** or newer
- Telegram bot from [@BotFather](https://t.me/BotFather)

---

## ⚙️ Environment Variables

| Variable | Description | Source |
|----------|-------------|--------|
| `BOT_TOKEN` | Bot Token | [@BotFather](https://t.me/BotFather) |

---

## 🚀 Getting Started

**1. Clone the repository**
```bash
git clone https://github.com/hsh34811-hash/-.git
cd complete-telegram-group-bot
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Setup environment**
```bash
cp .env.example .env
# Edit .env and fill in your bot token
```

**4. Run the bot**
```bash
python main.py
```

---

## 👑 Rank System

| Rank | Permissions |
|------|-------------|
| `member` | Regular member |
| `distinct` | Distinguished |
| `admin` | Admin |
| `reeve` | Reeve |
| `creator` | Creator |
| `owner` | Owner |
| `devloper` | Developer |
| `programmer` | Programmer |

---

## 👨‍💻 Developer

<div align="center">

| | |
|--|--|
| **Name** | ✘ 𝙍𝘼𝙑𝙀𝙉 |
| **Telegram** | [![Telegram](https://img.shields.io/badge/@P__X__24-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/P_X_24) |

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:0d0d0d&height=130&section=footer&animation=twinkling" />

**Made with ❤️ by [✘ 𝙍𝘼𝙑𝙀𝙉](https://t.me/P_X_24)**

</div>

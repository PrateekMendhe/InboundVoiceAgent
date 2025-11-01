# 🤖 AI Inbound Voice Agent for n8n

Automated voice agent that books appointments, manages clients, and integrates into your CRM.

---

## 🎥 Video Guide

[![Watch the Setup Tutorial](https://img.youtube.com/vi/8evYjk8vXtI/maxresdefault.jpg)](https://youtu.be/8evYjk8vXtI)

**[👉 Watch Full Tutorial](https://youtu.be/8evYjk8vXtI)**

**[🎁 Join FREE Skool Community - Get 50+ AI Agent Templates](https://www.skool.com/chase-ai-community)**

---

## ⚡ How It Works
```
📞 Call → 🎙️ ElevenLabs AI → 🔧 n8n Webhooks → 📊 Google Services → 💬 Response
```

---

## 🎯 What It Does

- 📅 **Check availability** - Finds open calendar slots (9 AM - 5 PM)
- 📝 **Book appointments** - Creates events with auto-invites
- 🔄 **Modify/Cancel** - Updates or removes bookings
- 👥 **Client lookup** - Retrieves customer data by email
- ➕ **Add clients** - Onboards new customers
- 📊 **Track calls** - Logs transcripts and summaries

---

## 🛠️ Requirements

| Service | Cost |
|---------|------|
| ElevenLabs | $5-25/mo |
| Twilio | $20 one-time |
| Google (Calendar + Sheets) | Free |
| n8n | Free (self-hosted) |

---

## 🚀 Quick Setup

1. Import workflow to n8n
2. Connect OAuth (Google Calendar + Sheets)
3. Add ElevenLabs + Twilio credentials
4. Update Calendar ID and Sheet Document ID
5. Map n8n webhook URLs to ElevenLabs tools
6. Test and deploy 🎉

---

## ⚙️ Configuration
```javascript
workdayStartHour: 9           // Business hours start
workdayEndHour: 17            // Business hours end
minGapMinutes: 60             // Minimum appointment length
timeZone: 'America/Chicago'   // Your timezone
```

---

## 📋 Database Structure

**Clients:** First Name | Last Name | Email | Phone | Balance  
**Calls:** Email | Phone | Call Summary

---

## 🎬 Perfect For

🏋️ Gyms | 🏥 Medical | 💼 Consulting | 🔧 Services | 📚 Coaching

---

## 🌟 Benefits

| Before | After |
|--------|-------|
| ❌ Manual scheduling | ✅ Automatic 24/7 |
| ❌ Missed calls | ✅ Never miss a booking |
| ❌ Data entry | ✅ Auto-logged |
| ❌ Expensive staff | ✅ $5-25/month |

---

## 💡 Key Features

✅ Smart gap detection between appointments  
✅ Timezone-aware formatting  
✅ Robust error handling  
✅ Real-time calendar sync  
✅ Call analytics tracking

---

## 🏆 Credits

**Created by [Chase AI](https://www.skool.com/chase-ai-community)**

**Ready to start your own AI Agency? Join [Chase AI+](https://www.skool.com/chase-ai)**

---

**Now go automate!** 🚀

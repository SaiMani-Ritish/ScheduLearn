#  ScheduLearn

**ScheduLearn** is an AI-powered assistant that intelligently schedules podcasts and videos (from Spotify and YouTube) into your Google Calendar, based on:  
- Preferred Topics  
- Available Time Slots  
- Desired Duration  

The goal is to help you turn idle time into learning time by fitting short, meaningful podcast episodes into your day — no manual searching or scheduling needed.  

---

## Features (WIP)

 Automatically fetches podcast episodes based on your topics  
 Filters episodes based on your available time and preferences  
 Schedules the podcast as a Calendar event with link + title  
 (Coming Soon) Integrate YouTube as a content source  
 (Coming Soon) Smart scheduling using calendar availability  

---

## Setup Instructions

### 1. Google Calendar API

- Create a project in [Google Cloud Console](https://console.cloud.google.com/)  
- Enable the **Google Calendar API**  
- Create **OAuth 2.0 Client ID** credentials and download `credentials.json`  
- Save `credentials.json` in your working directory  

### 2. Install Required Packages

```bash
pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib spotipy
```

### 3. Update Config File
Rename `example.config.py` to `config.py`

Add the relevant API keys and credentials in the file

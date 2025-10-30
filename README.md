# 🎧 Spotify Dashboard

*A Power BI dashboard for analyzing Spotify song and artist performance.*

---

## 📌 Business Requirement

Spotify stakeholders — **music analysts**, **playlist managers**, and **marketing teams** — need a consolidated dashboard to monitor **song and artist performance** across different dimensions.

### 🎯 Objectives
- Track KPIs: **Total Songs**, **Distinct Artists**, **Average Popularity**, and **Average Duration**
- Compare **Explicit vs Non-Explicit** songs
- Analyze **Songs by Album Type** (single, album, compilation)
- View **Distinct Songs & Avg Popularity by Year**
- Trend analysis: **Popularity** & **Distinct Songs by Month**
- Highlight **Top Songs & Top Artists by Popularity**

---

## 🧩 Dashboard Pages

### 🏠 Overview Page
- KPIs for songs, artists, popularity, and duration  
- Explicit vs Non-Explicit song comparison  
- Distribution by album type and release year  
- Monthly trends of popularity and song count  

### 🎤 Artist Page
- Top artists by popularity  
- Songs and albums per artist  
- Drill-down insights (release date, avg popularity, duration)  
- Identify artists with consistent hits or #1 positions  

### 🎵 Songs Page
- Top songs by popularity  
- Album vs Single distribution  
- Song count comparison  
- Detailed table: name, release date, popularity, duration  

---

## 🚩 Problem Statement

Spotify’s raw “Top 50” dataset only provides rankings, not insights.  
This dashboard helps stakeholders quickly **see trends, performance patterns, and KPIs** that aid decision-making.

**Problems Solved:**
- ✅ No clear KPI tracking → Dashboard provides metrics at a glance  
- ✅ Missing explicit/non-explicit analysis → Added visual comparison  
- ✅ Poor visibility of album distribution → Clear breakdowns by album type/year  
- ✅ Missing trend insights → Added monthly/yearly visuals  
- ✅ Lack of artist-song connection → Drill-down interactivity  
- ✅ Data-driven decisions → Identify top-performing artists and songs  

---

## 🧠 Tools & Technologies
- **Power BI** (data visualization)
- **Spotify Dataset** (Top 50)
- **Excel / CSV** (data preparation)
- **DAX & Power Query** (data modeling)
- **GitHub** (project version control)

---

## 🗂️ Folder Structure
```bash
Spotify-Dashboard/
├── assets/
│   └── icon.png
├── Business_Requirements/
│   └── Business Requirements.docx
├── Data/
│   └── spotify_top50.csv
├── PowerBI/
│   └── Spotify_Dashboard.pbix
├── Dashboard_Screens/
│   └── overview.png
│   └── artist_page.png
│   └── songs_page.png
└── README.md

# 🎬 ProDoge Video Network

A high-performance, minimalist video streaming platform built with **Next-level Video Architecture**.

## 🚀 Features
- **High-Class Player:** Uses Plyr.js for a premium, ads-free viewing experience.
- **Backend:** Powered by **Supabase** for real-time data and secure storage.
- **Cloud Hosting:** Automatically deployed via **Vercel**.
- **Mobile Optimized:** Fully responsive grid layout using Tailwind CSS.

## 🛠 Setup Instructions (No Terminal)
1. **GitHub:** Save `index.html` in your repository.
2. **Supabase:** 
   - Create a bucket named `video-uploads` (Set to Public).
   - Create a table named `videos` with columns: `title` (text) and `url` (text).
   - Insert a row with your video name and the link from your Storage bucket.
3. **Vercel:** Import this repo and click **Deploy**.

## 📝 Credentials Note
This site is pre-configured with the specific Supabase URL and Key provided for the project.

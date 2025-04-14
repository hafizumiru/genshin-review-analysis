# Genshin Review Analysis

📊 **Project Overview**
This project analyzes user reviews of the mobile game **Genshin Impact** on Google Play Store, with a specific focus on reviews submitted for **App Version 5.5** — the most recent release at the time of analysis.

---

## 🎯 Objectives

- Understand the **perception of users** towards Genshin Impact version 5.5.
- Identify **recurring themes**, feedback, and pain points from user reviews.
- Perform **sentiment analysis** on textual reviews.
- Visualize rating distribution and observe trends.

---

## 📁 Dataset

- Source: [Google Play Store Scraped Data]
- Total Reviews: ~1285
- Filtered Version: **App Version 5.5**
- Key Columns:
  - `content` - User review text
  - `score` - Rating from 1 to 5
  - `at` - Date of review
  - `appVersion` - Version of the app reviewed

---

## 🔧 Preprocessing Steps

- Drop irrelevant columns (e.g., `userImage`, `replyContent`, `repliedAt`)
- Handle missing values and format dates
- Clean text data (lowercasing, punctuation removal, stopwords)
- Filter only reviews with `appVersion == 5.5`

---

## 🔍 Analysis Highlights

- 📈 Rating Distribution for v5.5
- 🧠 Word Frequency in Positive vs Negative Reviews
- 💬 Sentiment Polarity
- ⏳ Review Trend over Time (within v5.5 lifecycle)
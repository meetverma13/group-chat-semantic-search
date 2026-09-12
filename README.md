# Search a Group Chat Properly

A zero-backend semantic search engine designed for unstructured, code-mixed (Hinglish) group chat archives.

## 🚀 Live Demo & Project Links
- **Live Deployed App:** https://group-chat-search-ap-7u0w.bolt.host
- **Demo Video:** [PASTE_YOUR_LOOM_OR_DRIVE_VIDEO_LINK_HERE]

---

## 📊 Evaluation & Benchmark Performance
- **Overall Benchmark Accuracy (40 queries):** 87.5%
- **Hard Zero-Word-Overlap Accuracy (8 queries):** 75.0%
- **Accuracy Gap:** 12.5%

---

## 🔥 Key Technical Features

1. **Multi-Intent Search Router:**
   - **Person Intent:** Direct metadata filtering by sender (e.g., *"What did Priya say..."*).
   - **Temporal Intent:** Date range and timestamp window filtering (e.g., *"What did we discuss last month..."*).
   - **Semantic/Meaning Intent:** Hinglish synonym mapping combined with TF-IDF cosine similarity scoring (e.g., *"When did we decide on the trip?"* $\rightarrow$ matches *"chalo Manali fix hai"*).
2. **Context Window UI:** Renders target search results alongside 3 preceding and 3 succeeding messages to preserve conversation context.
3. **Synthetic Corpus Support:** Evaluates over 4,000 messy chat entries spanning 6 months across 8 participants.

---

## 🛠️ Tech Stack
- **Frontend Framework:** React + Vite
- **Styling:** Tailwind CSS
- **Deployment Platform:** Bolt Host

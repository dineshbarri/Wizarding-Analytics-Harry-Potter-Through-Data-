<div align="center">
  <h1>🔮 The Wizarding World Unveiled: A Harry Potter Data Journey</h1>
  <p>
    <strong>Wizarding Analytics</strong><br>
    Explore J.K. Rowling’s magical universe through data — book sales, word counts, character mentions, and more.
  </p>
  <p>
    <a href="https://public.tableau.com/app/profile/dinesh.barri8170/viz/TheWizardingWorldUnveiledAHarryPotterDataJourney/Dashboard1" target="_blank">
      🚀 View Live Tableau Dashboard
    </a>
  </p>
  <img src="images/preview.gif" alt="Tableau Dashboard Preview" width="80%" style="border-radius:12px; border:2px solid #ccc; margin-top:10px;">
</div>

---

## ✨ Project Overview

Welcome to **Wizarding Analytics** — a data-driven exploration of the Harry Potter universe.  
This project weaves together multiple public datasets (book metadata, character stats, full text corpora) to create immersive visual stories about J.K. Rowling’s saga.  
From comparing book popularity and awards to mapping character appearances and sentiment trends — this is Harry Potter reimagined through analytics.

---

## 🧱 Key Themes & Dashboards

Here’s what you’ll find in the Tableau workbook:

| Theme | Description |
|---|---|
| **Book Metrics** | Compare book sales, pages, awards, release year side by side. |
| **Character Analytics** | Show top characters by count, book-wise appearance, and co-occurrence networks. |
| **Text & Sentiment** | Word count per book, sentiment score trends across chapters. |
| **Interactive Storytelling** | Filters by book, character, and year to drive custom insights. |

Each dashboard panel is designed for clarity, narrative progression, and visual cohesion — dark theme with rich colors to match the magical theme.

---

## 📦 Data Sources & Processing

**Primary Datasets used:**

- *Book metadata*: Sales, awards, page counts, release years (merged from Kaggle sources) :contentReference[oaicite:4]{index=4}  
- *Full texts of all 7 books* (in `.txt`) for word-level analytics :contentReference[oaicite:5]{index=5}  
- *Character dataset* listing character appearances across books :contentReference[oaicite:6]{index=6}  
- *Pottermore / fandom metadata* (optional enrichments) :contentReference[oaicite:7]{index=7}  

**Processing steps (pre-Tableau):**

1. Clean metadata — unify column names, handle missing values.  
2. Parse full text to compute metrics (word count, sentence count, frequency of character names).  
3. Join character stats with metadata to support cross-filtering.  
4. Export final CSVs (e.g. `book_metrics.csv`, `character_counts.csv`, `sentiment_by_book.csv`).

---

## 🖼️ Screenshots & GIF Preview

Here are visuals of the dashboard in action:

| Screen | Description |
|---|---|
| ![Dashboard gif](images/preview.gif) | Full interactive dashboard in motion |
| ![Book metrics screenshot](images/book_metrics.png) | Book comparison: sales, pages, awards |
| ![Character trend screenshot](images/char_trend.png) | Character mention trends across books |

(*Note: more images in the `images/` folder.*)

---

## 🚀 How to Explore

1. **Open the Tableau Public link** above to view the live dashboard.  
2. Download the `.twbx` workbook from this repo (in `tableau/` folder) to open locally in Tableau Desktop / Tableau Public.  
3. You can replace or update the data CSVs in `data/` and refresh the workbook to see new visuals.  
4. Experiment: add new datasets (fanfiction, film data) or new sheets (e.g. house themes, quotes).

---

## 🧠 Insights & Findings

Here are some highlights I discovered:

- *“Harry Potter and the Deathly Hallows”* leads both in page count and sales among the 7.  
- The later books tend to have more negative sentiment overall (more conflict, darker tone).  
- Some supporting characters spike in mentions unexpectedly in specific books (e.g. **Dumbledore**, **Snape**).  
- Awards do not always correlate with highest sales or pages — interesting discrepancies emerge.

These patterns reveal the tension between narrative, popularity, and reception in the wizarding world.

---

## 📚 How You Can Extend This

- Add **house-level** analytics: affiliation, mention count per house.  
- Integrate **movie box office / ratings** data to compare book vs film popularity.  
- Visualize **character networks**: co-occurrence graphs, centrality metrics.  
- Use **natural language processing**: topic modeling, sentiment timeline per chapter.

---

## 🧑‍💻 About & License

**Author:** Your Name / GitHub (e.g. Dinu)  
**Contact:** [dineshbarri1997@gmail.com] / [https://www.linkedin.com/in/dinesh-barri/]  

**License:** MIT (or whatever open license you prefer)  

---

> “Words are, in my not-so-humble opinion, our most inexhaustible source of magic.” — *Albus Dumbledore*

---

Let me know when you have added your Tableau workbook and images, and I can generate a **preview GIF** from it or help you integrate it with GitHub Pages so your repo looks polished and clickable.
::contentReference[oaicite:8]{index=8}

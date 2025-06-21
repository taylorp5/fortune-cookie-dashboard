# 🥠 Fortune Cookie Dashboard

> **Click the cookie. Reveal your fortune. Analyze the trends.**

An interactive Excel dashboard that brings hundreds of fortune cookie messages to life using Power Query, VBA macros, and creative design.

---

## 💡 Inspiration

This project was born out of a habit I didn’t realize I had — collecting fortune cookie messages. When I moved out of my college apartment recently, I found an embarrassing number of them taped to my walls, tucked in drawers, and even scattered around my desk. Most were mine, but I had also started collecting my friends’ fortunes anytime we ate together.

As I looked at the pile, I thought: *“What if I actually analyzed these?”* That turned into this playful but data-driven dashboard.

---

## 🧰 Tools Used

- Microsoft Excel
- Microsoft Co-Pilot
- Power Query
- VBA (macros)
- Form controls & shape layering
- Data visualizations (bar, donut, word cloud)

---

## 🧼 Data Cleaning

I collected over 500 messages and cleaned them using Power Query. Themes, subthemes, and keywords were manually categorized and tagged for analysis.

[Data Cleaning Screenshot](Fortune_Cookie_DC_PQ.jpg)


---

## 🧠 VBA Interactivity

Using shape layering and the Selection Pane, I created a reveal sequence where clicking a fortune cookie image shows a message and then displays the full dashboard.

[VBA Editor and Shape Setup](Fortune_Cookie_VBA.png)

---

## 🗂️ Raw Dataset Snapshot

The dataset includes fields like `Message`, `Theme`, `Subtheme`, `Source`, and `Location`. Keywords were identified using Excel formulas.

[Raw Data Format](Fortune_Cookie_Raw_Data.png)

---

## 📦 Dataset

The dataset used for this project contains 500 fictional fortune cookie messages along with associated themes, subthemes, source restaurants, and locations. Since no public dataset like this exists, the messages were generated using GitHub Copilot based on real-world formatting patterns and tone.

The goal was to create a realistic, structured sample to showcase data cleaning, categorization, and interactive dashboard design in Excel — not to conduct an academic linguistic study.

➡️ This dataset simulates what you'd get from compiling messages over time from various restaurants and regions.


## 📊 Dashboard Visuals

The dashboard features:

- 🥇 Top **Themes** (Donut Chart)
- 🧠 Top **Subthemes** (Bar Chart)
- 🧾 **Word Cloud** of Most Common Keywords
- 📍 **Location Breakdown** by Message Count

---

## 📸 Dashboard Preview

> Screenshot these from Excel and upload to GitHub for embedding.

```md
![Initial View - Cookie Only](images/before_click.png)
![Fortune Reveal](images/fortune_shown.png)
![Full Dashboard View](images/dashboard_view.png)

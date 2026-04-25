# 🍕 Pizza Fresh & Tasty — Sales Dashboard Analysis

> **A complete freelance data analysis project** — from raw dashboard screenshots to a professional client report (`.docx`) and a LinkedIn-ready pitch deck (`.pptx`).

---

## 📌 Project Overview

This project analyses the **Pizza Fresh & Tasty** sales dashboard and delivers two client-ready documents:

| Deliverable | Format | Purpose |
|---|---|---|
| Sales Performance Report | `.docx` | Full client report with KPIs, product analysis, time-demand breakdown & 7 strategic recommendations |
| LinkedIn Pitch Deck | `.pptx` | 8-slide visual deck optimised for LinkedIn carousel posts |

The analysis covers **three dashboard views**: Overview, Time Analysis, and Key Insights — extracting actionable intelligence to help the business grow.

---

## 📊 Key Findings at a Glance

```
💰 Total Revenue    ₹8,17,860   ▲ +12% MoM
📦 Total Orders       12,450    ▲  +8% MoM
🍕 Units Sold         18,900    ▼  -3% MoM
🎯 Avg Order Value      ₹650    ▲  +5% MoM
```

- 🔥 **Peak Hour:** 12 PM — 6,543 orders
- 📅 **Peak Day:** Friday — 8,106 orders
- 🏆 **Top Pizza:** The Classic Deluxe Pizza (2,453 units)
- 🚨 **Critical Outlier:** The Brie Carre Pizza (490 units — 5× below #1)

---

## 🗂️ Repository Structure

```
pizza-sales-analysis/
│
├── 📄 README.md                    ← You are here
│
├── 📁 inputs/
│   ├── dashboard_overview.png      ← Dashboard screenshot 1 (KPIs + top/bottom sellers)
│   ├── dashboard_time.png          ← Dashboard screenshot 2 (hourly + daily demand)
│   └── dashboard_insights.png     ← Dashboard screenshot 3 (strategic takeaways)
│
├── 📁 outputs/
│   ├── Pizza_Sales_Report.docx     ← Full client Word report
│   └── Pizza_LinkedIn_Deck.pptx   ← LinkedIn carousel deck
│
└── 📁 scripts/
    ├── generate_report.py          ← Python script (python-docx) → .docx
    └── generate_ppt.js             ← Node.js script (pptxgenjs) → .pptx
```

---

## 🛠️ Tech Stack

| Tool | Version | Purpose |
|---|---|---|
| Python | 3.11+ | Report generation |
| `python-docx` | 1.2.0 | Word document creation |
| Node.js | 18+ | PPT generation |
| `pptxgenjs` | 4.0.1 | PowerPoint creation |

---

## ⚙️ Setup & Usage

### Prerequisites

Make sure you have Python and Node.js installed on your machine.

```bash
# Check versions
python --version    # 3.11+
node --version      # 18+
npm --version
```

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/pizza-sales-analysis.git
cd pizza-sales-analysis
```

### 2. Install Python Dependencies

```bash
pip install python-docx
```

### 3. Install Node.js Dependencies

```bash
npm install pptxgenjs
```

### 4. Generate the Word Report

```bash
python scripts/generate_report.py
# Output → outputs/Pizza_Sales_Report.docx
```

### 5. Generate the PowerPoint Deck

```bash
node scripts/generate_ppt.js
# Output → outputs/Pizza_LinkedIn_Deck.pptx
```

---

## 📑 Report Sections

### Word Report (`Pizza_Sales_Report.docx`)

1. **Executive Summary** — Business context and high-level narrative
2. **KPI Table** — 4 core metrics with MoM delta and colour-coded status
3. **Product Performance** — Top 5 (green) and Bottom 5 (red) seller tables + revenue by category
4. **Time-Based Demand** — Full hourly breakdown (9 AM–11 PM) and day-of-week analysis
5. **Strategic Recommendations** — 7 numbered action items (R1–R7)
6. **Conclusion** — Prioritised next steps with 30–60 day implementation timeline

### LinkedIn Deck (`Pizza_LinkedIn_Deck.pptx`)

| Slide | Title |
|---|---|
| 1 | Cover — Brand intro |
| 2 | Key Performance Highlights |
| 3 | Product Performance — Best & Worst Sellers |
| 4 | Revenue by Pizza Category |
| 5 | Orders by Hour of Day |
| 6 | Orders by Day of Week |
| 7 | Strategic Recommendations |
| 8 | Key Takeaways + CTA |

---

## 💡 Strategic Recommendations Summary

| # | Recommendation | Priority |
|---|---|---|
| R1 | Maximise lunch rush staffing (12–1 PM) | 🔴 High |
| R2 | Launch dinner window promos (17–19 hrs) | 🔴 High |
| R3 | "Sunday Special" activation campaign | 🟡 Medium |
| R4 | Weekend combo/limited-edition deals (Fri–Sat) | 🟡 Medium |
| R5 | Review/discontinue Brie Carre Pizza | 🔴 High |
| R6 | Weekly "Featured Pizza" rotation for Top 5 | 🟢 Low |
| R7 | Structured upselling at checkout (XL/XXL) | 🟡 Medium |

---

## 🎨 Design Choices

- **Colour palette:** Brand green (`#2E8B2E`) + dark navy (`#1A1A2E`) + red alerts (`#C0392B`)
- **Typography:** Georgia (headings) + Calibri (body) — professional and universally supported
- **Word doc:** Colour-coded tables, HR dividers, confidentiality footer
- **PPT deck:** Dark cover, KPI cards with delta badges, native charts (editable in PowerPoint), 3-column recommendation grid

---

## 📤 LinkedIn Usage Tip

To get maximum reach on LinkedIn, **upload the `.pptx` as a PDF document post** — LinkedIn renders each slide as a swipeable carousel, which typically gets 3–5× more impressions than a static image.

```
File → Save As PDF → Upload to LinkedIn as "Document" post
```

---

## 👤 Author

**DataEdge Analytics** — Freelance Data Analysis & Business Intelligence

> *Turning raw dashboards into decisions.*

---

## 📄 License

This project is for client demonstration purposes. All data is fictional and used for analytical illustration only.

---

*Made with 🍕 and data*

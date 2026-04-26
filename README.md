# 🍕 Pizza Fresh & Tasty — Sales Dashboard

> An interactive Excel dashboard analyzing pizza sales performance across revenue, product, and time dimensions — with a full client report (`.docx`) and LinkedIn deck (`.pptx`) included.

---

## 📸 Preview

| Overview | Time Analysis | Key Insights |
|----------|--------------|--------------|
| ![Overview](Dashboard/Dashboard_Overview.png) | ![Time](Dashboard/Dashboard_TimeAnalysis.png) | ![Insights](Dashboard/Dashboard_Insight.png) |

> *Screenshots from the live Excel dashboard.*

---

## 📁 Project Structure

```
pizza-sales-dashboard/
│
├── 📊  Pizza_Sales_Dashboard.xlsx       ← Main Excel dashboard (3 tabs)
├── 📝  Pizza_Sales_Report.docx          ← Full client report (Word)
├── 📽️  Pizza_LinkedIn_Deck.pptx         ← LinkedIn presentation (8 slides)
│
├── assets/
│   ├── preview_overview.png
│   ├── preview_time.png
│   └── preview_insights.png
│
└── README.md
```

---

## 📊 Dashboard Tabs

### 1. Overview
- **Total Revenue** — ₹8,17,860 (+12% MoM)
- **Total Orders** — 12,450 (+8% MoM)
- **Total Units Sold** — 18,900 (−3% MoM)
- **Avg Order Value** — ₹650 (+5% MoM)
- Top 5 & Bottom 5 best/worst selling pizzas (bar charts)
- Revenue breakdown by category: Classic, Supreme, Chicken, Veggie (donut chart)
- Interactive slicers: filter by **Size** (S / M / L / XL / XXL) and **Category**

### 2. Time Analysis
- Orders by **Hour of Day** (line chart) — peaks at 12–1 PM (6,543 orders)
- Orders by **Day of Week** (column chart) — Friday is highest (8,106), Sunday lowest (5,917)

### 3. Insights
- Written strategic takeaways covering revenue trends, product outliers, and time-based opportunities

---

## 🔑 Key Findings

| Finding | Detail |
|--------|--------|
| 💰 Revenue growing faster than orders | Customers ordering fewer but pricier items — upselling is working |
| 🔥 Lunch rush dominates | 12–13 hr window accounts for the single largest daily spike |
| 📅 Friday is peak day | 8,106 orders — 17% above weekly average |
| ⚠️ Sunday is weakest | 5,917 orders — 15% below average; activation campaign needed |
| 🚨 Brie Carre is a critical outlier | Only 490 units — ~5× less than the #1 pizza |
| 🏆 Top 5 sellers are tightly bunched | 2,371–2,453 units — no single runaway hit |

---

## 🛠️ Built With

- **Microsoft Excel** — PivotTables, PivotCharts, Slicers, Conditional Formatting
- **Microsoft Word** — Client report with formatted tables and analysis
- **PowerPoint** — LinkedIn-ready 8-slide deck

---

## 🚀 How to Upload This Project to GitHub

Follow these steps to publish this project on GitHub — no coding experience needed.

### Step 1 — Create a GitHub Account
If you don't have one, sign up free at [github.com](https://github.com).

---

### Step 2 — Create a New Repository

1. Click the **`+`** icon (top-right on GitHub) → **New repository**
2. Fill in the details:
   - **Repository name:** `pizza-sales-dashboard`
   - **Description:** `Excel sales dashboard for Pizza Fresh & Tasty with client report and LinkedIn deck`
   - **Visibility:** `Public` (so others can see it on LinkedIn) or `Private`
3. ✅ Check **"Add a README file"** → this pre-creates the repo
4. Click **"Create repository"**

---

### Step 3 — Upload Your Files

> ⚠️ GitHub doesn't render `.xlsx` or `.pptx` files visually in-browser, but visitors can still download them. Adding screenshot images (Step 5) lets people preview the dashboard without downloading anything.

#### Option A — Upload via Browser (Easiest, no installs)

1. Open your new repository on GitHub
2. Click **"Add file"** → **"Upload files"**
3. Drag and drop these files into the upload area:
   ```
   Pizza_Sales_Dashboard.xlsx
   Pizza_Sales_Report.docx
   Pizza_LinkedIn_Deck.pptx
   README.md
   ```
4. Add a commit message: `Add Excel dashboard, client report and LinkedIn deck`
5. Click **"Commit changes"** ✅

#### Option B — Upload via GitHub Desktop (Recommended for ongoing updates)

1. Download [GitHub Desktop](https://desktop.github.com/) and sign in
2. Click **"Clone a repository"** → find `pizza-sales-dashboard` → choose a local folder
3. Copy your project files into that local folder:
   ```
   Pizza_Sales_Dashboard.xlsx
   Pizza_Sales_Report.docx
   Pizza_LinkedIn_Deck.pptx
   README.md
   assets/   ← folder with your screenshots
   ```
4. GitHub Desktop will list all files under **"Changes"**
5. Write a summary (e.g., `Initial project upload`) → click **"Commit to main"**
6. Click **"Push origin"** — files are now live on GitHub 🎉

#### Option C — Git Command Line (Advanced)

```bash
# 1. Clone your repo locally
git clone https://github.com/YOUR_USERNAME/pizza-sales-dashboard.git
cd pizza-sales-dashboard

# 2. Copy your files into this folder, then:
git add .
git commit -m "Add Excel dashboard, client report and LinkedIn deck"
git push origin main
```

---

### Step 4 — Replace the Default README

1. On GitHub, click `README.md` → click the ✏️ **pencil icon** (Edit file)
2. Select all the existing text and paste in this README's contents
3. Update the preview image paths once screenshots are in the `assets/` folder
4. Scroll down → click **"Commit changes"**

---

### Step 5 — Add Dashboard Screenshots (Important!)

GitHub won't preview Excel files visually, so screenshots make your repo look professional.

**How to take screenshots:**
- **Windows:** `Win + Shift + S` → drag to select the chart area → paste into Paint and save as PNG
- **Mac:** `Cmd + Shift + 4` → drag to select → file saves to Desktop automatically

**What to capture:**
| File to save | What to screenshot |
|---|---|
| `assets/preview_overview.png` | The Overview tab of your Excel dashboard |
| `assets/preview_time.png` | The Time Analysis tab |
| `assets/preview_insights.png` | The Insights tab |

**How to upload screenshots:**
1. In your repo, click **"Add file"** → **"Upload files"**
2. Type `assets/` in the path field before the filename when uploading
   - Or create the folder first: click **"Add file"** → **"Create new file"** → type `assets/.gitkeep` → commit
3. Upload your 3 PNG files into the `assets/` folder
4. The preview table at the top of this README will automatically show them ✅

---

### Step 6 — Polish Your Repo's Appearance

1. **Add topics (tags):** In your repo, click the ⚙️ gear next to **"About"** → add:
   ```
   excel  dashboard  data-analytics  pizza  business-intelligence  data-visualization  pivottables
   ```
2. **Pin the repo:** Go to your GitHub profile → click **"Customize your profile"** → pin `pizza-sales-dashboard` so it shows up first
3. **Add a website link:** In **About**, you can link to your LinkedIn profile

---

### Step 7 — Share on LinkedIn

Once uploaded, copy your repo URL:
```
https://github.com/YOUR_USERNAME/pizza-sales-dashboard
```

**Post the `.pptx` as a LinkedIn carousel**, then add this in the caption:

```
📊 Just completed a full pizza sales dashboard project!

Built an interactive Excel dashboard analyzing 12,450+ orders —
covering revenue trends, best/worst sellers & hourly demand patterns.

Key insight: Revenue +12% while units sold dropped 3%
→ customers are upselling themselves 🍕

📁 Full project (Excel + report + slides) on GitHub — link in comments 👇

#DataAnalytics #Excel #Dashboard #BusinessIntelligence #DataVisualization #Portfolio
```

---

## ❓ FAQ

**Q: Can I open the dashboard without a paid Excel license?**  
A: Yes — [LibreOffice Calc](https://www.libreoffice.org/) (free) opens `.xlsx` files. Some slicer interactivity may look slightly different.

**Q: Why can't I see the Excel file preview on GitHub?**  
A: GitHub doesn't render Excel files. Add screenshots to the `assets/` folder — they'll show up in this README automatically.

**Q: Can I edit the data with my own pizza sales data?**  
A: Yes. The dashboard uses PivotTables — update the source data sheet and refresh the PivotTables (`Data → Refresh All`) to update all charts automatically.

---

## 📄 License

This project is for portfolio and educational purposes.  
Data is fictional and used for demonstration only.

---

## 👤 Author

**DataEdge Analytics** — Freelance Data Analyst  
*"Turning raw data into decisions."*

---

⭐ If this project was useful, consider starring the repo!

# 🎬 Worldwide Gross Film Analysis

A Tableau visualization analyzing the worldwide gross earnings of romantic/comedy films.  
**Hosted on Tableau Public:** [View Interactive Dashboard](https://public.tableau.com/app/profile/shanujan.suresh/)

---

## 📌 Project Overview
- **Goal**: Compare box office performance of romantic comedies and drama films.
- **Key Insights**:
  - Top-grossing film: *Twilight* (≈$700M)
  - Notable outliers: *High School Musical 3*, *Sex and the City* franchise
  - 80% of films grossed under $200M
- **Tools Used**: Tableau Public, Data Cleaning (Excel/Python)

---

## 📂 Files
```
worldwide-gross/
├── README.md               # This file
├── data/
│   └── worldwide_gross.csv # Raw dataset (films + earnings)
├── dashboards/
│   └── film_gross.twbx     # Packaged Tableau workbook
└── images/                 # Screenshots
    └── dashboard_preview.png
```

---

## 🔍 How to Use
### For Viewers:
1. **Interactive Version**: Click the [Tableau Public link](https://public.tableau.com/views/FilmInsights_17408244252750/WorldwideGross?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) above.
2. **Static View**: See `/images/dashboard_preview.png`.

### For Developers:
1. **Edit in Tableau**:
   ```bash
   git clone https://github.com/yourusername/worldwide-gross.git
   Open film_gross.twbx in Tableau Public/Desktop
   ```
2. **Rebuild from Data**:
   - Connect `worldwide_gross.csv` as a new data source
   - Recreate fields: `Film`, `Worldwide_Gross_Millions`

---

## 🛠️ Data Sources
| Column | Description | Type |
|--------|-------------|------|
| `Film` | Movie title | String |
| `Worldwide_Gross_Millions` | Earnings in millions (USD) | Integer |

**Note**: Original data sourced from [Box Office Mojo](https://www.boxofficemojo.com/) (hypothetical example).

---

## 💡 Suggested Improvements
- Add filters by release year/genre
- Incorporate Rotten Tomatoes scores
- Animate trends over time

---

## 📬 Contact
- **Email**: shanujansh@gmail.com  
- **LinkedIn**: [Shanujan Suresh](https://linkedin.com/in/shanujansuresh)  
- **Tableau Public**: [Shanujan suresh](https://public.tableau.com/app/profile/shanujan.suresh/)

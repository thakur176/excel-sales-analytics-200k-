# Excel Sales Analytics — 200k Rows

**Goal:** End-to-end Excel analytics project on large sales data (2021–2024): QA → Cleaning → Data Model → Pivot analysis → Interactive Dashboard.

## Files (what's in this repo)
- `SalesProject_Raw_QA.xlsx` — Raw data + QA checks (kept untouched for audit)  
- `SalesProject_Analysis_Dashboard.xlsx` — Cleaned data, Power Query steps, PivotTables, Dashboard, Notes  
- <img width="1890" height="629" alt="Screenshot 2025-08-31 220540" src="https://github.com/user-attachments/assets/cc90ee9a-3c90-49f7-ada2-4e598056ba72" />
 — Full dashboard screenshot  
- <img width="1043" height="617" alt="Screenshot 2025-08-31 220619" src="https://github.com/user-attachments/assets/943cd248-a3b2-4c54-be77-524a762ab086" />
 — Close-up: KPI cards & top metrics  
- <img width="1206" height="628" alt="Screenshot 2025-08-31 220644" src="https://github.com/user-attachments/assets/a4fff057-415c-45fc-95f4-f3db12f306a9" />
 — Close-up: Monthly trend / pivot chart  
- `Resources/FULL_DATA_LINK.txt` — Link to the full Excel file (https://www.dropbox.com/scl/fi/1j2e4gyt5h1wakbdy27zj/SalesProject_Analysis_Dashboard.xlsb?rlkey=dxaxd6a9ll9vaoe1u33jwyqyu&st=ygfpkonj&dl=0) — download link inside

> **Full Excel file (~40MB)** is hosted externally due to GitHub file-size limits.  
> **Download:** [Full Excel File (Dropbox)](https://www.dropbox.com/scl/fi/g3a3ct4hit8e8jeqsgg5i/SalesProject_Raw_QA.xlsx?rlkey=xdltc11cw5vcweuxut1yt1oel&st=a6c5yhis&dl=0)

---

## Highlights
- Processed and analyzed **200k+ sales rows** using Excel and Power Query.  
- Data cleaning & QA documented step-by-step in `SalesProject_Raw_QA.xlsx` (QA sheet).  
- Time intelligence: Order_Year / Order_Month / Order_Day derived fields.  
- Interactive PivotTables & PivotCharts with **Slicers** and **Timeline** for on-the-fly filtering.  
- KPIs: Total Sales, Orders, Average Order Value (AOV); breakdowns by Region, Category, SalesRep, Payment Mode; Top Customers; Monthly trend analysis.

---

## How to use (quick)
1. Download the full file (Dropbox link above) OR open `SalesProject_Analysis_Dashboard.xlsx`.  
2. Open the **Dashboard** sheet for the main interactive view (full screenshot in `/images`).  
3. Use the **Slicers** (Year / Region / SalesRep / PaymentMode) and **Timeline** (Order Date) to filter.  
4. To refresh after replacing data: `Data → Refresh All` (Power Query connections will refresh).

---

## Reproducibility & Audit
- Raw data is preserved in `SalesProject_Raw_QA.xlsx`. QA sheet includes the cleaning steps and issues found.  
- Power Query steps are documented inside `SalesProject_Analysis_Dashboard.xlsx` (Query Editor window).  
- If you need to re-run with updated raw data, replace rows in the Raw sheet and `Refresh All`.

---

## Screenshots (recommended)
- <img width="1890" height="629" alt="Screenshot 2025-08-31 220540" src="https://github.com/user-attachments/assets/2d8efc9b-cdcc-4a12-9805-6ce20c1d53ea" />
 — full dashboard screenshot  
- <img width="1043" height="617" alt="Screenshot 2025-08-31 220619" src="https://github.com/user-attachments/assets/5ba389ea-4c6f-4969-b5f5-f6da40ae4a4c" />
 — zoom into KPIs / cards (shows values & small formulas)  
- <img width="1206" height="628" alt="Screenshot 2025-08-31 220644" src="https://github.com/user-attachments/assets/07f9f337-934f-4f45-8a1b-aa187e8e9a81" />
 — zoom into trend chart & slicer interactions  
*(Close-ups help viewers quickly understand visuals and logic.)*

---

## Notes & assumptions
- Dataset is **synthetic / anonymized** and used for portfolio demonstration.  
- Designed for storytelling and business review: quick executive KPIs + drill-down capability.

---

## Repo structure (recommended)

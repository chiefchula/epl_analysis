# ⚽ Premier League Table Builder: From Raw Data to League Standings

## 📊 Project Overview

This project builds the complete Premier League 2024/25 league table from raw match data using R. No pre-calculated points or standings — everything is derived from match results.

**Data source:** [football-data.co.uk](https://www.football-data.co.uk/mmz4281/2425/E0.csv)

**Rows:** 380 matches

**Output:** Complete league table + insights report

---

## 🚀 Live Reports

| Report | Link |
|--------|------|
| **League Table Report** | [(https://rpubs.com/ThomasChula/1425057)]

---


---

## 🔧 How to Run

### Prerequisites

Install R and RStudio, then install required packages:

```r
install.packages(c(
  "tidyverse",
  "knitr",
  "kableExtra",
  "DT",
  "rmarkdown"
))

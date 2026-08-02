# Dashboards Portfolio

A collection of BI dashboards built in Tableau and Power BI, covering operational, sales, and logistics analytics across different datasets.

## 📊 Tableau — [see full details →](tableau/README.md)

| Dashboard | Live link |
|---|---|
| ✈️ Flight Delays and Cancellations | [Open on Tableau Public](https://public.tableau.com/app/profile/yehra/viz/flight-delays-analysis/Airlines) |
| 🛒 EU Superstore Orders Dashboard | [Open on Tableau Public](https://public.tableau.com/app/profile/yehra/viz/eu-superstore-orders-dashboard/EUSuperstoreOrdersDashboard) |

## 📈 Power BI — [see full details →](power-bi/README.md)

| Dashboard | Access |
|---|---|
| 🛍️ E-Commerce Operations Dashboard (6 pages: Sales, Logistics, Payments, Reviews, Sales Localisation) | [.pbix download](power-bi/ecommerce-operations-dashboard.pbix) + screenshots |

## 📁 Repository Structure

```
dashboards-portfolio/
├── README.md
├── tableau/
│   ├── README.md
│   ├── flight-delays-analysis.twbx
│   ├── eu-superstore-orders-dashboard.twbx
│   └── screenshots/
└── power-bi/
    ├── README.md
    ├── ecommerce-operations-dashboard.pbix
    └── screenshots/
```

## 🛠 Tech Stack

`Tableau Desktop` · `Tableau Public` · `Power BI Desktop` · `Git LFS`

## 📌 A note on Git LFS

The Power BI `.pbix` file (~38 MB) is tracked via [Git LFS](https://git-lfs.com/) rather than committed directly, to keep the repository lightweight. If cloning this repo to download the file itself (not required just to view the screenshots/README):

```bash
git lfs install
git clone https://github.com/YeHra/dashboards-portfolio.git
```

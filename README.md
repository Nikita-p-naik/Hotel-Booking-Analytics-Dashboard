# Hotel Booking Analytics Dashboard

An interactive Tableau dashboard analyzing 87K+ hotel bookings — tracking booking trends, ADR (Average Daily Rate), cancellation behavior, and market segment performance across 177 countries.

## 📊 Overview

This project visualizes hotel booking data to surface insights around seasonal demand, pricing trends, cancellation risk, and guest acquisition channels. Built entirely in **Tableau** with a multi-sheet dashboard combining KPIs, trend lines, bar charts, and a geographic scatter plot.

## 🖥️ Dashboard Components

- **KPI Summary** — Total Bookings, Average Daily Rate, Avg Length of Stay, Cancellation Rate, Avg Lead Days, Total Country, Repeat Guest %
- **Monthly Booking Trend** — Bookings by month, highlighting peak season in July–August
- **Monthly ADR Trend** — Average Daily Rate trend across the year, peaking in August
- **Booking by Marketing Segment** — Volume breakdown by channel (Online TA, Offline TA/TO, Direct, Groups, Corporate, Complementary, Aviation, Undefined)
- **Cancellation Rate by Customer Type** — Cancellation % across Transient, Transient-Party, Contract, and Group customers
- **Top 10 Countries - Booking Volume vs. ADR** — Scatter plot comparing booking volume and average daily rate by country
- **Lead Time Distribution** — Bookings bucketed by lead time (0–30 days through 360+ days)
- **ADR by Market Segment** — Average Daily Rate compared across each marketing/booking segment

## 🔑 Key Metrics Tracked

- Total Bookings: 87,396
- Average Daily Rate: 106.3
- Avg Length of Stay: 3.631 nights
- Cancellation Rate: 27.5%
- Avg Lead Days: 79.89
- Total Countries: 177
- Repeat Guest %: 3.91%

## 🗂️ Data Source

Hotel booking-level dataset including booking date, arrival month, lead time, ADR, length of stay, cancellation status, customer type, marketing segment, and guest country.

## 🛠️ Tools Used

- **Tableau Desktop / Public** — data modeling, calculated fields, and dashboard design

## 📁 Repository Contents

| File | Description |
|------|--------------|
| `*.twbx` | Packaged Tableau workbook containing the full dashboard and underlying data |
| `README.md` | Project documentation (this file) |

## 🚀 How to Use

1. Clone or download this repository.
2. Open the `.twbx` file in **Tableau Desktop** or **Tableau Public** (free download from Tableau).
3. Explore individual sheet tabs or the combined dashboard view.
4. Hover over charts for tooltip-level detail; click marks to cross-filter across the dashboard.

## 📌 Notes

- Figures are based on the underlying hotel booking dataset and are intended for analytical/portfolio purposes.
- Add screenshots of the dashboard to a `/screenshots` folder for quick preview on GitHub.

## 📄 License

This project is open for educational and portfolio use.

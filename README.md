# PhonePe_Dashboard

Now I have a complete, deep picture of all the data. Here are the perfect answers:

---

## 1. 🏷️ Project Title

**PhonePe 2024 Performance Dashboard | Payments, Loans, Insurance & User Analytics**

---

## 2. 📋 Purpose

This dashboard delivers a full-spectrum analytics view of PhonePe's digital financial ecosystem, built on **300,000 transactions** from **107,658 users** across the entire calendar year 2024. It enables product managers, business analysts, and finance teams to monitor transaction volumes and success rates, analyse revenue across four core services (Recharge & Bills, Money Transfer, Loans, and Insurance), identify payment failure patterns, and track user growth trends — enabling data-driven decisions for product improvement, fraud reduction, and business expansion.

---

## 3. 🛠️ Key Technologies Used

- **Microsoft Power BI Desktop** — interactive multi-page dashboard and visual analytics (`.pbix`)
- **Microsoft Excel** — primary data source with 6 structured sheets (`.xlsx`)
- **DAX (Data Analysis Expressions)** — calculated KPIs: total transaction value, success rate %, average transaction amount, failure rate, and service-wise aggregations
- **Power Query (M Language)** — multi-sheet data merging, date/time transformation, relationship modelling between Users and Transactions tables, and data type standardisation

---

## 4. 📦 Data Source

- **Source:** **Kaggle**
- **File:** `Phonepe-Final-Dataset.xlsx`
- **6 Sheets | 300,000 transactions + 107,658 user records**

| Sheet | Records | Key Fields |
|---|---|---|
| `All_Users` | 107,658 | User_ID, Name, Age (18–60), Join_Date (2023–2025) |
| `All_Transactions` | 300,000 | Transaction_ID, Amount (₹20–₹99,999), Service, Service Type, Payment_Status, Date (Jan–Dec 2024) |
| `Recharge_Bills` | 50,000 | Mobile Recharge, DTH, Cable TV, Electricity Bill |
| `Money_Transfer` | 150,000 | To Self Account, To Mobile Number, To QR Code, To UPI ID |
| `Loans` | 50,000 | Gold Loan, Auto Loan, Mutual Fund, Credit Score |
| `Insurance` | 50,000 | Term Life, Health, Car, Bike |

- **Payment Statuses:** Successful (287,993) | Failed (9,980) | Wrong PIN (700) | Server Error (692) | Insufficient Amount (635)
- **Total Successful Transaction Value: ₹333.3 Crore**

---

## 5. ✨ Features of the Dashboard

- **Top-Line KPIs** — Total transactions (3L), total successful value (₹333.3 Cr), overall success rate (96%), and total registered users (107,658) as headline cards
- **Service-wise Revenue Breakdown** — Loans dominate with ₹253.25 Cr, followed by Insurance (₹51.29 Cr), Money Transfer (₹37.82 Cr), and Recharge & Bills (₹5.07 Cr)
- **Transaction Success vs. Failure Analysis** — Visual split of all 5 payment statuses with drill-down into failure reasons: Server Error, Wrong PIN, Insufficient Amount, Wrong Info, Bank Denied
- **Service Type Deep-Dive** — Performance breakdown across all 16 service sub-types including FASTag Recharge, UPI transfers, Gold Loan, Term Life Insurance, and more
- **Money Transfer Channel Analysis** — Comparative view of To UPI ID, To Mobile Number, To QR Code, and To Self Account transfer volumes
- **Loan Portfolio Overview** — Gold Loan, Auto Loan, Mutual Fund, and Credit Score transaction trends and value contributions
- **Insurance Premium Analytics** — Health, Term Life, Car, and Bike insurance premium volumes and success rates
- **Monthly Transaction Trends** — Full 12-month (Jan–Dec 2024) time-series showing seasonal peaks and service-wise growth patterns
- **User Demographics & Growth** — Age distribution (18–60) and user joining trend from 2023–2025 to understand platform adoption
- **Interactive Filters / Slicers** — Dynamic filtering by Service, Service Type, Payment Status, Month, and Age Group for granular drill-down analysis

---

## 6. ✨ Screenshots of the Dashboard

- Home Page: https://github.com/Goutamee/PhonePe_Dashboard/blob/main/1_Home_Page.png
- Insurance Page: https://github.com/Goutamee/PhonePe_Dashboard/blob/main/2_Insurance.png
- Loan Page: https://github.com/Goutamee/PhonePe_Dashboard/blob/main/3_Loans.png
- Transaction Page: https://github.com/Goutamee/PhonePe_Dashboard/blob/main/4_Transactions.png
- Bill Page: https://github.com/Goutamee/PhonePe_Dashboard/blob/main/5_Bills.png

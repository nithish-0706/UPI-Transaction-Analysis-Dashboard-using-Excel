# 📊 UPI Transaction Analysis Dashboard (Excel)

An interactive Excel dashboard that analyses **25,000 UPI transactions** (Jan – Sep 2026) to understand payment trends, app market share, merchant spending, failure patterns and fraud-risk levels.

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?logo=microsoftexcel&logoColor=white)
![Pivot Tables](https://img.shields.io/badge/Feature-Pivot%20Tables-blue)
![Slicers](https://img.shields.io/badge/Feature-Slicers%20%26%20Timeline-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

UPI (Unified Payments Interface) is India's most widely used digital payment system. This project turns raw transaction-level data into an easy-to-read, interactive dashboard so that anyone can quickly answer questions like:

- How many transactions happen every month and what is the total value?
- Which UPI app (PhonePe, Google Pay, Paytm…) is used the most?
- Which merchant categories drive the most spending?
- How often do transactions fail, and why?
- What share of transactions fall under Low / Medium / High risk?

## 🎯 Objectives

1. Clean and organise the raw UPI transaction data.
2. Summarise the data using **Pivot Tables**.
3. Visualise insights with **Pivot Charts**.
4. Build an interactive **Dashboard** with **Slicers** and a **Timeline** filter.
5. Identify failure reasons and risk patterns to support decision-making.

## 🗂️ Workbook Structure

| Sheet | Description |
|-------|-------------|
| `UPI Transactions` | Raw dataset – 25,000 rows × 20 columns |
| `Pivot Table` | 7 pivot tables used as the data source for charts |
| `Dashboard` | Final interactive dashboard with 5 charts, slicers and a date timeline |

## 📋 Dataset Description

**Records:** 25,000 transactions | **Period:** 01 Jan 2026 – 30 Sep 2026 | **Columns:** 20

| Column | Description |
|--------|-------------|
| Transaction Date / Time | When the transaction happened |
| Transaction ID | Unique ID for each transaction |
| Payer VPA / Payee VPA | UPI IDs of sender and receiver |
| Transaction Amount | Amount in ₹ |
| Transaction Type | P2P, P2M or Refund |
| Payment Purpose | Food, Rent, Transfer, Bills, Travel, etc. |
| Merchant Category | Grocery, Food & Dining, Fuel, Electronics, etc. |
| Payer Bank / Payee Bank | Banks involved in the transaction |
| UPI App | PhonePe, Google Pay, Paytm, BHIM, Amazon Pay, Navi, CRED |
| Payment Channel | QR Code, UPI ID, Mobile Number, Contact List, Collect Request |
| Transaction Status | Success / Failed / Pending |
| Failure Reason | Reason for failed or pending transactions |
| Is New Payee | Whether the payee was new (Yes / No) |
| Average Transaction Amount | Payer's average transaction amount |
| Daily Transaction Count | Payer's number of transactions that day |
| Daily Total Transaction Amount | Payer's total spend that day |
| Risk Category | Low / Medium / High |

## 🛠️ Tools & Techniques Used

- **Microsoft Excel**
- Pivot Tables & Pivot Charts
- Slicers (UPI App, Merchant Category, Transaction Status)
- Timeline filter (Transaction Date)
- Data cleaning & formatting
- Dashboard design

## 🔍 Key Insights

- 💰 **Total value processed:** ₹3.25 crore (₹32.53 M) across 25,000 transactions, with an average ticket size of about **₹1,301**.
- ✅ **Success rate:** **95.1%** of transactions succeeded, 3.7% failed and 1.3% stayed pending.
- 📱 **App market share:** **PhonePe (46.1%)** and **Google Pay (35.1%)** together handle over 80% of all transactions.
- 🛒 **Transaction type:** Person-to-Merchant (P2M) makes up **59.9%**, P2P 37.2% and refunds 2.9%.
- 🏪 **Merchant categories:** Grocery and Food & Dining have the highest transaction *counts*, while Electronics has the highest *value* among merchant categories.
- 📅 **Monthly trend:** Monthly volume stays steady at roughly 2,600–2,900 transactions, with **September** recording the highest value (~₹38.9 lakh) and **February** the lowest volume.
- ❌ **Top failure reason:** *Insufficient Funds*, followed by *Transaction Timeout* and *Bank Server Down*.
- ⚠️ **Risk profile:** 67.7% Low, 24.5% Medium and **7.8% High** risk transactions.


## 🚀 How to Use

1. Clone or download this repository.
2. Open `UPI Transaction Analysis.xlsx` in **Microsoft Excel** (2016 or later recommended – slicers and timeline are required).
3. Go to the **Dashboard** sheet.
4. Use the **slicers** and **timeline** to filter by UPI app, merchant category, status or date range – all charts update instantly.

```bash
git clone https://github.com/nithish-0706 
cd https://github.com/nithish-0706/UPI-Transaction-Analysis-Dashboard-using-Excel.git
```

## 📁 Repository Structure

```
├── UPI Transaction Analysis.xlsx   # Main Excel project
├── images/
│   └── dashboard.png               # Dashboard screenshot
└── README.md
```

## 🙋 Author

**Name : Nithish**
📧 nithishjrp@gmail.com · 🔗 [LinkedIn](https://www.linkedin.com/in/nithish-jrp/) · 💻 [GitHub](https://github.com/nithish-0706)

---

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).

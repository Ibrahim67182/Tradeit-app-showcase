<div align="center">

# 🔄 Trade It
### *Manage All Your Trading Transactions — in One App*

> A mobile-first trading management app for small businesses and entrepreneurs who are done with spreadsheets.

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org)


[![Platform](https://img.shields.io/badge/Platform-Android-brightgreen?style=flat-square&logo=android)](https://android.com)
[![Auth](https://img.shields.io/badge/Auth-Google%20OAuth-red?style=flat-square&logo=google)](https://developers.google.com/identity)
[![Export](https://img.shields.io/badge/Export-PDF%20%7C%20Excel-blue?style=flat-square)](https://pub.dev)


[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)](https://vercel.com)
[![DB on DigitalOcean](https://img.shields.io/badge/DB%20on-DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)](https://digitalocean.com)


</div>

---

## 📖 Overview

**Trade It** is a mobile application built for traders, small business owners, and entrepreneurs who need full control over their trading workflow — without expensive accounting software or complex spreadsheets.

From inventory tracking to profit analytics, from recording purchases to generating monthly PDF reports, Trade It brings your entire business into one clean, reliable interface.



📄 [View App Guide & Documentation](./trade-it-guide-doc/tradeit_guide.pdf)


---

## ✨ Features

### 📊 Analytics Dashboard
Get a real-time birds-eye view of your business performance — Total Net Profit, Gross Profit, Total Sales, Total Purchases, and Operational Activity all in one place.

> 📸 See `/screenshots/dashboard/` for UI previews

---

### 📦 Inventory Tracking
Real-time stock levels updated automatically after every purchase or sale. Know exactly what you have at any moment.

> 📸 See `/screenshots/inventory/` for UI previews

---

### 🔁 Transaction Management
Record purchases from suppliers and sales to customers with smart auto-calculation — fill any 2 of 3 fields (Quantity, Rate, Total) and the third is computed for you.


> 📸 See `/screenshots/transactions/` and `/screenshots/transactions-history` for UI previews 


---

### 👥 Contact Management
Maintain a full directory of Customers and Suppliers, each linked directly to their transactions.

> 📸 See `/screenshots/customers/` for Customers UI previews
> 📸 See `/screenshots/suppliers/` for Suppliers UI previews
> 📸 See `/screenshots/products/`  for Products UI previews

---

### 💸 Expense Logging
Track business costs beyond product purchases — rent, transport, salaries, utilities. Expenses flow directly into Net Profit calculations.

> 📸 See `/screenshots/expenses/` for UI previews

---

### 📈 Reports & Exports
Generate **Product Reports** (all-time performance per product) and **Monthly Reports** (full month breakdown with net profit). Export to **Excel (.xlsx)** or **PDF** with a single tap.

> 📸 See `/screenshots/reports/` for UI previews

---

### 🌍 Multi-Currency Support
Select any world currency and all amounts across the entire app update instantly. Clean display, no recalculation of historical values.

> 📸 See `/screenshots/settings/` for UI previews

---


## 🛠️ Tech Stack

### 📱 Mobile App
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

### 🌐 Backend & Database
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)

### 🔐 Auth & Integrations
![Google OAuth](https://img.shields.io/badge/Google_OAuth-4285F4?style=for-the-badge&logo=google&logoColor=white)

### ☁️ Deployment
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white)



---

## ⚙️ Key Technical Highlights

- **Google OAuth** — Secure, passwordless authentication with full cross-device data persistence
- **Real-time Inventory** — Stock levels derived live from transaction history, never stored statically
- **Business Rule Enforcement** — No negative inventory, date validation, cascaded deletion rules enforced at the data layer
- **Auto-Calculation** — Fill any 2 of 3 transaction fields; the third is computed automatically
- **Export Engine** — Excel `.xlsx` exports for transaction history and product reports; PDF exports for monthly reports
- **Multi-Currency** — Instant display-layer currency switching across all screens
- **Full CRUD** — Complete create, read, update, delete lifecycle for Products, Customers, Suppliers, Transactions, and Expenses

---

## 📐 Business Rules at a Glance

| Scenario | Rule |
|---|---|
| Creating a Purchase | Must select Supplier + Product first |
| Creating a Sale | Must select Customer + Product first |
| First Sale of a Product | Requires at least one Purchase recorded first |
| Sale Date | Cannot be earlier than the first purchase date |
| Out of Stock | Sale is blocked — no negative inventory |
| Deleting a Purchase | Delete all related Sales first |
| Deleting a Product | Delete all related Transactions first |
| Transaction Fields | Fill any 2 of 3 — third is auto-calculated |

---

## 🎯 Ideal For

- Small and medium traders managing physical product inventory
- Wholesale buyers who resell retail
- Business owners wanting a mobile-first alternative to spreadsheets
- Anyone needing per-product and per-month performance tracking

---

## 👤 Author

**Ibrahim Junaid**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ibrahim-junaid-690b13288/)

---

<div align="center">

**Trade It — Secure · Fast · Reliable**
*Manage All Your Trading Transactions*

</div>

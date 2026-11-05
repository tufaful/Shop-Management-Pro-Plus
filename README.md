# Shop Management Pro 🛍️

[![GitHub Profile](https://img.shields.io/badge/Developer-Tufaful%20Ambia-blue?style=for-the-badge&logo=github)](https://github.com/tufaful)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Offline-First](https://img.shields.io/badge/Offline--First-100%25-brightgreen?style=for-the-badge)](#-technical-stack--architecture)
[![Bilingual](https://img.shields.io/badge/Bilingual-English%20%7C%20Bengali-orange?style=for-the-badge)](#-bilingual-localization-engine-english--bengali)

**Shop Management Pro** is a high-performance, offline-first, all-in-one Enterprise ERP, Business Management, and Point of Sale (POS) solution. Built for speed, operational precision, and data privacy, it runs as a 100% standalone single-file HTML web application powered by browser-native IndexedDB storage. Your business operations, product inventory, billing transactions, customer due ledgers, courier COD tracking, fixed assets valuation, staff payroll, damage loss logs, and financial accounting remain completely local, private, and fully functional without requiring an active internet connection.

---

## 📑 Table of Contents
- [🚀 Quick Links](#-quick-links)
- [✨ Core Enterprise Modules](#-core-enterprise-modules)
  - [🛒 Point of Sale (POS) & Fast Billing](#-point-of-sale-pos--fast-billing)
  - [📊 Enterprise Business Reports Hub (12 Sub-Tabs)](#-enterprise-business-reports-hub-12-sub-tabs)
  - [📂 Universal Category & Brand Hub](#-universal-category--brand-hub)
  - [🚚 Courier Partners & COD Analytics](#-courier-partners--cod-analytics)
  - [🏢 Fixed Assets & Valuation Engine](#-fixed-assets--valuation-engine)
  - [⚠️ Damage & Loss Write-off Register](#️-damage--loss-write-off-register)
  - [👔 HR, Staff Payroll & Leave Register](#-hr-staff-payroll--leave-register)
  - [🏛️ Govt Sales Tax & VAT Ledger](#️-govt-sales-tax--vat-ledger)
  - [👥 CRM, Customer Due Ledgers & WhatsApp Reminders](#-crm-customer-due-ledgers--whatsapp-reminders)
  - [🔒 Security, Lock Date & Vault Backup](#-security-lock-date--vault-backup)
- [📋 Complete Module Directory (35+ Modules)](#-complete-module-directory-35-modules)
- [🛠 Technical Stack & Architecture](#-technical-stack--architecture)
- [📥 Installation & Deployment](#-installation--deployment)
- [📱 Mobile App Support (APK & PWA)](#-mobile-app-support-apk--pwa)
- [📖 Keyboard Shortcuts Guide](#-keyboard-shortcuts-guide)
- [🤝 Developer Contact & Support](#-developer-contact--support)
- [🛡 License](#-license)

---

## 🚀 Quick Links
- **Developer GitHub:** [https://github.com/tufaful](https://github.com/tufaful)
- **Repository:** [https://github.com/tufaful/Shop-Management-Pro-Plus](https://github.com/tufaful/Shop-Management-Pro-Plus)

---

## ✨ Core Enterprise Modules

### 🛒 Point of Sale (POS) & Fast Billing
- **Lightning-Fast Checkout:** Rapid product addition via barcode scanning or real-time catalog search.
- **Visual Product Grid & Filter Tabs:** Filter items instantly by category with stock level indicators.
- **Cashier Hotkeys:** Keyboard-driven counter operations (`F2`, `F4`, `F8`).
- **Flexible Split Payments:** Split tender across Cash, Bank Transfer, Mobile Financial Services (bKash, Nagad, Rocket, Upay), and Partial/Credit Due.
- **Multi-Format Receipt Printing:** 
  - ESC/POS Thermal 80mm & 58mm receipts with auto-cutter alignment.
  - Standard A4 and A5 printable invoices and cash memos.
- **Held Carts (Suspended Sales):** Park active customer carts with custom notes and resume them anytime.

### 📊 Enterprise Business Reports Hub (12 Sub-Tabs)
1. **Overview & P&L Statement:** Gross sales revenue, Cost of Goods Sold (COGS), Operating Expenses, Net Profit, and Gross Margin %.
2. **Sales Report:** Filtered sales invoices by date range and payment tender.
3. **Purchases & Vendor Ledger:** Supplier procurement invoices, paid amounts, and accounts payable.
4. **Expenses & Operating Income:** Store overhead expenses and secondary income streams.
5. **Customer Dues & Receivables:** Outstanding customer balances with 1-click WhatsApp reminder links.
6. **Product Performance Analysis:** Sales volume, gross profit per SKU, and margin % meters.
7. **Category & Brand Analytics:** Comparative sales performance across Product Categories and Brands.
8. **Courier & COD Analytics:** Delivery parcel volume, collected COD funds, and shipping charges.
9. **Fixed Assets Valuation:** Equipment/furniture asset listing, original purchase costs, and market valuation.
10. **Damage & Loss Write-offs:** Incident logs, damaged inventory write-offs, and total financial loss.
11. **HR, Staff Payroll & Leaves:** Monthly staff base salary budget, salary payments, and leave register.
12. **Govt Sales Tax & VAT Ledger:** Official sales VAT tracking and treasury deposit vouchers.
- **Custom Date Filters:** Quick pills (Today, Yesterday, 7 Days, This Month, Last Month, This Year, All Time, Custom Range).
- **Export & Print:** 1-Click Excel/CSV exports for all 12 sub-tabs with sanitized cells.

### 📂 Universal Category & Brand Hub
- **Responsive Category Dropdown Filter:** Instant mobile-friendly dropdown select for filtering product categories, brands, couriers, expenses, assets, damages, and leaves.
- **Bilingual Summary Cards:** Real-time active services, units, vouchers, and total expense counters.
- **Cleaned Data Architecture:** Complete removal of obsolete `mfs_wallet` category to keep store schemas pristine.

### 🚚 Courier Partners & COD Analytics
- **Courier Directory:** Manage courier partners (Steadfast, Pathao, RedX, Paperfly, Sundarban, SA Paribahan, etc.).
- **Parcel Shipment Tracking:** Link sales invoices to tracking numbers and shipping statuses.
- **COD Reconciliation:** Track collected Cash on Delivery (COD) funds vs. courier delivery charges.

### 🏢 Fixed Assets & Valuation Engine
- **Asset Registration:** Record shop computers, barcode scanners, thermal printers, furniture, and lighting assets.
- **Market Valuation & Depreciation:** Track original procurement cost, depreciation, and current market value.

### ⚠️ Damage & Loss Write-off Register
- **Inventory Write-offs:** Log broken, expired, or damaged products with damage reason tags.
- **Auto Stock Deduction:** Automatically reduces inventory stock counts while logging financial write-off loss.

### 👔 HR, Staff Payroll & Leave Register
- **Employee Roster:** Store employee profiles, designations, and base monthly salaries.
- **Salary Disbursement:** Process monthly salary disbursements and log cash outflows.
- **Staff Leave Log:** Track employee casual, sick, and annual leave requests and approvals.

### 🏛️ Govt Sales Tax & VAT Ledger
- **VAT Collection Sync:** Automatically captures sales VAT from invoices into official ledger format.
- **Treasury Deposits:** Record government tax authority treasury deposits with challan numbers.

### 👥 CRM, Customer Due Ledgers & WhatsApp Reminders
- **Customer Due Ledger:** Full transaction history, outstanding balances, and collection slips.
- **1-Click WhatsApp Reminders:** Generate instant personalized due reminder links for customer chat.

### 🔒 Security, Lock Date & Vault Backup
- **Master PIN & Role Access:** Secure administrative screens with Master PIN locks.
- **Lock Date Protection:** Block historical transaction editing/deletion before a specified date.
- **Triple-Format Backup:** JSON Plain Backup, Encrypted AES-256 Vault Backup, and Modular CSV Exports.

---

## 📋 Complete Module Directory (35+ Modules)

| Category | Included Modules |
| :--- | :--- |
| **Sales & Billing** | 🛒 POS Terminal · 🧾 Sales Invoices · ↩️ Sales Returns · 🚚 Delivery Hub · ⏳ Held Carts |
| **Inventory & Stock** | 📦 Products Catalog · 📜 Stock History · 🏷️ Barcode Labels · ⏰ Expiry Alerts · ⚖️ Measurement Units · 📂 Categories |
| **Procurement & Supply** | 📥 Purchases · 📤 Purchase Returns · 🏢 Supplier Directory · 📑 Supplier Ledgers |
| **Customers & Dues** | 👥 Customer Directory · 📒 Customer Due Ledger · 💬 WhatsApp Reminders · 💳 Collection Slips |
| **Enterprise Operations** | 🚚 Courier & COD · 🏢 Fixed Assets · ⚠️ Damage Write-offs · 👔 HR & Payroll · 🏖️ Staff Leaves |
| **Accounts & Finance** | 💵 Cash Book · 🏦 Bank Accounts · 📉 Daily Cash Closing · 💸 Expenses · 💰 Other Income · 🏛️ VAT Ledger |
| **Analytics & Reports** | 📊 12-Subtab Business Reports · 📈 Profit & Loss · 🏷️ Inventory Valuation · 🛡️ Audit & Compliance |
| **System & Security** | 🔒 PIN & Role Security · 🔒 Lock Date · ♻️ Recycle Bin · 💾 Backup & Vault · ⚙️ Settings |

---

## 🛠 Technical Stack & Architecture
- **Frontend Core:** Pure Vanilla TypeScript / JavaScript with reactive DOM rendering.
- **Styling:** Utility styling with Dark & Light theme toggling and zero horizontal overflow.
- **Persistence Layer:** Client-side IndexedDB engine for offline-first performance.
- **Print Engine:** CSS print sheets forESC/POS thermal printers (80mm / 58mm) and standard A4/A5 printers.
- **Distribution:** Standalone Single File Application (`index.html`).

---

## 📥 Installation & Deployment

### 1. Local Offline Usage
1. Download `index.html`.
2. Open in Chrome, Edge, Firefox, Safari, or Brave.
3. Ready to use offline immediately.

### 2. Cloud Deployment
- Host on **GitHub Pages**, **Netlify**, or **Vercel** by deploying `index.html`.

---

## 📱 Mobile App Support (APK & PWA)
- **Progressive Web App (PWA):** Tap **"Add to Home Screen"** in mobile browser.
- **Android APK:** Wrap `index.html` using Capacitor or WebToApp builder.

---

## 📖 Keyboard Shortcuts Guide

| Shortcut | Action | Description |
| :--- | :--- | :--- |
| **`F2`** | Product Search | Focus POS product search |
| **`F4`** | Customer Lookup | Focus customer combobox |
| **`F8`** | Complete Sale | Trigger quick checkout dialog |
| **`Alt + M`** | All Feature | Open left navigation drawer |
| **`Alt + L`** | Language Switch | Toggle between English 🇬🇧 and Bengali (বাংলা) 🇧🇩 |
| **`ESC`** | Close Modal | Dismiss dialog or popup |

---

## 🤝 Developer Contact & Support
- **Developer:** Tufaful Ambia
- **GitHub:** [https://github.com/tufaful](https://github.com/tufaful)
- **Email:** [ambia.inbox@gmail.com](mailto:ambia.inbox@gmail.com)
- **WhatsApp:** [https://wa.me/tufaful](https://wa.me/tufaful)

---

## 🛡 License
Distributed under the **[MIT License](LICENSE)**.

```
Copyright (c) 2026 Tufaful Ambia
```

Developed with ❤️ by **Tufaful Ambia**.

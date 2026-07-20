# 🛢️ Oil Kadai — Smart Billing & Point of Sale (POS) System

A lightweight, fully responsive, single-file web-based Point of Sale (POS) and billing application designed for retail shops. It features live sales analytics, dynamic catalog management, multi-currency support, custom payment gateway configurations, and local data persistence.

Live Web App Link: [https://gokul11salem.github.io/oilkadai/](https://gokul11salem.github.io/oilkadai/)

---

## 🌟 Key Features

* **📊 Real-time Dashboard**: Live metrics tracking today's sales, monthly revenue, order counts, and a breakdown of recent transactions.
* **🛒 Interactive Shop & Cart**: Categorized catalog with quick-add options, quantity adjusters, and a sticky floating cart summary.
* **🌐 Multi-Currency Support**: Supports global currency contexts (MYR, INR, SGD, USD, AED, SAR) with flags and dynamic conversions.
* **📜 Audit History & CSV Export**: 30-day transaction logs with itemized breakdowns and a one-click CSV export option for bookkeeping.
* **🔒 PIN-Protected Admin Panel**: Secure master control screen (Default PIN: `1234`) to manage inventory, update pricing, change shop branding, and configure banking setups.
* **💳 Dynamic Payment Terminals**: Custom QR code image support alongside international bank routing fields (SWIFT/BIC, IBAN, IFSC).
* **💾 Local Data Persistence**: Fully client-side storage implementation using standard browser `localStorage` to ensure data survives page refreshes without needing a backend server.

---

## 🛠️ Technical Stack & Implementation Details

* **Frontend**: HTML5, CSS3 (CSS Custom Properties & Flexbox/Grid Layouts)
* **Scripting**: Vanilla JavaScript (ES6+)
* **Data Storage**: Browser `localStorage` API (Zero backend/database dependency)
* **Styling & Fonts**: Google Fonts (`Poppins`, `Inter`) with dynamic UI styling for mobile & desktop viewports
* **Architecture**: Single Page Application (SPA) inside a single `index.html` file

---

## 🚀 Step-by-Step User Guide

### 1. Launching the App
Simply open the live URL: [https://gokul11salem.github.io/oilkadai/](https://gokul11salem.github.io/oilkadai/) on any modern desktop browser, tablet, or smartphone.

### 2. Processing a New Sale
1. Click on the **Shop** tab from the top navigation bar.
2. Select the desired item from the product grid by clicking **Add to Cart**.
3. Adjust product quantities using the `+` or `−` buttons.
4. Click the floating bottom cart bar (**🛒 Cart**) to review the **Order Summary**.
5. Click **Proceed to Payment** to view the customer payment terminal (QR code and bank transfer details).
6. Once payment is received, click **✓ Payment Received — Complete Sale**. The transaction will be saved, and you will be redirected to the dashboard.

### 3. Viewing Analytics & Exporting Reports
1. Go to the **Dashboard** tab to view daily and monthly sales metrics.
2. Navigate to the **History** tab to review all completed orders from the past 30 days.
3. Click **⬇ Download CSV Report** to download a spreadsheet file of your sales history.

### 4. Managing Admin Settings
1. Click on the **Settings** tab.
2. Enter the default PIN: `1234` on the numeric keypad to unlock the panel.
3. **Customize Branding**: Update the shop name, slogan, or upload a custom logo image.
4. **Manage Inventory**: Add new products, update prices, change currency tags, edit product photos, or remove items.
5. **Configure Payments**: Upload a custom payment QR code image or fill in your bank details (Account number, Bank name, SWIFT/IBAN).
6. **Change PIN**: Update your security PIN for future logins.

---

## 👨‍💻 Local Development & Deployment

Since the entire application resides in a single `index.html` file, no build tools or package managers (like npm or webpack) are required.

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/gokul11salem/oilkadai.git](https://github.com/gokul11salem/oilkadai.git)

   Run locally:
2. Open index.html directly in any web browser.

### 📄 License
This project is open-source and free to use for personal or commercial retail operations.

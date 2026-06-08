# 📱 MeUIPay - Digital Banking Transfer History Portal
> ປະຫວັດການໂອນເງິນ - Digital Banking

MeUIPay is a premium, high-fidelity single-page web application that simulates a digital banking transfer history portal. Built specifically for Lao language environments, it offers a visual dashboard for viewing, searching, filtering, and simulating various types of money transfers.

---

## ✨ Features & Capabilities

The application provides a comprehensive tabbed interface that mirrors modern mobile/desktop banking applications:

### 1. 📂 Transaction History Tabs
*   **General History (ປະຫວັດທຸລະກຳທົ່ວໄປ):** View standard one-to-one transfers with complete sender, receiver, bank info, and CBS reference numbers.
*   **Multi-Payment History (ປະຫວັດຈ່າຍເງິນຫຼາຍ):** Track batch/bulk transfers (e.g., salaries or supplier payouts). Shows total recipients, successful/failed breakdowns, and detailed nested sub-lists for each recipient.
*   **Scheduled Transfers (ປະຫວັດຕັ້ງເວລາໂອນ):** Monitor recurring or set-time transfers (e.g., office rent, savings plans, monthly insurance) with customized execution dates (e.g., "Every 1st of the month").

### 2. 📊 Dynamic Analytics Dashboard
*   Interactive summary cards at the top dynamically calculate and display:
    *   **Total Amount (ຍອດລວມທຸລະກຳ):** Cumulative cash flow across all matching transactions.
    *   **Success Amount (ທຸລະກຳສຳເລັດ):** Sum of successful payments.
    *   **Failed Amount (ທຸລະກຳລົ້ມເຫຼວ):** Sum of failed transactions (with prominent red indicator).
*   Counters update dynamically as search queries or dropdown filters are applied.

### 3. 🔍 Advanced Filtering & Search
*   **Bank/Account Filter:** Filter records by financial institution (e.g., BCEL, LDB, APB).
*   **Transaction Category:** Toggle between all, internal, or external transfers.
*   **Interactive Search Bar:** Instantly query by transaction ID, descriptions, batch names, account numbers, or sender details.
*   **Date Range Selectors:** Filter history between custom dates.

### 4. 🎛️ Live Transfer Simulator (Drawer Overlay)
*   An interactive sliding sidebar panel allows you to simulate and add new records on-the-fly:
    *   Add new individual general payments.
    *   Design multi-payment batches with custom row entries, name inputs, and success/fail statuses.
    *   Create future scheduled items.
*   Submitted entries immediately update the main lists, transaction details, and analytics widgets.

### 5. 📑 Interactive Actions
*   Simulated PDF downloads and transaction certificate extractions with modern pop-up toast alerts.

---

## 🎨 Design System & Aesthetics

*   **Color Palette:** Built with premium, tailored CSS variable tokens centering on a flagship **Primary Teal** (`#0b847c`), soft background slate, and status colors (emerald for success, red for failures, and gold accents).
*   **Typography:** Beautiful dual-font system featuring **Noto Sans Lao** for crisp Lao language display and **Inter** for clean numerical and English content.
*   **Micro-Animations:** Fluid, cubic-bezier transitions on hover states, tab switching, and button clicks, including modal slide-ins.
*   **Responsive Layout:** Fully compatible across modern desktop screens, tablets, and mobile devices.

---

## 🛠️ Technology Stack

The project values ease of deployment and lightweight speed:
1.  **HTML5:** Structured semantic markup.
2.  **Vanilla CSS:** Clean modern styling using CSS Variables, custom scrollbars, and flexbox/grid layouts.
3.  **Vanilla JavaScript (ES6+):** Pure client-side logic for filtering, search, dynamic HTML generation, stats calculations, and drawer simulation without external frameworks or dependencies.

---

## 🚀 Getting Started

Since the app has no dependencies or compilation steps, you can open and run it instantly:

### Method 1: Direct File Open
Simply double-click `index.html` or open it directly in any web browser (Chrome, Edge, Safari, Firefox).

### Method 2: Local Web Server
For a better development experience (supporting live-reloads), run a quick local server.

Using Python:
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000`.

Using Node.js:
```bash
npx serve .
```
Then navigate to `http://localhost:3000` (or the port specified).

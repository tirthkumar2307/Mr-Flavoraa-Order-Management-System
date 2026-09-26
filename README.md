# 🍔 Mr Flavoraa — Order Management App

A lightweight, offline-first order management web app built for **Mr Flavoraa**, a quick-service food outlet. It helps you take orders, track preparation status, manage cancellations, and generate daily sales reports — all from a mobile-friendly interface that works entirely in the browser.

No backend. No login. No internet required after the first load. Just open and start taking orders.

---

## ✨ Features

### 📋 Order Taking
- **Full menu with categories** — Dosa, Waffles, Bun Samosa, Pizza & Garlic Bread, Toast, Golden Batons, Mexican Special, Gujarati Snacks, and Beverages.
- **Variant pricing** — Items like Dosa (Oil / Butter) and Waffles (Half Moon / Full Moon) support two price points per item.
- **Custom pricing** — Water Bottle and similar items accept a manually entered price (e.g., MRP).
- **Live cart** — Add, increase, or decrease quantities. The cart bar shows a running total in ₹.

### 🟡 Active Order Tracking
- Each order displays all items with **tap-to-check readiness**.
- A **"ALL ITEMS READY"** flag appears when every item is marked done.
- The **Complete** button only activates once all items are checked off.
- Cancel any active order with a confirmation dialog (kept in history, not deleted).

### ✅ Completed & ❌ Cancelled Orders
- Separate tabs for completed and cancelled orders, sorted by latest activity.
- Full item breakdown and total for completed orders.

### 📊 Daily Report
- Today's total orders, completed, cancelled, and active counts.
- Total sales for the day.
- **Top 5 most ordered items** based on completed orders.
- **Download today's data as CSV** for accounting or record-keeping.

### ☰ More Menu
- Order history grouped by date, with order count and sales per day.
- **Export full backup (JSON)** — save all your order data anytime.
- **Clear all data** — permanently wipe all stored orders (with confirmation).

### 🎨 Design & UX
- Mobile-first, max-width 480px layout — looks great on phones.
- **Dark mode** support (follows system preference).
- Safe-area insets for notched devices (iPhone, etc.).
- Smooth screen transitions and toast notifications.
- Works **completely offline** after first load.
- All data stored in **localStorage** — nothing leaves your device.

---

## 🛠️ Tech Stack

- **HTML5** — single file, no build step
- **CSS3** — custom properties, flexbox, grid, safe-area insets
- **Vanilla JavaScript** — no frameworks, no dependencies
- **localStorage** — persistent client-side data storage
- **Google Fonts** — Archivo Black & Inter

---

## 🚀 Getting Started

### Option 1: Just open it
1. Download `index.html` (or the HTML file from this repo).
2. Double-click to open it in any modern browser.
3. Start taking orders.

### Option 2: Host it (recommended)
Since it's a single static HTML file, you can host it anywhere:
- **GitHub Pages** — push the file, enable Pages in repo settings.
- **Netlify / Vercel** — drag and drop the file.
- **Any static host** — just upload the HTML.

### Option 3: Add to home screen (best for daily use)
1. Open the app in Chrome (Android) or Safari (iOS).
2. Tap **"Add to Home Screen"**.
3. It will behave like a native app — full screen, offline, one-tap access.

---

## 📁 File Structure

```
mr-flavoraa/
├── index.html      # The entire app (HTML + CSS + JS)
└── README.md       # This file
```

Yes, it's really just one file. That's the point.

---

## 📖 How to Use

### Taking an Order
1. Tap **➕ NEW ORDER** (or the **New** tab).
2. Enter the customer's name.
3. Pick a category, then tap **+** to add items to the cart.
4. For variant items (Dosa, Waffles, Coldrinks), set the quantity for the specific variant.
5. For custom-price items (Water Bottle), enter the price first.
6. Tap **SAVE ORDER**.

### Preparing an Order
1. Go to the **Active** tab.
2. Tap the checkbox next to each item as it gets prepared.
3. Once every item is checked, tap **✓ Complete**.
4. To cancel, tap **❌ Cancel** and confirm.

### Generating a Report
1. Go to the **Daily Report** tab.
2. Review today's numbers and top items.
3. Tap **📥 DOWNLOAD TODAY'S DATA (CSV)** to export.

### Backing Up Data
1. Go to **More** → **Export backup (JSON)**.
2. Save the file somewhere safe. You can restore by manually importing (future feature).

---

## 💾 Data & Privacy

- **All data is stored locally** in your browser's `localStorage`.
- **Nothing is sent to any server.** No analytics, no tracking, no accounts.
- **Clearing browser data will erase orders** — use the JSON backup regularly.
- The CSV export is generated entirely on-device.

---

## 🗺️ Roadmap / Ideas

- [ ] Import backup (JSON restore)
- [ ] Print-friendly order tickets
- [ ] Multiple staff accounts
- [ ] Cloud sync (optional)
- [ ] Sales trend charts (weekly / monthly)
- [ ] Custom menu editor
- [ ] PWA installable with service worker

---

## 🤝 Contributing

This is a small, focused project. If you'd like to improve it:

1. Fork the repo.
2. Make your changes in `index.html`.
3. Test on mobile and desktop.
4. Open a pull request with a clear description.

Please keep the "single file, no dependencies" philosophy intact.

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 👨‍🍳 About Mr Flavoraa

**Mr Flavoraa** serves fresh dosas, waffles, bun samosas, pizzas, toasts, fries, Mexican specials, Gujarati snacks, and beverages. This app was built to make daily order management fast, simple, and reliable — even without an internet connection.

---

**Built with ❤️ for Mr Flavoraa.**
```
⭐ If this helped you, consider starring the repo!
```

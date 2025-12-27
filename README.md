# Restaurant Menu App 🍽️

**A static HTML/CSS restaurant menu web app** showcasing meals, details pages, and simple order flows that navigate to per-item thank-you pages.

## 🔧 Features

- Clear menu pages (starters, main courses, desserts, beverages). ✅
- Individual meal detail pages with price, nutritions, extras, notes box and quantity selection. ✅
- Order form on each meal page that routes to a meal-specific thank-you page. ✅
- Responsive layout with Google Fonts and Font Awesome icons. 💅

## 🗂️ Files & Structure

Key files:
- `index.html` — home / menu
- detail pages (examples): `beef-samoosas.html`, `milk-tart.html`, `vetkoek-bites.html`, `grilled-chicken-pap.html`, `softdrinks.html`, etc.
- `order-thank-you-<meal>.html` — per-meal thank-you pages (e.g., `order-thank-you-beef-samoosas.html`)
- `style.css` — global styles
- `images/` — images used across pages

## 💡 How it works

1. Open `index.html` in your browser.
2. Navigate to any meal's detail page.
3. Select extras, add notes, choose quantity and click **Place Order**.
4. The form redirects you to the corresponding `order-thank-you-<meal>.html` page which displays a static summary.

> Note: This is a static site — form submissions are handled by simple redirects to static thank-you pages (no server-side processing). To capture actual order data you'd add JavaScript (local state or POST to a server/API).

## ✅ Local Testing

- Clone the repo and open `index.html` in your browser.
- Click through a few meal pages and press **Place Order** to verify the redirect lands on the appropriate `order-thank-you-*` file.

## ✍️ Contributing

- Feel free to add more meals, tweak `style.css`, or add a simple JavaScript file to pass form data to the thank-you pages.



Tshabzel — Luxury Fashion (Simple Ordering Frontend)

Overview
- Fashion brand website developed by Mobi Flex

Files
- `tshabzel.html` — Main page with order form.
- `tshabzel.css` — Simple luxury-looking styles.
- `tshabzel.js` — Builds a WhatsApp message and opens WhatsApp Web / App via `wa.me` link.

How it works
- User fills the form and clicks "Order via WhatsApp".
- The page opens WhatsApp (Web or mobile) with a pre-filled message containing the order details addressed to `+256786722322`.

Run locally
- Option A: Open `tshabzel.html` directly in your browser.
- Option B: Run a simple local server (recommended to avoid any browser file restrictions):

PowerShell (Windows):

```powershell
# from project root (c:\Users\HP Laptop 15\Desktop\tshabzel)
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

Notes & Next Steps
- This is a static frontend. For order persistence, confirmation flows or payment integration, add a backend service and/or WhatsApp Business API.
- The WhatsApp number is hard-coded to `256786722322`.

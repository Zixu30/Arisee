# ARISEE — Free Fire Top-Up

Clean static website ready for GitHub Pages.

## Checkout flow
1. Select a Diamond pack.
2. Enter Free Fire UID (6–12 digits).
3. Scan the ARISEE QR code and pay.
4. Tap **Payment Done · Complete Order**.
5. WhatsApp is shown only for help/support.

The checkout stores the latest order locally in the buyer's browser. Because this is a static GitHub Pages site, it does not automatically send completed orders to the owner. For automatic owner-side order collection, a backend such as Firebase/Firestore would be required.

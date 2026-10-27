AGRIMARKET GLOBAL — STARTER WEBSITE
====================================

WHAT THIS PACKAGE IS
- A responsive, professionally styled marketplace front-end.
- Product catalogue with search, category/country filters and display-currency selector.
- Seller listing form that adds a product to the current browser session.
- Enquiry preview modal.
- Works as a static website and is suitable for an Android phone browser.

IMPORTANT LIMITATIONS
This is a front-end prototype, not yet a production marketplace. Product uploads are stored only in the current page's memory and are not visible to other users. It has no login, persistent database, image upload storage, admin moderation, checkout, payout splitting, order management, or buyer/seller messaging backend. Currency figures use illustrative fixed rates and are not live FX quotes. Do not accept real payments through this prototype.

HOW TO PREVIEW ON ANDROID
1. Download and extract the ZIP.
2. Open index.html with a browser or use a code editor/preview app that supports local HTML.
3. For external image loading, keep an internet connection.

HOW TO PUBLISH A PUBLIC PREVIEW (FREE HOSTING MAY BE AVAILABLE)
1. Create a GitHub account and a new public repository named agrimarket-global.
2. Upload index.html and README.txt to the repository.
3. Create a Vercel account and import the repository; Vercel should detect a static site.
4. Deploy and test the generated vercel.app URL on phone and desktop.
Official guide: https://vercel.com/docs/deployments
Note: hosting provider terms/pricing may change. A custom domain usually costs extra.

WHAT IS REQUIRED BEFORE ACCEPTING REAL ORDERS
1. Backend/API and database (e.g. managed PostgreSQL) with access rules.
2. Farmer/buyer accounts, password reset, email verification and admin moderation.
3. Private image storage, file-size/type checks and abuse reporting.
4. Server-side payment initialization and webhook verification; never put secret keys in browser code.
5. Order records, refunds/disputes, seller payouts, commission accounting, and audit logs.
6. Terms of service, privacy notice, seller rules, refund policy and contact details.
7. Testing, backups, monitoring, security review and business verification.

INTERNATIONAL CURRENCY / PAYSTACK
Paystack's current official help pages state that Nigerian businesses can request international card payments and may receive USD payouts subject to eligibility and a Zenith Bank USD domiciliary account. International payment activation is not automatic for every business. Fees and business eligibility must be checked in your own dashboard and official docs.
International payments: https://support.paystack.com/en/articles/2130690
API docs: https://paystack.com/docs/api/
Do not assume a marketplace can split payments or pay out many farmers automatically just because a normal checkout works. Confirm marketplace/subaccount/payout support and compliance with the provider before implementing.

NEXT BUILD PHASE
Connect a production backend, secure authentication, product database and protected image storage; then integrate a payment provider after business eligibility and payout design are confirmed. Keep test mode on until full end-to-end testing is complete.

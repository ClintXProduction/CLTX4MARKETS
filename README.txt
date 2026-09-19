# CLTX4 Marketplace

A free, mobile-friendly electronics catalog.

## Quick setup
1. Create a free GitHub account.
2. Create a new public repository, e.g. `cltx4-marketplace`.
3. Upload `index.html`, `style.css`, `app.js`, and `products.js`.
4. In the repository: Settings → Pages → Deploy from branch → `main` / root.
5. Open the GitHub Pages URL shown there.

## Add products
Edit `products.js`. Copy a product object and change:
- id
- name
- price
- category
- image (direct image URL)
- description
- stock

## Change the inquiry button
In `app.js`, edit `makeLink()` to point to your preferred contact service.

For GCash, don't put your password, OTP, or other private account credentials in this site. You can display a payment name/number only if you intentionally want customers to see it.

## Notes
This is a catalog/inquiry site, not a payment processor. It does not automatically collect payments or customer data.


## Configured contact/payment options
- GCash: 09661821176
- PayPal: bracenoclint@gmail.com
- Messenger: Cltx Pros
- Messenger: Clint Pio Manuel XBraceno
- Facebook: Cltx Pros
- TikTok: CLTX4
- Instagram: Clinxk_1

These are displayed in the payment/contact section and included in product/cart inquiries.

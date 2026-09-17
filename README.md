# HardwareHub

Full-stack hardware store portal with:

- Customer storefront and cart
- Checkout and invoice display
- Online-payment status flow
- Bank transfer reference and JPG/PNG/PDF proof upload
- Distance-based transportation estimate
- Admin portal for products and order/payment status
- JSON persistence for local development

## Run locally

```bash
npm install
npm start
```

Open `http://localhost:3000` for the storefront and `http://localhost:3000/admin.html` for the admin portal.

The server must remain running while using the site. Stop it with `Ctrl+C`.

## Production notes

This is launchable as a working MVP. Before taking real payments, add authentication, HTTPS, a production database, server-side payment gateway integration, and transactional email (SMTP/SendGrid). Replace the sample bank details and currency before launch.

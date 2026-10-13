# GENZ-GAMES / NerdyTips

Independent, mobile-first landing page for a football prediction subscription service.

## Current status
- Static frontend prototype only.
- Membership cards: Daily $15, Weekly $200, Monthly $500.
- Bitcoin receiving address is displayed as provided by the operator.
- No database, customer account, payment verification, order storage, automated Telegram delivery, or live PayPal checkout is connected yet.
- The checkout form intentionally does not transmit or store personal information.

## Publish the frontend
In GitHub, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save. GitHub Pages hosts static files only; backend services are required for real subscriptions and payments.

## Before commercial launch
1. Configure a backend/database and secure administrator authentication.
2. Implement server-side order creation and payment verification.
3. Confirm the BTC network, payment amount calculation, confirmations and refund/support policy.
4. Add a supported PayPal workflow only after merchant eligibility and compliance are verified.
5. Implement private Telegram access grants and expiry/removal.
6. Add privacy policy, terms, contact/support and responsible-betting notices.
7. Test the entire flow with small test transactions before accepting customer payments.

Never commit private keys, seed phrases, passwords, API secrets, or service-role keys to this repository. The public BTC receiving address is not a private key.

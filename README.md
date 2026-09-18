# Zipo Earning

A deployment-ready Node.js/Express + SQLite starter for a legitimate earning platform.

## Included
- Registration/login/logout
- Editable profile
- Member dashboard and transaction history
- Mpamba deposit instructions: 0891344290 / Funny Nkhoma
- Deposit reference submission and admin verification
- Airtel Money or Mpamba withdrawal request workflow
- Developer/admin login
- Admin approval/rejection of transactions

## Run
1. Install Node.js 18+.
2. Run `npm install`.
3. Set `SESSION_SECRET` to a strong random secret.
4. Optionally set `DEVELOPER_PASS` instead of using the development default.
5. Run `npm start`.
6. Open `http://localhost:3000`.

For production, use HTTPS, a persistent database, backups, rate limiting, CSRF protection, audit logs, and an official payment-provider integration. Do not treat a submitted reference as proof of payment until verified.

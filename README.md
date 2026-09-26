# Grand Crown Platform

Mobile-first Grand Crown customer platform and admin dashboard.

## Render
- Build Command: `npm install`
- Start Command: `npm start`
- Customer: `/`
- Admin: `/admin`

## Customer UI
- Navy/gold Grand Crown layout matching the approved visual reference.
- Home, Products, My Products, Referral, Team and Account sections.
- PesaJet deposit popup; checkout URL is opened only when the customer taps **Open PesaJet**.
- Deposits remain pending until an administrator approves them.
- Withdrawal minimum UGX 3,000, 12% fee, 10:00 AM–5:00 PM EAT.
- Welcome bonus UGX 2,100 and daily check-in UGX 100.
- Level 1 referral commission 10%; Levels 2 and 3 disabled.

## Admin UI
- Dashboard statistics.
- Users management with a popup for **Credit, Debit, Ban/Unban, Delete**.
- Deposit approval/rejection.
- Withdrawal approval/rejection.
- Product management.
- Transactions and referral reporting.
- General and PesaJet payment settings.

## Security
Set `ADMIN_USER` and a strong `ADMIN_PASS` in Render environment variables before production.

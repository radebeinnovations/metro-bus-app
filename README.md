# MetroBus Wallet

A static, interactive prototype of the MetroBus Wallet mobile experience. It includes onboarding, wallet top-ups, route browsing, trip purchase, vendor payments, airtime/data purchases, tag management, and transaction history.

## Run locally

No build step is required.

```bash
python3 -m http.server 3001 --bind 127.0.0.1
```

Open [http://localhost:3001](http://localhost:3001).

To run the available JavaScript syntax check:

```bash
npm test
```

## Login behaviour

This is a front-end prototype, not a production authentication system. The login form lets a user continue when both fields are filled in, but it does not send, save, or validate credentials.

Do **not** hard-code passwords, member numbers, API keys, or real customer details in this repository. A production version should use a secure authentication provider and server-side session handling.

## Deploying

The app is plain HTML, CSS, JavaScript, and image assets, so it can be deployed directly to Vercel with no build command. The production deployment should use the `radebeinnovations` Vercel account/team.

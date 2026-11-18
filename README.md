# PrivacyShield — Privacy Command Center

An editable, responsive frontend recreation of the PrivacyShield prototype, based on the screenshots supplied by the project owner.

## Run it

No build tools or installation are required.

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Select **Explore secure demo mode** to open the dashboard.

You can also publish the repository with GitHub Pages (Settings → Pages → deploy from the `main` branch, root folder).

## What's included

- Privacy-focused onboarding screen
- Dashboard overview with privacy metrics and an illustrative data-flow map
- Legal/jurisdiction demo assessment
- Consent preference controls
- Data tracker demo
- Simulated proof receipt and audit trail
- Responsive layout for desktop and mobile

## Important prototype limitations

This is a frontend recreation, not the original source export from the hosted ChatGPT site. It is an interactive demonstration only:
- World ID verification is **not connected**.
- Zero-knowledge proofs and nullifiers are **simulated**.
- Blockchain storage, legal scoring, cookie blocking, browser telemetry, and live cross-border tracking are **not implemented**.
- Consent controls update only the page's local demo state; they do not change browser cookie settings.
- The legal assessment is educational and is not legal advice.

A production implementation would need reviewed backend services, real World ID integration, secure proof verification, a browser extension or approved telemetry source, and legal/security review.

## Project structure

```
PrivacyShield/
├── index.html
├── README.md
└── .gitignore
```

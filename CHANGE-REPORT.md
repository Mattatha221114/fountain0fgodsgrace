# FOGGIM — updated website

Updated 8 October 2026 following the navigation, interaction and branding requests.

- Added a persistent smartphone navigation bar: **Home, Services, WhatsApp, Testimonies, Give**. WhatsApp is the raised central button with its recognisable brand icon. Services links to the service schedule.
- Added a floating **Prayer Line** button linked to **073 319 95 44**. It is hidden while payment inputs are focused to keep entry clear.
- Added **Testimonies** to the main menu and created its page with the requested **MOTIvision Holdings is still developing this page** message and a direct link to share a testimony with the ministry. No testimonies were invented.
- Changed About to use the full ministry name.
- Added the church logo behind the hero portrait, mouse-following logo depth, raised navigation hover states, and lift/expansion effects on cards and imagery.
- Added a brief full-screen church-logo entrance: rotation, light bloom and reveal. It clears automatically after 1.7 seconds, can be skipped by a key or click, and is bypassed for reduced motion.
- Removed demonstration/prototype labels from visitor-facing pages. Recording and registration actions accurately explain when their connections are pending instead of claiming playback or completed reservations.
- Added payment-specific interfaces: cardholder/card number/expiry/CVV for Card and Stripe; bank/reference and pending verified banking details for EFT; mobile-number entry for Capitec Pay; and a PayPal handoff explanation without collecting PayPal credentials.
- Giving supports amount/purpose/name/method, review, edit, payment continuation and restart. Continuing explains that payment is not connected and that no payment was processed. Card/mobile fields are cleared after review, when changing methods and when leaving the page. Nothing is submitted or persistently stored. The card interface asks visitors not to use live details until payment is connected.
- Added the supplied **MOTIvision Holdings logo** and centred the entire attribution block on desktop and mobile. Preserved the exact attribution wording and **https://www.motivision.co.za/** link.

## Checks

All ten pages passed Chrome layout/navigation/form-label checks at **1440, 1024, 768, 390 and 320px**. No horizontal overflow, broken internal file links or JavaScript errors were found. Confirmed mobile menu keyboard close, dock destinations, Prayer Line destination, logo entrance completion, pointer movement, reduced-motion bypass and skip-to-content.

All five giving methods passed field, validation, review and pending-payment checks. Browser request monitoring confirmed no requests during review/payment continuation; browser storage remained empty. Checked sensitive values were excluded from review and cleared. Registration shows an accurate pending-connection state.

Visually reviewed the final desktop hero, mobile giving, mobile Testimonies and centred mobile footer. Original ministry images and invitation video remain in place. Added only the supplied MOTIvision logo. Full backend integrations, real sermon recordings and verified event arrangements still need to be connected before live ministry use.

## Open or host

Extract the ZIP and open **foggim/index.html**. The folder can be hosted unchanged on GitHub Pages or any static host; no build step is needed. No publication or deployment was performed.

# FOGGIM website — integration handoff

Open index.html locally or publish this directory to a static host such as GitHub Pages. No installation/build step or external font dependency is required.

The original nine routes remain; testimonies.html is the requested addition. styles.css is the original styling base, experience.css provides the cinematic design, and additions.css provides the mobile dock, Prayer Line, logo entrance, hover behaviour and centred attribution. main.js provides navigation/reveals/dialogs; additions.js provides the logo effects, active mobile links and giving interface.

Payment providers and registration are NOT connected. The UI provides method-specific fields and a review flow; proceeding gives an accurate pending-connection result. There is no payment API, fetch submission, account storage, localStorage, sessionStorage or cookie handling. Card and mobile fields are cleared on review, method changes and page exit, excluded from summaries, and never logged. No card data should be used until a verified secure processor is integrated. Use a provider-hosted payment form/tokenisation for production rather than submitting these local fields.

EFT account details have not been invented. Confirm the ministry's bank details before connecting them. PayPal credentials are never requested here. Real sermon media must replace the pending-recording state; only the original invitation video supplies actual media. Confirm Mountain Prayer details and any event arrangements with the ministry before announcing them. No testimonials or ministry achievements have been invented.

The supplied church vision, mission and foundation wording remain unchanged. The supplied MOTIvision logo is copied unchanged and links to https://www.motivision.co.za/.

The entrance lasts 1.7 seconds and is skippable by key/click; reduced motion bypasses it. Native page transitions fall back gracefully to normal navigation. No frameworks or heavy animation libraries were added.

See CHANGE-REPORT.md and QA-RESULTS.txt for the latest changes and browser checks.

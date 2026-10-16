E-BUSINESS CARD - Mani & Partners
Files: index.html, emblem.png, card.vcf  (keep all three in the same folder)

HOST (free, ~3 minutes) - Cloudflare Pages or Netlify:
 1. Go to app.netlify.com/drop (or Cloudflare Pages > Upload assets)
 2. Drag the whole folder (or the zip) in. You get a link like https://xyz.netlify.app
 3. Rename the site (e.g. manimaran-card) for a clean link.
 4. Optional: attach your own domain (e.g. card.yourfirm.com).

TRACK VIEWS (free): goatcounter.com
 1. Create an account, choose a code, e.g. manipartners
 2. In index.html set: const GOATCOUNTER_CODE = "manipartners";
 3. Re-upload. Dashboard shows visits, country, device, and taps on Save/Call/Email/Directions.

KNOW WHICH CLIENT OPENED IT: send a unique link per person
   https://yoursite/?ref=Client-ABC       (GoatCounter lists it under Referrers)

AFTER HOSTING: in index.html change og:image to the full URL of emblem.png
so WhatsApp / LinkedIn show a preview picture.

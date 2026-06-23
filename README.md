# Phillip Patterson — Artist Portfolio Website

Premium contemporary artist website for Phillip Patterson.  
**Live site:** https://designsbyphill.github.io/phillippatterson.com.au/ (after deployment)

## Design Philosophy
- Sophisticated, immersive, gallery-quality experience
- Heavy emphasis on texture, light, and materiality of the artworks
- Minimalist yet atmospheric — feels like a contemporary art museum or luxury gallery
- Fully responsive (desktop, tablet, mobile)
- No excessive animations; elegant interactions only

## Pages
- **index.html** — Cinematic homepage with hero, artistic quote, featured works, and studio introduction
- **portfolio.html** — Full interactive gallery with filterable artworks, rich detail modals, image galleries, video support, and purchase flows
- **available.html** — Focused view of currently available works with quick-acquisition buttons
- **about.html** — Thoughtful artist statement, creative philosophy, process, and studio context
- **contact.html** — Professional contact form + direct links (prefills from portfolio enquiries)

## Key Features Implemented
- Fixed elegant navigation with mobile hamburger
- Artwork detail modals with multi-image galleries + video player
- PayPal purchase simulation (ready for real PayPal button integration)
- Image lightbox / zoom
- URL hash deep-linking to specific artworks (e.g. `#glass-liminal`)
- Contact form with mailto fallback + prefill support from other pages
- Status badges (Available / Sold)
- In-situ installation mockups using the provided imagery
- The glass sculpture video is embedded in the portfolio modal

## Assets
All images and the installation video are optimized and located in `/assets/images/`.

## Deployment to GitHub Pages (Recommended)

1. Clone or download this folder.
2. Initialize a git repo if needed:
   ```bash
   git init
   git add .
   git commit -m "Initial premium artist site for Phillip Patterson"
   ```
3. Create a new GitHub repository named exactly `phillippatterson.com.au` under the `designsbyphill` account (or push to the existing one).
4. Push to the `gh-pages` branch or enable GitHub Pages on the `main` branch serving `/` (root).
5. For custom domain `phillippatterson.com.au`, add a `CNAME` file containing the domain and configure DNS at your registrar (Hostinger) to point to GitHub Pages.

**Note:** The site is 100% static and requires no backend or paid hosting.

## Customization Notes for Production
- Replace PayPal simulation with actual PayPal Buy Now buttons or a real checkout (Stripe / PayPal Commerce).
- Add Google Analytics or Plausible if desired.
- Update prices, add new artworks by extending the `artworks` array in `portfolio.html`.
- For real form submissions, integrate Formspree, Netlify Forms, or EmailJS.

## Credits
Designed & built as a creative director exercise for Phillip Patterson’s artistic practice.  
All imagery sourced from provided artist assets (glass sculptures, textured paintings, in-situ renders).

---

**Ready to deploy.** The site captures the requested sophisticated, textural, high-end gallery feeling while remaining fully functional as a static GitHub Pages site.

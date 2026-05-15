# Excel Hotels & Resorts — Wedding Landing Page

Destination wedding landing page for Excel Hotels & Resorts.
**Five private resorts** across Jim Corbett and Bhimtal, Uttarakhand.

---

## Quick Deploy to GitHub Pages

1. Create a new GitHub repository (public).
2. Upload `index.html` and `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Source: **Deploy from a branch**.
5. Branch: **main** / root.
6. Click **Save**.

Your page will be live at `https://yourusername.github.io/repository-name/` within a minute or two.

### Custom Domain (optional)

1. **Settings → Pages → Custom domain** — enter your domain (e.g. `weddings.excelhotelandresort.com`).
2. Add a CNAME record in your DNS pointing to `yourusername.github.io`.
3. Tick **Enforce HTTPS** once the certificate provisions.

---

## What's in the file

`index.html` is a **fully self-contained** single-file page. All images, fonts (via Google Fonts CDN), CSS, and JavaScript are embedded or linked — no separate asset folders. You can host it anywhere static HTML is supported (GitHub Pages, Netlify, Vercel, S3, your own server).

### Sections, top to bottom

- **Header** — fixed nav (Destinations · Resorts · Pre-Wedding · FAQ · Get a Call Back)
- **Hero** — sunset resort image with headline *"Where the forest bears witness to your vows"* + primary CTA
- **Editorial Intro** — *Five private resorts · Three destinations · One perfect wedding* + stats
- **Photography Break** — full-bleed mandap photo with parallax
- **Destinations** — three wedding destination types: Forest · Mountain · Lakeside
- **Resort Showcase** — five resort cards in order:
  1. The Banyan Retreat — 140 rooms, Chhoi, Corbett
  2. Excel Hotels & Resorts, Kotabagh — 67 rooms
  3. La Perle River Resort — 59 rooms, Dhikuli, Corbett
  4. Mango Bloom River Resort — 48 rooms, Mohaan, Corbett
  5. Excel Hotels & Resorts, Bhimtal — 49 rooms
- **Wedding Gallery** — *Moments that last forever* (6 photos)
- **Pre-Wedding Shoots** — best season, photography information
- **Photography Break** — full-bleed Bhimtal aerial
- **The Experience** — 3-day itinerary timeline
- **Inclusions** — 9 package inclusions
- **Testimonials** — 3 couples
- **Inquiry Form** — name / phone / email capture
- **FAQ** — 8 answers
- **Final CTA** — *Your wedding deserves this setting*
- **Footer** — Our Resorts · Services · Contact

### Contact details wired across the page

- Phone: **+91 92113 01990** (header nav button, hero CTA, every "Get a Call Back" trigger, footer, floating bottom-right call button, thank-you overlay)
- Email: **wedding@excelhotelandresort.com**

---

## To change contact details later

Search-and-replace in `index.html`:

- Phone display: `+91 92113 01990` → your new number
- Phone link: `tel:+919211301990` → `tel:+91XXXXXXXXXX`
- Email: `wedding@excelhotelandresort.com` → your new email

That's it. No build step.

---

## Built by

Alcor Getaways · May 2026

# Summit Concrete Co. — Construction Demo Website

Reusable multi-page demo site for any concrete or construction business. Sample company, not a real business. Demo by A’Nya.

**Pages:** Home · Services · Our Work · Reviews · Free Estimate · Admin

- **Opening intro:** plays `intro.mp4` (drop a 4–8s landscape clip in the repo root). If the file is missing, a built-in blueprint-and-pour animation plays instead. Skip button, Esc to skip, "Replay intro" in the footer, skipped for reduced-motion visitors and on `#admin`.
- Animated hero with floating cards, page transitions and scroll reveals
- Sample reviews (clearly labeled) to replace with the client's real Google reviews
- Free-estimate form feeds the Admin dashboard
- Admin (`#admin`, demo PIN `1234`): estimate requests with status, photo uploads, featured reviews, business info

## Reusing for a client
Search the file for `Summit` and replace it with the client's name, then set phone, email and service area in Admin → Business info. Replace the sample reviews and upload job photos.

Single file (`index.html`), no build step. Hosted with GitHub Pages.

> Admin data is saved in the viewer's browser only (demo). Connect a database or email service before going live.

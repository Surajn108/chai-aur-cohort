# Cursor Page — Recreated Sections

A static recreation of key sections from the [Cursor](https://cursor.com) marketing homepage.

---

## Sections Recreated

1. **Navbar** — Logo, nav links (Features, Enterprise, Pricing, Resources), Sign In and Download buttons  
2. **Hero / Main** — Headline (“Built to make you extraordinarily productive…”) and primary “Download for macOS” CTA  
3. **Hero 1** — Large product preview image  
4. **Hero 2** — “Trusted every day by millions of professional developers” with company logo cards (Stripe, OpenAI, Linear, Datadog, NVIDIA, Figma, Ramp, Adobe)  
5. **Hero 3** (three feature blocks)  
   - Agent: “Agent turns ideas into code”  
   - Tab: “Magically accurate autocomplete”  
   - Ecosystem: “Everywhere software gets built”  
6. **Hero 6** — Tagline: “The new way to build software.”  
7. **Testimonials** — Six quote cards   
8. **Hero 7 — “Stay on the frontier”** — Three cards: Access the best models, Complete codebase understanding, Develop enduring software  
9. **Hero 8 — Changelog** — Four changelog cards with dates and titles  
10. **Main (repeat)** — “Cursor is an applied team focused on building the future of coding” and “Join us” CTA  
11. **Hero 1 (repeat)** — Team photo  
12. **Hero 9 — “Recent highlights”** — Three blog-style cards with titles and descriptions  
13. **Try Cursor** — “Try Cursor now.” and Download button  
14. **Footer** — Columns: Product, Resources, Company, Legal, Connect; bottom bar with copyright, theme/language controls  

---

## Fonts

| Usage | Font |
|--------|------|
| Primary | **CursorGothic** (custom), loaded from `/fonts/cursorgothic.woff2` and `/fonts/cursorgothic.woff` |
| Fallbacks | `"CursorGothic Fallback"`, `system-ui`, `Helvetica Neue`, `Helvetica`, `Arial`, `sans-serif` |

Body text uses CursorGothic when available; otherwise it falls back to the system stack above.

---

## Colors

| Purpose | Value | Usage |
|--------|--------|--------|
| **Primary background** | `#13120a` (`--Prime_col`) | Page background, navbar, main areas |
| **Secondary background** | `#1b1813` (`--Sec_col`) | Feature blocks, cards, footer |
| **White** | `#fff` | Primary text, borders, button outlines |
| **Black** | `#000` | Text on white buttons |
| **Accent / links** | `#f54e00` | “Learn about…”, “See what’s new”, “View more posts” |
| **Muted text** | `#82817d` | Descriptions, dates, secondary copy |
| **Card text** | `#e6e6e6` | Testimonial body text |
| **Author meta** | `#9a9a9a` | Author titles under testimonials |
| **Footer text** | `#999894` | Copyright and footer copy |
| **Card border** | `#1f1f1f` | Testimonial card borders |
| **Dark card** | `#201f19` | Recent highlights cards |
| **Footer controls** | `#26251f` | Footer button/control backgrounds |
| **Button hover** | `#edecec` | Download button hover |
| **Nav hover** | `#1b1813` | Sign In button hover |

---

## Files

- `index.html` — Page structure and content  
- `style.css` — Layout and typography (uses `--Prime_col` and `--Sec_col`)  
- `assets/` — Images and logo  
- `fonts/` — CursorGothic (woff2, woff) for local use  

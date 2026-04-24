# James Paul Site

Static site. Flat file structure. Ready for Vercel.

## Files

```
index.html     Landing page
tutoring.html  LSAT tutoring detail
essays.html    Essay review detail
pricing.html   Pricing overview + FAQ
styles.css     Shared stylesheet
script.js      Mobile nav toggle
```

## Placeholders to Replace

Before deploying, find-and-replace these across all HTML files:

1. **Calendly URL.** Every `Book a Call` / `Book a Consultation` link uses `https://calendly.com/jamespaul/intro`. Swap in the real scheduling link.
2. **Email.** Footer links use `hello@jamespaul.com`. Swap in the real address.
3. **Testimonial.** `index.html` contains a placeholder testimonial inside `<!-- ========== Testimonial ========== -->`. Replace the quote and attribution, or delete the section if no testimonial is available yet.

## Deploying to Vercel

1. Push this folder to a GitHub repo.
2. In Vercel, import the repo. No build step needed. Vercel serves the static files directly.
3. Vercel auto-detects the static site. Leave all settings default.

Alternatively, drag-and-drop the folder into Vercel's deploy UI.

## Customizing

All colors, fonts, and spacing live as CSS variables at the top of `styles.css`. Adjust there for global changes. Type scale and rhythm can be edited in the same file.

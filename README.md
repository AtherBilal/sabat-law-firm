# Sabat Law Firm — Website

A modern, responsive marketing site for **Sabat Law Firm, LLC** — attorney Anthony W. Sabat, serving the Greater St. Louis Metropolitan area and O'Fallon, IL with estate planning, probate, real estate, and business law.

Static single-page site: warm cream + evergreen brand, Fraunces / Hanken Grotesk typography, real client reviews, and a plain-English voice.

## Run locally

```bash
python3 -m http.server 8754
# then open http://localhost:8754/
```

## Structure

- `index.html` — the entire site (self-contained HTML/CSS/JS)
- `assets/` — photography and brand imagery

## Notes

- The contact form uses a `mailto:` fallback (no backend). For real lead capture, wire it to a form service such as Formspree or Netlify Forms.
- Built as a free redesign of the firm's web presence.

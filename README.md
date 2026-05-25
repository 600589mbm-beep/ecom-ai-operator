# Ecom AI Operator — Website

Marketing site for **Ecom AI Operator**, a pack of 5 Claude Skills for ecommerce sellers.

Static HTML/CSS — no build step. Deploys to GitHub Pages.

## Pages
- `index.html` — home / hero / overview
- `skills.html` — the 5 skills in detail
- `pricing.html` — Starter $49 / Pro $97 / Club $19/mo
- `faq.html` — common questions
- `free.html` — lead magnet (free Listing Optimizer in exchange for email)
- `assets/style.css` — shared styles

## Before launch — replace these placeholders
| Placeholder | Where | Put |
|---|---|---|
| `REPLACE_WITH_CHECKOUT_LINK_STARTER` / `_PRO` / `_CLUB` | `pricing.html` | Gumroad/Stripe checkout URLs |
| `REPLACE_WITH_EMAIL_FORM_ENDPOINT` | `free.html` | Mailchimp/ConvertKit/Beehiiv form action |
| `REPLACE_WITH_CONTACT_EMAIL` | all footers + `free.html` | support email |

## Local preview
```bash
python3 -m http.server 8080   # then open http://localhost:8080
```

## Deploy
Served via GitHub Pages from the `main` branch root. Pushing to `main` redeploys.

---
Not affiliated with Anthropic. "Claude" is a trademark of Anthropic, PBC.

# Growth Audit — Quizlet

**Live:** https://bterzic123.github.io/quizlet-flow-rebuild/
**Prototype only:** https://bterzic123.github.io/quizlet-flow-rebuild/?view=proto

Quizlet's ads sell finals week; Q+ Unlimited sells the same feature list to everyone. This audit rebuilds the first launch so it asks what each student is studying for and answers it on Q+ Unlimited, in Quizlet's own design and at its published prices. Three phones show three new students: one from the Meta creator ad, one from App Store search, one from the YouTube ad.

## The five ideas

| # | Idea | Expected effect |
| :-- | :-- | :-- |
| 1 | Ask what they're studying for, then name it on Q+ Unlimited | CR +15–20% to trial start |
| 2 | Let them in before the sign-up wall | CR +5–10%, ARPU +10–17% |
| 3 | Make the loader read their answers back | CR +10–15% to trial start |
| 4 | Put 4.8 stars from 1.1M ratings next to the price | CR +10–15% to trial start |
| 5 | Show both plans and real dates on the first screen | CR +5–15%, ARPU +10–15% |

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps, not measured lift for Quizlet.

## Grounding

Screens, copy, features and prices come from the Quizlet iOS app as recorded on 11 November 2026 (EU storefront: 44,99 € a year with a 7-day free trial, 9,99 € a month). Ratings, user counts, survey figures and the quoted review come from the US App Store listing. Ads and their dates are as seen by AppMagic. 3,75 € a month is 44,99 € ÷ 12. Trial dates are counted from the day the page is opened.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

Prepared by Adapty · [Book a demo](https://calendly.com/d/cty4-37z-zqj)

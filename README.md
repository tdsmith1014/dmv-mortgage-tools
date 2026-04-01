# DMV Mortgage Tools

Free, browser-based real estate finance calculators for **Washington DC, Maryland, and Virginia** — built for home buyers navigating their first closing and real estate professionals who need fast, accurate numbers on every deal.

🌐 **Live site:** `https://YOUR-USERNAME.github.io/dmv-mortgage-tools`

---

## Tools included

| Tool | Description |
|------|-------------|
| **Mortgage Calculator** | Monthly payments, amortization, transaction summary (Condo / Co-op / SFH) |
| **Escrow Calculator** | End-in-mind formula, 60-day rule, 15 MD counties, 10 NoVA localities |
| **Closing Cost Calculator** | Transfer taxes, tax proration, APR (Reg Z), buyer & seller CD views |
| **Interest Rate Swap Analysis** | SOFR vs. fixed swap, unused fee drag, 3-year amortization |

## Key features

- **Jurisdiction-specific** — DC, Maryland (15 counties), and Virginia (10 NoVA localities) each have correct tax due dates, transfer tax rates, and escrow rules
- **60-day rule** — Escrow calculator automatically detects when the next tax due date is within 60 days and moves prorated tax to Prepaids, resetting escrow to the following due date
- **MD seller proration** — Maryland taxes are prepaid; buyer's obligation to seller is always shown at closing
- **Reg Z APR** — Closing cost calculator computes APR using the actuarial method per 12 CFR §1026.22, with tolerance checker (±0.125% fixed / ±0.250% ARM)
- **No server required** — All calculations run entirely in the browser; no data is collected or transmitted

## How to deploy to GitHub Pages

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Under **Source**, select `main` branch and `/ (root)` folder
4. Click **Save**
5. Your site will be live at `https://YOUR-USERNAME.github.io/dmv-mortgage-tools` within 1–2 minutes

## Files

```
index.html                    ← Landing page / dashboard
mortgage-calculator.html      ← Mortgage calculator (Condo/Co-op/SFH)
escrow-calculator.html        ← Escrow calculator with 60-day rule
closing-cost-calculator.html  ← Closing costs, transfer taxes, APR
swap-analysis.html            ← Interest rate swap vs. floating analysis
README.md                     ← This file
```

## Disclaimer

These tools are for estimation purposes only and do not constitute a Loan Estimate, Closing Disclosure, or any other legally required disclosure. Always obtain an official Loan Estimate from a licensed lender before making financial decisions.

---

*Built for the DC / Maryland / Virginia real estate market.*

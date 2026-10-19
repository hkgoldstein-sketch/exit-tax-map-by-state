# Exit Tax Map 2026: what a single seller keeps selling a $1M, $3M or $10M business, by state

Federal, 3.8% NIIT and state tax on a $1M, $3M and $10M business sale for all 50 states and DC, with each state rule dated and linked to its source.

- As of: **2026-10-18**
- Rows: 153
- Files: `data/exit-tax-map-by-state-2026.csv`, `data/exit-tax-map-by-state-2026.json`
- License: [CC BY 4.0](LICENSE) (use it, share it, adapt it, keep the attribution below)
- Source and live page: [Big Sale Tax: Exit Tax Map 2026: what a single seller keeps selling a $1M, $3M or $10M business, by state](https://bigsaletax.com/data/exit-tax-map-by-state/)

## Methodology
Single filer, resident of the state shown all year. Sale of the assets of an operating business owned more than five years, no real estate, farmland or qualified small business stock. The whole price over basis is long-term capital gain ($1,000,000, $3,000,000 or $10,000,000), no other income, no installment sale, 2026 federal standard deduction $16,100, state tax only (no local taxes). Federal tax uses the 2026 long-term capital gain brackets plus the 3.8% net investment income tax; the active-owner columns drop the 3.8% NIIT (and Minnesota's 1% investment income tax) for an owner who materially participates. Every state rule and its source URL is in the state_rule_2026 and source_urls columns. Illustration only, not tax advice.

## Columns
| Column | Meaning |
|---|---|
| `state` | State or DC name |
| `abbr` | Two-letter postal code |
| `sale_gain_usd` | Long-term capital gain on the sale (1,000,000 / 3,000,000 / 10,000,000) |
| `federal_income_tax_usd` | Federal long-term capital gain tax |
| `niit_usd` | 3.8% net investment income tax |
| `federal_total_usd` | Federal income tax plus NIIT |
| `state_tax_usd` | State tax on the gain |
| `total_tax_usd` | Federal plus NIIT plus state |
| `you_keep_usd` | Sale gain minus total tax |
| `effective_rate_pct` | Total tax divided by gain |
| `total_tax_active_owner_usd` | Total tax if the seller materially participates (no NIIT) |
| `you_keep_active_owner_usd` | Gain minus total tax for the active owner case |
| `alt_state_tax_usd` | Alternate state tax where a state has a special case (blank if none) |
| `alt_state_tax_case` | Description of that special case |
| `state_top_rate_2026` | State top statutory rate |
| `state_rule_2026` | State rule applied in plain words |
| `source_urls` | Primary source URLs for the state rule |
| `assumptions` | Assumptions used for every row |
| `computed` | Date the numbers were computed (YYYY-MM-DD) |
| `publisher` | Publisher |
| `page` | Canonical page for this dataset |

## How to cite
Attribution (plain): "Exit Tax Map 2026: what a single seller keeps selling a $1M, $3M or $10M business, by state", Big Sale Tax (Hans Goldstein, Enrolled Agent, admitted to practice before the IRS), https://bigsaletax.com/data/exit-tax-map-by-state/, as of 2026-10-18.
Machine-readable: see [CITATION.cff](CITATION.cff). Link to the live page when you publish the number.

## Refresh
Rebuilt monthly from the live page. The CSV on the site is the source of truth; this repo is a mirror.

Illustration and education only. Not tax, legal or investment advice.

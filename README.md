# Spotless Studios — B2B Lead Datasets & n8n Workflows

Open-source n8n automation templates and free 50-row B2B sample CSV datasets powered by **[Spotless Studios' 58 Live Apify Scrapers](https://apify.com/spotless_studios)**.

🌐 **Interactive Storefront & Live CSV Previews:** https://gyyguguy.github.io/b2b-lead-datasets-and-n8n-workflows/

---

## 📦 Ready-to-Import n8n Workflows (`n8n-workflows/`)

Import any `.n8n.json` file directly into n8n (**Workflows → Import from File**), set `APIFY_API_TOKEN` in your n8n environment variables, and run on a schedule:

| Workflow | Trigger | Output | Apify Actor |
|---|---|---|---|
| [`01-sled-gov-rfp-daily-slack-alert.n8n.json`](n8n-workflows/01-sled-gov-rfp-daily-slack-alert.n8n.json) | Daily 08:00 | New open US city/county IT & software RFPs → Slack | [SLED Gov Bids](https://apify.com/spotless_studios/sled-procurement-scraper) |
| [`02-shopify-platinum-agency-lead-enricher.n8n.json`](n8n-workflows/02-shopify-platinum-agency-lead-enricher.n8n.json) | Weekly Mon | Verified Platinum/Premier Shopify agencies + emails & LinkedIn → Google Sheets | [Shopify Partners v0.2](https://apify.com/spotless_studios/shopify-partners-scraper) |
| [`03-airbnb-str-occupancy-comp-monitor.n8n.json`](n8n-workflows/03-airbnb-str-occupancy-comp-monitor.n8n.json) | Daily 07:00 | 30d/90d/365d STR occupancy & nightly rate comps → Webhook | [Airbnb Calendar](https://apify.com/spotless_studios/airbnb-calendar-scraper) |
| [`04-skool-paid-community-creator-scout.n8n.json`](n8n-workflows/04-skool-paid-community-creator-scout.n8n.json) | Weekly Tue | Paid 150+ member Skool communities & owner socials → Google Sheets | [Skool Communities](https://apify.com/spotless_studios/skool-communities-scraper) |
| [`05-cisa-kev-ransomware-secops-alert.n8n.json`](n8n-workflows/05-cisa-kev-ransomware-secops-alert.n8n.json) | Every 6h | Newly added CISA KEV ransomware vulnerabilities → Slack | [CISA KEV & NVD CVEs](https://apify.com/spotless_studios/cisa-kev-cves-scraper) |

---

## 📊 Free 50-Row Sample CSV Datasets (`sample-datasets/`)

Inspect or import directly into Clay, Smartlead, Instantly, HubSpot, or Excel:

- [`shopify-plus-platinum-premier-agencies-sample-50.csv`](sample-datasets/shopify-plus-platinum-premier-agencies-sample-50.csv) — Verified Platinum/Premier Shopify agencies, emails, team sizes, client case studies
- [`webflow-certified-agencies-leads-sample-50.csv`](sample-datasets/webflow-certified-agencies-leads-sample-50.csv) — Certified/Premium Webflow agencies, hourly design/dev rates, minimum budgets
- [`us-sled-gov-it-software-rfps-sample-50.csv`](sample-datasets/us-sled-gov-it-software-rfps-sample-50.csv) — Active US state & local government IT, cloud & cybersecurity RFPs with closing dates
- [`stripe-verified-partners-directory-sample-50.csv`](sample-datasets/stripe-verified-partners-directory-sample-50.csv) — Verified Stripe implementation partners, products, certified staff counts

---

## 💼 Instant Full CSV Packs ($49) & Custom Managed Data Feeds

Want the complete deduplicated CSV packs (**870 verified rows across all 4 packs for $129**, or **$49/pack**) delivered instantly without running scrapers, or a custom daily/hourly CRM/BigQuery/Slack feed?

👉 **Email:** [spotless.studios.info@gmail.com](mailto:spotless.studios.info@gmail.com?subject=Full%20B2B%20CSV%20Pack%20%2F%20Custom%20Feed)  
👉 **Apify Store Portfolio (58 Public Actors):** https://apify.com/spotless_studios

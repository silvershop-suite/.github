# SilverShop Suite

A complete, modular commerce suite for **SilverStripe CMS 6**, extending [`silvershop/core`](https://github.com/silvershop/silvershop-core) into a full-featured online store.

Where SilverShop ships a solid commerce core, this suite adds the surrounding pieces a real shop needs — catalog, checkout, tax & finance, fulfilment, marketing and a headless API — as small, focused, independently installable modules.

## Modules

A set of coherent, reusable modules, grouped roughly as:

- **Catalog** — brands, colours & swatches, product galleries, bundles, related products, comparison, category index
- **Checkout & customers** — country-adaptive address fields, address lookup, wishlist
- **Tax & finance** — VAT compliance, invoicing, ledger, reports, currency formatting
- **Fulfilment** — shipping labels, MyParcel, barcodes, stock alerts
- **Marketing** — newsletters (Mailchimp / Campaign Monitor / Laposta), SEO, USPs, reviews
- **Search** — fast faceted search with a Meilisearch backend
- **Headless** — REST and GraphQL APIs

## Install

Each module installs on its own:

```bash
composer require silvershop-suite/<module>
```

Browse the full list on [Packagist](https://packagist.org/packages/silvershop-suite/).

## Requirements

- SilverStripe CMS **6.2+**
- PHP **8.3+**

## Licence

BSD-3-Clause. Built and maintained by **Remy Vaartjes**.

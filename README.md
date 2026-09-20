# Invoice & Quote Desktop

An offline-first Windows invoice and quote generator for freelancers and small businesses. No subscriptions, no cloud required — everything runs and stays on your machine.

## Why this exists

Most invoicing tools are SaaS subscriptions charging $15–40/month for something a lightweight native app can do for a one-time price. This app targets freelancers, trades, and small business owners who want a fast, offline, no-nonsense invoicing tool.

## Core features (v1)

- [ ] Client / contact database (local, SQLite)
- [ ] Product / service catalog with default pricing
- [ ] Invoice creation — line items, tax, discounts, totals
- [ ] Quote creation, with quote-to-invoice conversion
- [ ] PDF export with clean, branded layout
- [ ] Invoice status tracking (Draft / Sent / Paid / Overdue)
- [ ] Local save/load, no account or internet required

## Planned for v2+

- [ ] Recurring invoices / templates
- [ ] Simple revenue reporting (by month / by client)
- [ ] Email sending built-in
- [ ] Optional payment link integration (Stripe)

## Tech stack

- **UI:** WPF or WinUI 3 (C#)
- **Database:** SQLite (local file, no server)
- **PDF generation:** QuestPDF or PDFsharp
- **Packaging:** MSIX / Microsoft Store, or direct .exe distribution

## Project structure

```
/src            application source code
/docs           feature specs, schema notes, design decisions
/assets         icons, logos, invoice template assets
/tests          unit and integration tests
```

## Status

🚧 Early scaffold — drop in generated app files as they're built. See `docs/ROADMAP.md` for build order.

## License

MIT — see `LICENSE`.

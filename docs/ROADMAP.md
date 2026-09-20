# Roadmap

## v1 — Core MVP
1. Client list (add/edit/delete, local SQLite storage)
2. Invoice creation: line items, tax calculation, totals
3. PDF export via QuestPDF or PDFsharp
4. Save/load invoices locally

## v2 — Quoting & status
1. Quote creation and quote → invoice conversion
2. Payment status tracking (Draft / Sent / Paid / Overdue)
3. Simple revenue reporting (by month, by client)

## v3 — Optional / stretch
1. Recurring invoice templates
2. Built-in email sending
3. Stripe payment link integration
4. E-signature support for quotes

## Things to double-check when building with AI
- Tax calculation edge cases (multi-rate, regional tax rules e.g. GST/HST/PST)
- Currency/number rounding
- PDF layout polish — first AI pass is usually functional but generic; iterate on visual design

# Data Model (draft)

## Client
- id
- name
- company (optional)
- email
- phone
- billing_address

## Product / Service
- id
- name
- description
- default_unit_price
- tax_rate

## Invoice / Quote
- id
- type (invoice | quote)
- client_id
- issue_date
- due_date
- status (draft | sent | paid | overdue)
- line_items: [{ product_id, description, quantity, unit_price, tax_rate }]
- subtotal
- tax_total
- discount
- total
- notes

## Invoice Number Sequence
- Auto-incrementing, prefixable (e.g. INV-0001, QUO-0001)

# Design Decisions

## 1. Data Modeling Approach
The schema is designed to represent real-world invoice structures extracted from unstructured PDF documents.

## 2. Required vs Optional Fields
- Required: invoice_id, issue_date, items, total_amount
- Optional: due_date, notes

## 3. Validation Logic
- invoice_id uses regex pattern validation
- email fields use format validation
- numeric fields enforce minimum values

## 4. Nested Structure
Items are modeled as an array of objects to support repeating invoice entries.

## 5. Scalability
The schema is designed to support:
- multi-currency systems
- optional fields
- future extensions (discounts, shipping, etc.)

## 6. Data Integrity Consideration
Subtotal and tax are separated to allow validation logic and future rule enforcement.

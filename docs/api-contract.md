# API Contract (Example)

## Endpoint
POST /invoices/validate

## Request Body
- JSON invoice data

## Response
- 200 OK → valid schema
- 400 Bad Request → validation errors

## Purpose
This endpoint validates incoming invoice data against the JSON Schema
before storing or processing it.

## Problem

Many organizations receive large PDF invoices (25–150 pages) that contain unstructured data.
Manually extracting this information is time-consuming and error-prone.

## Solution

This project demonstrates how to convert unstructured invoice data into a structured JSON format,
and validate it using a scalable JSON Schema.

# Invoice JSON Schema (Advanced)

This project demonstrates designing a production-level JSON Schema from unstructured invoice documents.

## Features
- Deeply nested JSON structure
- Field-level validation (regex, format, enums)
- Required vs optional field logic
- Scalable data modeling approach
- Real-world invoice use case

## Structure
- `/schema` → JSON Schema definition
- `/examples` → Sample extracted data
- `/docs` → Design decisions and architecture

## Use Case
This simulates extracting structured data from complex PDF invoices (25–150 pages) and converting them into validated JSON.

## Skills Demonstrated
- Data modeling
- JSON Schema design
- Validation logic
- API-ready structure design

 ## Data Flow

1. Raw PDF document (unstructured)
2. Data extraction (manual or automated)
3. Structured JSON output
4. JSON Schema validation
5. Ready for API integration

# Travel CRM – API & DB Pack

Generated: 2025-08-26

This pack contains:
- `openapi.yaml` – OpenAPI 3.0 spec for v1 APIs across phases
- `schema.sql` – MySQL 8 DDL covering MVP → Scale modules
- Suggested flow:
  1. Import `schema.sql` into MySQL
  2. Load `openapi.yaml` into Swagger UI/Postman for live docs
  3. Extend per sprint (add fields, tags, paths)

## Phase Mapping
- **Phase 1 (MVP):** auth, users, partners, roles, leads, customers, bookings (basic), invoices, payments (manual/initiated), reports (basic)
- **Phase 2 (Core Expansion):** vendors, destinations, hotels, activities, itineraries (v1), files, payment gateways, notifications (ops)
- **Phase 3 (Differentiators):** offers & promotions, mobile-friendly endpoints, vendor portal specific scopes
- **Phase 4 (Scale):** integrations (GDS/accounting/messaging), audit logs, advanced reports, compliance

## Notes
- Security: JWT bearer, role+tenant scoping by `partner_id`
- Pagination: `page`, `limit`, plus `sort` and `q` search (add in handlers)
- IDs are UUID (CHAR(36)) for portability; you can switch to BINARY(16) if preferred
- Payments: Use webhooks to reconcile statuses
- GST: invoice fields included; adapt to your country rules as needed

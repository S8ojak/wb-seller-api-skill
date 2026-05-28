# NOTICE

This repository is an internal RIDNESS (Project4) maintained fork of
[miilv/wb-seller-api-skill](https://github.com/miilv/wb-seller-api-skill).

**Purpose:** Hold the canonical OpenAPI snapshot of the Wildberries Seller API
that the RIDNESS Project4 analytics platform depends on, without relying on the
upstream maintainer's release cadence.

**Source of truth for content:** <https://dev.wildberries.ru/openapi/>

**Sync cadence:**
- On-signal: when our `wb_changelog` cron flags a WB API change.
- Preventive: monthly review against `dev.wildberries.ru`.

**License:** no explicit license in upstream; content derived from Wildberries
public API documentation. See upstream repository for current status.

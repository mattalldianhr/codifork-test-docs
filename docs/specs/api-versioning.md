# API Versioning Spec

## Job to Be Done

Allow the API to evolve without breaking existing clients.

## Approach

URL-based versioning: `/api/v1/...`, `/api/v2/...`. Major versions only.
Minor changes are additive and backwards-compatible.

## Deprecation

Versions are supported for 12 months after the next major ships. Deprecation
warnings are returned in a `Deprecation` response header.

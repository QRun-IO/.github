# QQQ Compatibility Matrix

This document tracks version compatibility across the QQQ ecosystem components.

**Last Updated:** December 24, 2024

## Current Recommended Versions

| Component | Version | Status | Notes |
|-----------|---------|--------|-------|
| qqq-core | 0.25.1 | Stable | Current production release |
| qqq-frontend-dashboard | 0.25.0 | Stable | Material UI dashboard |
| qqq-frontend-core | 0.25.0 | Stable | TypeScript core library |

## QBit Compatibility

All QBits are designed to work with the latest stable QQQ release.

| QBit | Min QQQ Version | Max QQQ Version | Status | Notes |
|------|-----------------|-----------------|--------|-------|
| qbit-user-role-permissions | 0.24.0 | - | Stable | User/role management |
| qbit-workflows | 0.25.0 | - | Stable | Requires qbit-user-role-permissions |
| qbit-webhooks | 0.24.0 | - | Stable | Webhook support |
| qbit-standard-process-trace | 0.24.0 | - | Stable | Process tracing |
| qbit-sftp-data-integration | 0.24.0 | - | Stable | SFTP import/export |
| qbit-customizable-table-views | 0.25.0 | - | Stable | Table view customization |
| qbit-bom | 0.24.0 | - | Stable | Parent POM for QBits |

## Tooling Compatibility

| Tool | Min QQQ Version | Notes |
|------|-----------------|-------|
| qqq-mcp-rag | Any | AI assistant - works with all QQQ versions |
| qqq-orb | 0.24.0+ | CircleCI Orb for CI/CD |
| qctl | 0.25.0+ | Platform controller CLI |

## Version History

### qqq-core 0.25.0 (May 2025)

**Compatible with:**
- qqq-frontend-dashboard: 0.25.0
- qqq-frontend-core: 0.25.0
- All QBits >= 0.24.0

**Breaking Changes:**
- Updated dotenv library (requires quoting `#` in values)

### qqq-core 0.24.0 (March 2025)

**Compatible with:**
- qqq-frontend-dashboard: 0.24.0
- qqq-frontend-core: 0.24.0

**New Features:**
- Initial QBit architecture
- Enhanced authentication scopes

---

## How to Update This Document

When releasing a new version:

1. Update the "Current Recommended Versions" table
2. Add QBit compatibility if changed
3. Add a new entry under "Version History"
4. Note any breaking changes

This document is the source of truth for version compatibility across the QQQ ecosystem.

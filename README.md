# Database Scripts

Database resources for the VidhyaPlus learning platform.

## Purpose

This repository is intended to house version-controlled database assets such as:

- Schema definitions
- Migrations
- Seed data
- Local development bootstrap scripts
- Data-maintenance utilities

## Current Status

The repository is currently being prepared for its database assets. The integrated VidhyaPlus repository contains the active application database resources today.

## Related Project

See [vidhyaplus-backend](https://github.com/itdaaiclassroom/vidhyaplus-backend) for the full-stack platform, including its current database folder.

## Contribution Convention

When scripts are added, use a clear, ordered naming convention:

```
001_create_core_schema.sql
002_add_student_indexes.sql
seed_development_data.sql
```

Each migration should be safe to review, documented, and paired with rollback guidance when appropriate.

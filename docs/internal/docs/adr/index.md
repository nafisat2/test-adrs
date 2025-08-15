---
id: adrs-overview
title: Architecture Decision Records (ADR)
sidebar_label: Overview
# prettier-ignore
description: Overview of Architecture Decision Records (ADR)
---

The substantial architecture decisions made in the test-adrs project live here.
For more information about ADRs, when to write them, and why, please see
[this blog post](https://engineering.atspotify.com/2020/04/14/when-should-i-write-an-architecture-decision-record/).

Records are never deleted but can be marked as superseded by new decisions or
deprecated.

Records should be stored under the `./docs/internal/docs/adr` directory.

## Contributing

### Creating an ADR

- Copy `./docs/internal/docs/adr/.template.md` to
  `./docs/internal/docs/adr/YYYYMMDD-title.md` (title should be
  descriptive.)
- Fill in the ADR following the guidelines in the template
- Submit a pull request
- Address and integrate feedback from the community
- Merge the pull request

## Superseding an ADR

If an ADR supersedes an older ADR then the status of the older ADR is changed to
"superseded by YYYYMMDD-title", and links to the new ADR.

<details><summary>❗Development Environment for Testing Changes</summary>

**⚠️ IMPORTANT:** Always test breaking changes in development environment before production.

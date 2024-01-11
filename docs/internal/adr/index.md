---
id: adrs-overview
title: Architecture Decision Records (ADR)
sidebar_label: Overview
# prettier-ignore
description: Overview of Architecture Decision Records (ADR)
---

The substantial architecture decisions made in the Labels Repo project live here.
For more information about ADRs, when to write them, and why, please see
[this blog post](https://engineering.atspotify.com/2020/04/14/when-should-i-write-an-architecture-decision-record/).

Records are never deleted but can be marked as superseded by new decisions or
deprecated.

Records should be stored under the `docs/internal/adr` directory.

## Contributing

### Creating an ADR

- Copy `docs/internal/adr/.template.md` to
  `docs/internal/adr/YYYYMMDD-title.md` (title should be
  descriptive.)
- Fill in the ADR following the guidelines in the template
- Submit a pull request
- Address and integrate feedback from the community
- Add the path of the ADR to the
  [`mkdocs.yml`](https://github.com/grafana/gops-labels/docs/internal/mkdocs.yml)
- Merge the pull request

## Superseding an ADR

If an ADR supersedes an older ADR then the status of the older ADR is changed to
"superseded by YYYYMMDD-title", and links to the new ADR.

# 20221024 Record Architecture Decisions

## Status

Accepted

## Context

We'd like to record architectural decisions made by the Cloud Platform Team
regarding Grafana Cloud deployment.

## Decision

We'd like current and future contributors to understand why things are done the
way they are. Any significant decision that impacts the way we write and deliver
software should have an ADR.

[This post](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions)
lays out a widely accepted format for ADRs which was used to create
[.template.md](.template.md) and this ADR.

ADR files should be named `YYYYMMDD-title.md` which is contrary to the above
article. It states, "...ADRs will be numbered sequentially and
monotonically...". We don't have a need for such a number since this is a manual
system and we don't expect a high volume. It then states, "...Numbers will not
be reused..." which I think we can ignore. Multiple ADRs can have the same date,
though I'd expect it to be uncommon. Prefixing ADRs with dates does one
important thing: keep ADRs in the order of the decisions made. We can assign
them a number later on if it becomes useful.

## Consequences

Collectively understanding how we got here makes it easier to rationalize about
and agree upon how to change for the better.

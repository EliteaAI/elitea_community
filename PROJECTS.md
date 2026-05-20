# Elitea Community Triage Project Guide

This document explains how the **Elitea Community Triage** project is used in the public Elitea community workflow.

The project tracks public community-reported items from initial intake through review, backlog, implementation, testing, and completion.

## Purpose

The **Elitea Community Triage** project exists to:

- make community intake visible and organized
- help maintainers triage issues consistently
- communicate high-level progress to the community
- separate public intake workflow from internal planning systems

The default repository for this project is:

- `EliteaAI/elitea_community`

## Project board

- https://github.com/orgs/EliteaAI/projects/5/views/1

## What is tracked in the project

The project is used for actionable items coming from the public community repository, including:

- bug reports
- feature requests
- actionable product feedback
- selected documentation issues

General Q&A and informal discussion usually belong in:

- https://github.com/EliteaAI/elitea_community/discussions

## Workflow statuses

Items usually move through the following statuses:

### `New`
A newly submitted item that has just entered the project.

### `To triage`
The item is awaiting maintainer review, validation, classification, or clarification.

### `Backlog`
The item has been reviewed and retained for future work, but is not currently being worked on.

### `Accepted`
The item has been picked up for implementation planning or development.

### `In progress`
Work is actively underway.

### `In Testing`
Implementation is complete or nearly complete and is being tested or verified.

### `Done`
The item has been completed.

## Project fields

### Status
Tracks the workflow stage:
- New
- To triage
- Backlog
- Accepted
- In progress
- In Testing
- Done

### Priority
Tracks relative importance:
- P0
- P1
- P2

### Severity
Used mainly for bug reports:
- Blocker
- Critical
- Relatively Critical
- Not Critical

### Size
Used by maintainers to estimate overall implementation scope.

### Estimate
Used by maintainers to estimate work effort where needed.

### Iteration
Used for planning work into a time-based cycle when applicable.

### Start date / Target date
Used when items move into planned or active work.

## How maintainers should use the project

Maintainers should use the project to:

- review new community submissions
- classify issues consistently
- assess severity and priority
- decide whether an item belongs in backlog or active work
- track progress once work begins
- provide visible status to the community without exposing internal planning details

## Labels vs project fields

In general:

- **labels** classify the issue
- **project fields** describe workflow and planning state

Examples of labels:
- `type:bug`
- `feat:chat`
- `int:github`
- `nfr:performance`
- `meta:needs-info`

Examples of project field values:
- status = `To triage`
- priority = `P1`
- severity = `Critical`

See [LABELS.md](./LABELS.md) for label details.

## What community users should expect

Community users usually do **not** need to manage project fields directly.

Instead, users should:

1. open an issue in `EliteaAI/elitea_community`
2. choose the correct issue template
3. provide enough detail for triage
4. follow up if maintainers ask for more information

Once an issue is reviewed, maintainers may update its project fields and labels.

## Important notes

- Not every submitted issue or feature request will be implemented.
- Community submissions are reviewed and considered, but implementation depends on product fit, impact, capacity, and prioritization.
- Internal/private planning may continue in separate repositories or projects.

## Related files

Please also review:

- [README.md](./README.md)
- [CONTRIBUTING.md](./CONTRIBUTING.md)
- [SUPPORT.md](./SUPPORT.md)
- [LABELS.md](./LABELS.md)
- [SECURITY.md](./SECURITY.md)

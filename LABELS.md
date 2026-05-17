# Elitea Community Labels Guide

This document explains the labels used in the public Elitea community repository.

Labels help the Elitea team and community members understand what an issue is about, how it should be reviewed, and where it best fits in the product.

## Why labels matter

Labels help us:

- group similar issues and requests
- route items to the right product area
- identify integrations involved
- show triage status
- communicate whether we need more information
- highlight beginner-friendly or community-help opportunities

Labels are applied by maintainers during triage. In some cases, issue templates may also apply default labels automatically.

---

## Label groups

We use the following label groups:

- `type:*` — what kind of item it is
- `meta:*` — triage or workflow state
- `comm:*` — community-origin feedback
- `feat:*` — product area or feature area
- `int:*` — integration involved
- `nfr:*` — quality attributes such as usability or performance

---

## `type:*` labels

These labels describe the kind of issue.

### `type:bug`
Use when something is broken, incorrect, or behaving unexpectedly.

Examples:
- a button does nothing
- an action fails with an error
- output is incorrect
- expected functionality does not work

### `type:feature`
Use when requesting a new capability, enhancement, or improvement.

Examples:
- add a new workflow
- improve an existing feature
- support a new integration scenario

### `type:documentation`
Use when documentation is missing, incorrect, outdated, or unclear.

Examples:
- docs page has wrong steps
- a feature is undocumented
- examples are confusing

### `type:question`
Used for support-style questions or requests for clarification.

In many cases, these may be redirected to **GitHub Discussions**, especially Q&A or Troubleshooting categories.

---

## `meta:*` labels

These labels show the current review or decision state.

### `meta:needs-triage`
The issue is new and waiting for maintainer review.

### `meta:needs-info`
We need more details from the reporter before we can continue.

Examples:
- missing reproduction steps
- missing environment information
- unclear problem description

### `meta:duplicate`
The issue or request is already tracked elsewhere.

### `meta:invalid`
The issue is incomplete, not actionable, or not actually a product issue.

### `meta:accepted`
The issue was reviewed and accepted for internal tracking or deeper consideration.

### `meta:planned`
The request or fix is accepted and planned for future work.

### `meta:not-planned`
The issue or request was reviewed, but is not planned at this time.

### `meta:wontfix`
The team decided not to make a change for this item.

### `meta:on-hold`
The item is temporarily paused pending dependency resolution, more information, or a decision.

---

## `comm:*` labels

### `comm:feedback`
General feedback from the community.

This may be applied when an issue is more about feedback or product experience than a clearly defined bug or feature.

---

## `feat:*` labels

These labels identify the affected Elitea feature area.

Examples include:

- `feat:agents`
- `feat:agent-studio`
- `feat:agent-publishing`
- `feat:chat`
- `feat:pipelines`
- `feat:toolkits`
- `feat:extensions`
- `feat:templates`
- `feat:credentials`
- `feat:settings`
- `feat:roles-permissions`
- `feat:user-profile`
- `feat:notifications`
- `feat:attachments`
- `feat:resources`
- `feat:analytics`
- `feat:monitoring`
- `feat:voice`
- `feat:workflow`
- `feat:apps`
- `feat:login-auth`

### How feature labels are used
Maintainers add these labels during triage to indicate where the issue belongs in the product.

You do not need to choose the exact label yourself unless asked. If you are unsure, describe the problem clearly in the issue form.

---

## `int:*` labels

These labels indicate that the issue involves a specific integration.

Examples include:

- `int:github`
- `int:gitlab`
- `int:jira`
- `int:confluence`
- `int:figma`
- `int:sharepoint`
- `int:vscode`
- `int:visual-studio`
- `int:jetbrains`
- `int:oauth`
- `int:openapi`
- `int:excel`
- `int:csv`
- `int:pdf`

### When integration labels are applied
Maintainers use these labels when the issue is related to:
- connecting Elitea to another system
- importing/exporting with another platform
- plugin/extension behavior
- auth/provider connection flows
- API contract or specification issues

---

## `nfr:*` labels

These labels describe non-functional qualities of the product.

### `nfr:performance`
Used for speed, latency, scalability, or heavy resource usage problems.

### `nfr:usability`
Used when the workflow is confusing, difficult, or inefficient.

### `nfr:ui`
Used for visual issues, layout problems, or inconsistent design behavior.

### `nfr:validation`
Used for incorrect validation, weak validation, or bad error handling.

### `nfr:accessibility`
Used for accessibility issues such as:
- keyboard navigation problems
- screen reader issues
- poor color contrast
- missing semantics or labels

### `nfr:observability`
Used when the system lacks enough visibility for diagnosis, logging, metrics, or traceability.

---

## Community contribution labels

### `good first issue`
A small, approachable issue that may be suitable for first-time contributors.

### `help wanted`
The team welcomes community help or extra attention on this issue.

---

## How community users should use labels

You usually do **not** need to apply labels manually.

Instead:

1. Choose the correct issue template
2. Provide complete details
3. Search existing issues and discussions first
4. Let maintainers classify and triage the item

The clearest way to help is to write a complete, focused issue with:
- a good summary
- reproducible steps
- expected and actual behavior
- relevant environment details
- screenshots or logs if available

---

## Best practices for users

Before opening a new issue:

- search existing issues
- search discussions
- avoid duplicates
- do not post credentials or secrets
- use Discussions for questions and general conversation
- use Issues for bugs and formal feature requests

---

## Security note

Please do **not** use public issues for sensitive security vulnerabilities.

See `SECURITY.md` for the correct private reporting process.

---

## Questions?

If you are not sure whether your topic belongs in:
- an issue
- a feature request
- a discussion

start with **GitHub Discussions** or check the repository `README.md` and `CONTRIBUTING.md`.

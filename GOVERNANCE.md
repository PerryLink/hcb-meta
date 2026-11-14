# HCB governance and organization plan

## Current state (2026-11-14)

HCB lives under the **PerryLink** personal account. The official repos are listed in README. This is intentional: one maintainer, fast iteration, no governance overhead.

## Do we need an organization?

**Not yet. Yes later.** Create an organization when at least two of these are true:

1. There is a second maintainer with merge rights.
2. An enterprise or standards body needs a neutral counterparty.
3. The project receives sponsorship/donations that should not flow through a personal account.
4. A trademark or certification program is pursued.

Until then, an org is mostly overhead; a personal namespace plus a public official-repo list is enough.

## Name options (checked 2026-11-14)

| Name | Status | Notes |
|---|---|---|
| `hcb` | **taken** (GitHub user since 2011) | not available |
| `hcb-org` | **taken** (organization) | not available |
| `hcb-dev` / `hcb-ai` | taken (users) | not available |
| **`hcb-labs`** | **available** | recommended: neutral, does not overclaim a foundation |
| `dsh-hcb` | available | recommended if the project stays DSH-specific |
| `hcbhq` | available | short, but less descriptive |

Recommendation: **`hcb-labs`** for a neutral compatibility/data project; `dsh-hcb` if it is explicitly a DSH sub-project.

## If/when you create the org

1. Create the org with 2FA required; add a second owner (not only PerryLink).
2. Transfer the official repos (`hcb`, `hcb-spec`, `hcb-cli`, `hcb-action`, `hcb-data`, `hcb-gate`, `hcb-badge`, `dsh-compat-baseline`). GitHub redirects old URLs; update badges/links.
3. Keep `PerryLink` as a member; do not delete the personal repos until redirects/Pages are confirmed.
4. Add `GOVERNANCE.md`, `SECURITY.md`, `TRADEMARK.md`, `CODEOWNERS`.
5. Move Pages to a custom domain (`hcb.dev` etc.) so the URL survives future transfers.
6. Publish the official repo list and a "not affiliated with DeepSeek" notice.

## Trademark

"HCB" is currently a common-law mark, not a registered trademark. If the project reaches a standard/enterprise stage, consider registering "HCB" in class 9/42 in China; do it through counsel, not as a side task.

## What an org does *not* solve

An org does not stop someone from creating `other/hcb`; GitHub namespaces are per-owner. What actually protects the project is: a canonical repo, a spec, a data license, a public official list, and (later) a trademark. The 7 namespace repos are a defensive convenience, not a global reservation.

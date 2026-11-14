> **This repository is retired (2026-11-14).**
>
> HCB is now the **data/gate subproject of [dsh-standards](https://github.com/PerryLink/dsh-standards)**.
>
> - Rules, checker and ENTRY/FLOW/BOOST definitions: [dsh-standards](https://github.com/PerryLink/dsh-standards)
> - Compatibility matrix, tracks data, risk and `hcb-gate/1`: [dsh-hcb](https://github.com/PerryLink/dsh-hcb)
>
> This repo is archived for URL stability. Do not use it for new work.

# HCB — Host Compatibility Baseline

> The umbrella repo for the HCB family. **Canonical data lives in [dsh-compat-baseline](https://github.com/PerryLink/hcb).**
> Independent community project. **Not affiliated with DeepSeek.**

HCB answers one question for the DeepSeek Harness plugin ecosystem:

> Which host versions does this plugin declare, which ENTRY/FLOW/BOOST tracks does it claim, what capability surface does it request, and should it be piloted or reviewed?

## Official HCB repositories

| Repo | Role |
|---|---|
| [dsh-compat-baseline](https://github.com/PerryLink/hcb) | **canonical** compatibility matrix, data, collector, viewer |
| [hcb-spec](https://github.com/PerryLink/hcb-spec) | the compatibility/tracks spec and consumer mapping |
| [hcb-cli](https://github.com/PerryLink/hcb-cli) | `hcb check <package>` CLI |
| [hcb-action](https://github.com/PerryLink/hcb-action) | drop-in GitHub Action |
| [hcb-data](https://github.com/PerryLink/hcb-data) | data mirror / fetch scripts |
| [hcb-gate](https://github.com/PerryLink/hcb-gate) | gate policy (`hcb-gate/1`) |
| [hcb-badge](https://github.com/PerryLink/hcb-badge) | SVG badge generator |

**Only these repos are official HCB repos.** Any other repo using the HCB name is not affiliated; see [NAMING.md](NAMING.md).

## What HCB is not

- Not a security audit, not a certification, not a ranking.
- No total score: ENTRY / FLOW / BOOST are independent tracks.
- Declared compatibility is a claim by the package author, not a test result.

## Links

- Canonical repo: https://github.com/PerryLink/hcb
- Viewer: https://perrylink.github.io/hcb/
- Docs: https://github.com/PerryLink/hcb/blob/main/docs/TRACKS.md

## License

MIT (code), CC-BY-4.0 (data). See dsh-compat-baseline for data license.

# HCB — Host Compatibility Baseline

> The umbrella repo for the HCB family. **Canonical data lives in [dsh-compat-baseline](https://github.com/PerryLink/dsh-compat-baseline).**
> Independent community project. **Not affiliated with DeepSeek.**

HCB answers one question for the DeepSeek Harness plugin ecosystem:

> Which host versions does this plugin declare, which ENTRY/FLOW/BOOST tracks does it claim, what capability surface does it request, and should it be piloted or reviewed?

## Official HCB repositories

| Repo | Role |
|---|---|
| [dsh-compat-baseline](https://github.com/PerryLink/dsh-compat-baseline) | **canonical** compatibility matrix, data, collector, viewer |
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

- Canonical repo: https://github.com/PerryLink/dsh-compat-baseline
- Viewer: https://perrylink.github.io/dsh-compat-baseline/
- Docs: https://github.com/PerryLink/dsh-compat-baseline/blob/main/docs/TRACKS.md

## License

MIT (code), CC-BY-4.0 (data). See dsh-compat-baseline for data license.

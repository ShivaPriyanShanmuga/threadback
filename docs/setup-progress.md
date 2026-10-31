# Setup progress

Updated October 31, 2026. This records completed setup, not a working Threadback Lens.

## Verified

- Public repository: https://github.com/ShivaPriyanShanmuga/threadback.
- Development branch: `codex/threadback-v1`.
- Lens Studio **5.23.2** installed at `C:\Program Files\Snap Inc\Lens Studio\Lens Studio.exe`.
- The downloaded installer has a valid **Snap Inc.** Authenticode signature.
- The unattended installer exited with code **0** and logged "Installation process succeeded" and "Need to restart Windows? No".
- Lens Studio launches and its SPECS Base Template has been selected. Project loading/saving is still in progress.
- Official CLAD plugin `ls-clad@ls-extensions` is installed and enabled in the local Codex configuration. Its connection to a live Lens Studio project is not yet verified.
- Official `plan-lens` skill installed locally at `.agents/skills/plan-lens` (ignored by Git).

## Tooling sources

- Devpost Learn pack source revision inspected: `5d8bc0800346d38e468c29b15afcb7ca92280005`.
- Snap CLAD extensions source revision inspected: `8adedd5d5b93f9dbe55f31c6be4264a4f8a608b3`.
- [Official Lens Studio download](https://ar.snap.com/download/v5-23-2).
- [Official CLAD setup for Codex](https://developers.specs.com/docs/clad/setup/setup-ai/codex-setup).

Local installer logs and tooling downloads are in ignored `artifacts/`; credentials and machine-specific MCP configuration must remain untracked.

## Next required steps

1. Finish loading and save the real SPECS project in this repository.
2. Confirm Lens Studio login and the live MCP connection; resolve local hook approval if still shown by Codex.
3. Run the installed planning skill using the already agreed v1 choices; capture the resulting brief.
4. Build with CLAD, validate in Preview, and record genuine demo evidence.

## Preview limitation discovered during setup

The official planning pack identifies persistent spatial anchors and cross-session spatial memory as behaviors that cannot be demonstrated in the laptop preview. Same-session pause/resume is the core demonstration. Task-data storage, workspace realignment, and any across-restart claims require separate verification; do not describe them as proven simply because pause/resume works.

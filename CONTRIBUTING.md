# Development workflow

Threadback is built and maintained in this repository. Use the approved v1 scope and, once available, the official `devpost/design-brief.md` to guide work.

1. Check repository status and existing changes before editing.
2. Use a focused `codex/` branch for implementation work. Keep commits small and named for their outcome.
3. Build the Lens through CLAD and the connected Lens Studio MCP as required by the hackathon.
4. Validate the changed behavior in Lens Studio Preview. Test state transitions, persistence, and recovery where relevant, and run meaningful LEAF checks when available.
5. Update the roadmap and change history with actual results. Distinguish implemented, verified, and planned behavior.
6. Review the diff for credentials, accidental generated files, and missing project assets before publishing.

Do not replace the Lens with a browser mockup, claim tests that did not run, or describe user-confirmed progress as automatic object recognition. Maintain a repeatable simulated demo and be explicit about hardware behaviors not yet tested.

Record the source/license of third-party assets when adding them. License selection for Threadback itself remains an owner decision.

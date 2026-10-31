# Threadback

**Pick up where you left off.**

Threadback is a spatial task memory Lens for Snap SPECS. It helps you return to an interrupted hands-on task by showing what you finished, what remains unresolved, and what to do next, beside the relevant objects.

Built for [Learn AR with SPECS](https://learn-specs.devpost.com/).

## Project status

Repository and product planning are being established. The Lens has **not been implemented or tested yet**. This repository currently contains the agreed v1 scope, setup instructions, build milestones, and demo plan. A real SPECS Base Template project, the required Devpost Learn planning workflow, and CLAD connection come before implementation.

## V1 experience

1. Create a task with a few steps.
2. Place spatial markers beside relevant objects.
3. Mark steps as not started, in progress, or done.
4. Leave an unfinished-detail note, such as "Positioned, but not attached."
5. Pause, then resume with a recap and a highlighted next action.
6. Edit notes, move markers, undo mistakes, and finish the task.
7. Save progress and explicitly realign the workspace when required after reopening.

Progress is confirmed by the user. V1 does not automatically recognize objects or verify that physical work is complete. Saving task data and restoring physical alignment are separate capabilities and must be tested separately.

## Demo

The hackathon demonstration will run in **Lens Studio Interactive Preview on a laptop**, with a simulated desk and organizer parts. The operator moves with keyboard/mouse controls and uses simulated pinch interactions. A phone is not required. This scene demonstrates the interaction without claiming live recognition or a validated real-world deployment.

See [the demo plan](docs/demo-plan.md) for the planned recording.

## Development

The required build stack is Lens Studio, the SPECS Interaction Kit/UI Kit where appropriate, TypeScript, the Lens Studio MCP, and Snap's CLAD plugin. The Lens is planned using the Devpost Learn skill pack. No separate website or phone app is the hackathon deliverable.

- [V1 scope and acceptance criteria](docs/v1-scope.md)
- [Setup and required toolchain](docs/setup.md)
- [Build roadmap and current status](docs/roadmap.md)
- [Contribution and verification workflow](CONTRIBUTING.md)
- [Change history](CHANGELOG.md)

The generated `devpost/design-brief.md` will be committed after the required planning skill runs in a connected Lens Studio project. It has not been generated yet.

## Submission

- Public repository containing the actual Lens Studio project and generated planning documents.
- Public YouTube demo under three minutes showing the Lens working end to end.
- Description explaining the audience, functionality, and lessons learned.
- Current round deadline: **November 9, 2026, 5:00 p.m. Eastern**. Recheck the [official rules](https://learn-specs.devpost.com/rules) before submission.

## Ownership and third-party material

An open-source license has not yet been selected. Record third-party asset sources and their licenses before including them. Public repository visibility alone does not grant an open-source license.

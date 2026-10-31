# Threadback v1 scope

Status: user approved the feature direction on October 31, 2026. These notes preserve that agreement; they are not a substitute for the Devpost Learn skill-generated design brief.

## Intended user and moment

A person returning to an interrupted hands-on activity at a desk. The demonstration scenario is assembling a small desk organizer. The defining moment is seeing an unfinished detail beside the relevant part and knowing the next action without reconstructing the whole task mentally.

## Core features and observable acceptance criteria

| Feature | Acceptance criterion in the Lens Studio preview |
| --- | --- |
| Task creation | Create a named task and a short sequence of steps; the active task and steps are visible when requested. |
| Spatial markers | Place a marker beside a workspace object, move around the scene, and see it remain at that scene location; reposition it when needed. |
| Step states | Set a step to not started, in progress, or done; use a text/icon label as well as color. |
| Unfinished details | Add and edit a note associated with a step/marker without treating the step as complete. |
| Pause | Save a snapshot of the current step, last completed step, unresolved notes, and next action; pausing does not complete anything. |
| Resume | Show the saved context and highlight the relevant marker; dismiss the recap to return to a quiet workspace. |
| Corrections and completion | Undo an accidental state change, edit a note, move a marker, and finish a task without leaving stale markers visible. |
| Persistence and realignment | Restore task content after a supported Lens restart; ask for workspace realignment before showing restored markers as aligned. Verify this separately from same-session pause/resume. |

## Interaction and layout

- Prefer standard Interaction Kit pinch/select and drag interactions with large targets.
- Keep markers beside relevant objects; avoid a dashboard stuck to the wearer's face.
- Only expand detailed text on request or during the resume recap.
- Start with one active task; multiple simultaneous tasks are outside the initial scope.
- Provide an explicit reset for repeatable demonstrations.
- Decide text entry using the actual UI Kit/preview capabilities during the design workflow. A prepared demo task may help recording, but must not be presented as proof of free-form creation or editing.

## Explicit scope limits

No automatic object recognition, automatic completion detection, unverified physical measurements, construction guidance, shared accounts, or cross-device synchronization. Voice notes are optional after the complete v1 flow works; every core action must have a preview-compatible control.

## Evidence required before claiming completion

- Successful preview walkthrough from task creation through interruption, resume, correction, and completion.
- Storage/reload and alignment checks, including a clearly signaled unaligned state.
- Preview logs checked for relevant errors.
- Meaningful LEAF tests where supported; record what actually ran and its result.
- A screen recording demonstrating the real Lens implementation, with simulation clearly identified.

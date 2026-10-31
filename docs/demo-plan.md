# Demo plan

Status: planned, not yet recorded or verified against a working Threadback Lens.

## Demonstration method

Use Lens Studio's SPECS simulation and Interactive Preview on the laptop. Build a small simulated desk scene with organizer parts as context. These are virtual props for demonstrating spatial placement, not an object-recognition system.

The operator moves the simulated viewpoint with keyboard and mouse controls and activates standard simulated hand/pinch interactions. The hackathon FAQ explicitly permits this workflow. Record the working preview using Lens Studio's recording control or a desktop recorder.

A phone moving around a real desk does not automatically drive the SPECS preview or supply usable world tracking. Real device behavior and persistent physical anchors remain separate validation work.

## Planned video, target 2 minutes 30 seconds

| Time | What the viewer sees |
| --- | --- |
| 0:00-0:10 | Working Lens immediately: resume an interrupted task and highlight the unfinished divider. Label footage "Lens Studio SPECS simulation." |
| 0:10-0:25 | Explain the problem: a checklist says what to do; Threadback preserves the exact unfinished detail and where it matters. |
| 0:25-0:55 | Start the organizer task, place a marker, and update step states using the implemented controls. |
| 0:55-1:15 | Add "Divider positioned, not attached," pause, and move the simulated viewpoint away. |
| 1:15-1:50 | Return, resume, read last completed / unfinished / next action, and select the relevant spatial marker. |
| 1:50-2:10 | Show a correction or undo and then complete the task; markers recede. |
| 2:10-2:30 | Briefly show genuine planning/build evidence and explain what was learned and the prototype's limits. |

## Recording controls

Snap's current documentation lists movement with WASD/arrow keys, Q/E for vertical movement, right-mouse dragging to look around, and the scroll wheel to move forward/backward. Verify the exact controls and simulated pinch mapping in the installed Lens Studio version before recording. The preview has a screen-recording control.

## Recording checklist

- Show actual working behavior; do not substitute a concept animation for the Lens.
- Show simulation clearly and avoid implying physical object recognition or glasses testing.
- Keep text readable and keep the working Lens visible in the first ten seconds.
- Rehearse the full sequence without runtime errors.
- Check audio, final duration under three minutes, and video permissions before submission.
- Upload publicly to YouTube only when the user authorizes publication of the completed video.

## Sources

- [Hackathon FAQ: simulated hands, pinch, camera, and world mesh](https://learn-specs.devpost.com/details/faqs)
- [Snap: SPECS/Spectacles preview panel](https://developers.snap.com/spectacles/get-started/start-building/preview-panel)
- [Snap: interactive preview controls and recording](https://developers.snap.com/lens-studio/lens-studio-workflow/previewing-your-lens)

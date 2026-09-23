# Vibe Tycoon demo video script

**Status:** Human-editable working script for the current 45-second silent browser preview. It is not the final Shipaton submission script: the video footage is a mobile-size Playwright browser capture, not footage from the target phone.

**Audio:** Silence. No voiceover, music, or sound effects. The gameplay recording is muted; the captions carry the story.

Edit this Markdown script directly. Keep the copy factual and aligned with the visible gameplay. The timecodes below match the current preview.

| Time | Picture and action | On-screen script |
|---|---|---|
| 00:00–00:05.9 | Open on Vibe Tycoon’s first-run studio screen. Enter the studio and show the live game. | **Open a studio and start from zero.** |
| 00:05.9–00:08.2 | Show Home and the first active job. | **Choose the first job.** |
| 00:08.2–00:13.0 | Tap through the active brief; let the job complete in the live game. | **Tap through the brief. Finish the work.** |
| 00:13.0–00:20.0 | Hold through the completion notices and payout flow. | **A completed job pays your studio.** |
| 00:20.0–00:27.7 | Show the earned 125 Cash and the 60 Cash agent price, then install the agent through the game UI. | **125 Cash earned · Agent costs 60 Cash** |
| 00:27.7–00:31.6 | Show the newly installed agent and return to Home. | **Hire your first agent.** |
| 00:31.6–00:45.0 | Leave the game untouched while the agent advances the next job. | **The agent advances the next job hands-free.** |

## Human editing notes

- Edit the timecodes, action notes, and on-screen copy in this file; this is the human-readable script.
- The current local HyperFrames composition is `renders/index.html` (ignored by Git). To reflect script edits in this preview, update the matching caption element text and its `data-start` / `data-duration`, then render again from `renders/` with the pinned HyperFrames CLI.
- Keep the preview-only banner while the source is browser footage. Remove it only after genuine footage from the supported target phone replaces that capture.
- For the competition cut, use the real-device capture sequence and checks in [VIDEO_PLAN.md](VIDEO_PLAN.md). Keep the essential video under two minutes and use only original or cleared material.

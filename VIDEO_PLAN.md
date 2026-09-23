# Vibe Tycoon — Shipaton device demo

**Viewer promise:** Can one prompt grow into a software studio that keeps working on its own?

**Story:** Start with the player moving a live job by hand. Show the job visibly finish and pay out. Use that earned Cash to install an agent, then let the same game advance without touch. The payoff is the transition from hands-on prompting to an idle team.

**Cut target:** 90 seconds · **Hard edit ceiling:** 110 seconds · **Frame:** portrait 1080 × 1920 · **Capture:** Vibe Tycoon running on an Android phone.

This is a capture plan, not a finished or submission-ready video. Film the current submission build on a real supported phone. Use normal-speed gameplay and cuts only; do not mock screens, seed or edit save data, or imply that progress happened faster than it did.

## Capture-ready storyboard

| Time | Shot / player action | Required live evidence | Caption / optional original VO |
|---|---|---|---|
| 0–3 s | **Hook — Home.** Start on the active job card; tap the prompt area once. | The on-screen prompt count or progress bar visibly advances in the real app. Use the phone's native touch indicator only if it is available. | **Caption:** “One prompt moves the job.” |
| 3–18 s | **Work — Home.** Continue prompting the same job at a readable pace. | Show the job name, prompt count, and progress moving together. Frame the phone UI large enough to read; do not cover the progress bar with captions. | **Caption:** “Every prompt pushes this job forward.” **VO:** “Start with a prompt. Keep the work moving.” |
| 18–31 s | **Payout — Home.** Complete the active job. Hold through the payout and the next job rolling in. | The same capture must show the completed job, Cash credited where the player can see it, and the next job becoming active. Do not cut across the payout. | **Caption:** “Finish the job. Earn Cash. Take the next brief.” **VO:** “Finish the job, collect the payout, and the next brief is ready.” |
| 31–46 s | **Build the team — AI.** Open AI, install one affordable agent with earned in-game Cash, and show the updated roster. | Show the real Install Agent action, Cash spent, and agent count increasing. Use the normal game flow; no debug controls or edited save values. | **Caption:** “Hire an agent to automate the prompts.” **VO:** “Then put your earnings back into the team.” |
| 46–70 s | **Idle payoff — Home.** Return Home and take both hands off the device. | In one continuous normal-speed take, show the live job progress advancing from agent prompts with no taps. Include the agent/desk visual if it is visible in this build. Do not speed-ramp the footage. | **Caption:** “Your agents keep the studio moving.” **VO:** “Now the team keeps prompting while you plan what to build next.” |
| 70–82 s | **Proof — Stats, if readable on the captured device.** Show the Growth view briefly, then return Home. | Use only values/charts that are present in the recorded app state. If the charts are empty, too small, or interrupt the story, stay on Home and continue the hands-free shot instead. | **Caption:** “Watch the studio grow.” No spoken numbers unless they are legible and verified in the footage. |
| 82–90 s | **Button — Home.** Leave the real game visible with progress still moving. | End on functioning gameplay, not a standalone logo card. Add the game name as a short, original text overlay in safe space. | **Caption:** “Vibe Tycoon — build your studio one prompt at a time.” |

## Recording setup

1. Install the same Android submission build that judges will receive. Confirm its version/build before recording and keep that build for every take.
2. Use a real on-device save earned through ordinary play. Before filming, leave the player with **zero agents**, Cash just below the first-agent price, and an active job whose visible payout will make that agent affordable. This lets the next shot spend the Cash earned on camera. Do not use debug menus, edited saves, or fabricated balances. If this exact state is not naturally available, revise the sequence to match the state the build can genuinely demonstrate.
3. Dismiss tutorial, milestone, and system prompts only through their real controls before a take. Keep the actions that make up the demonstration visible; never cut around a blocked or failed action and present it as successful.
4. Record the portrait screen directly from the phone at its native supported resolution. Capture one uninterrupted master take with system notifications hidden and game audio muted. Keep the original capture as the source footage.
5. Review every frame for third-party trademarks or logos inside game artwork, notification banners, status bars, or overlays. If any appear, choose a different in-game job/art state or re-capture; do not blur or crop away required gameplay evidence.

## Edit and sound

- Keep captions on-screen for sound-off viewing. Use large, high-contrast original typography in clear space; never obscure the prompt control, progress, payout, or agent count.
- The script above is optional original narration. If no clean original recording is available, use captions and silence. Add no stock footage, third-party logos, copyrighted music, or unlicensed sound effects.
- Use straight cuts between screens. Keep the active job and the payout in continuous footage so the cause and result remain clear. Trimming repeated taps is fine only when the visible counters and elapsed action still make sense.
- Keep the target at 90 seconds and the final essential footage at or below 110 seconds, safely under the two-minute limit.
- Render the final local MP4 to `renders/`. Public YouTube/Vimeo upload and providing its link on the submission form are separate actions that require explicit approval for the exact video and destination.

## Final review checklist

- [ ] The opening action is visible in the first second; no logo intro or empty establishing hold.
- [ ] The capture shows the app running on the intended Android phone, not a browser mockup or reconstructed UI.
- [ ] A prompt visibly advances the job; the same job completes, pays Cash, and rolls to another job.
- [ ] Installing an agent succeeds through the actual UI and updates the roster.
- [ ] Hands-free progress is recorded at normal speed with no touch input during the proof.
- [ ] Every overlay describes behavior actually visible in the shipped build; no hidden steps are represented as instant.
- [ ] No unlicensed third-party trademarks, logos, music, or other copyrighted material appear.
- [ ] Captions remain readable at phone size and do not cover important controls or results.
- [ ] Final runtime is no longer than 110 seconds; check the exported file's actual duration.
- [ ] Watch the export once muted and once with its chosen audio before upload.

## Source basis

The gameplay claims follow the current `origin/main` source inspected at `136dbd8d2f20b0486af95a8477e2370c612ca736` (app package version 1.3.0), including `src/ui/GameScreen.tsx`, `src/ui/prompt-keyboard.tsx`, and `scripts/playtest.cjs`, plus PAPI decisions AD-54, AD-55, and AD-58. Re-check the capture against the actual submission build before editing; source code alone does not prove that a specific device take succeeded.

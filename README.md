# Vibe Tycoon Shipaton demo

This repository holds the HyperFrames project for the Shipaton submission demo. It is a scaffold, not a finished or submission-ready video. The initial composition is an empty 10-second placeholder.

## Project setup

- HyperFrames CLI: pinned to `0.8.62` for repeatable preview and render commands.
- Canvas: portrait `1080 × 1920`, matching Vibe Tycoon's mobile orientation.
- Add captured, shipped game footage under `assets/device-footage/` and any documented, cleared audio under `assets/cleared-audio/`; see [VIDEO_PLAN.md](VIDEO_PLAN.md).
- Keep the essential demo below 120 seconds; the shot plan targets 110 seconds.

## Commands

Run these from the repository root:

```powershell
npm run dev
npm run check
npm run render -- --output renders/vibe-tycoon-demo.mp4
```

The render output is local. The submission copy still needs an authorized YouTube or Vimeo upload and a link entered on the Shipaton form.

## Submission requirements

The final video must show the real app running on its intended phone, match current shipped behavior, contain no third-party trademarks or uncleared copyrighted material, and stay under two minutes. Do not present the scaffold or a simulated screen as gameplay evidence.


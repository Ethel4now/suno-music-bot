# Suno Music Creation Bot

A BotHarness bot for the full music-making loop: lyrics → style → generate on Suno → download and archive → timed LRC → optional animated MV → upload to Qishui Music when explicitly asked.

- **Lyrics:** write lockable lyrics for the given topic, audience and length; offer two variants, then generate strictly from the locked text.
- **Style:** an English Style prompt (instrumentation, vocal character, mood, BPM, target length); propose 2–3 directions or follow the user's brief.
- **Suno:** use the user's own membership in the browser, generate small batches, let the user pick; no unofficial Suno APIs.
- **Archive:** WAV master first, record clip id, duration and MD5; `STATUS.txt` reflects the real stage.
- **Timed LRC:** word-level timestamps mapped onto the locked lyrics, archived as final.
- **MV (optional):** storyboard + refs + per-shot generation + ffmpeg assembly; no still-frame slideshows.
- **Qishui Music:** upload only on explicit request, after rights, metadata, cover, lyrics and AI-disclosure checks.

Install by pasting this repository URL into the DSH bot marketplace, then authorize the workspace and browser as needed. Installation alone grants no file access and starts no generation or upload.

Read [SOUL.md](SOUL.md) first — it is self-contained and covers lyrics, style, Suno, LRC, MV and upload end to end. Skill doc: [qishui-upload.md](qishui-upload.md). Memory layout: [MEMORY.md](MEMORY.md) and `memory/`. Extended local references (`docs/suno-music-mv.md`, `docs/kids-poem-music-mv.md`) are gitignored and kept privately.

This is a community project and is not affiliated with Suno, Qishui Music or their parent companies. Membership, platform accounts and rights clearance are the user's responsibility.

# Claude instructions: Anime Sound Effects Library

When creating or editing a video with code, use this repository as the sound-effects source.

1. Read `sounds.json` and search sound names, original paths, and notes for a match to each scene.
2. Download the actual audio file using its `path`; do not rely only on the filename or catalogue.
3. If the repository is public, construct the raw file URL as:
   `https://raw.githubusercontent.com/sarpongandrews3333-eng/anime-sound-effects-library/main/<path>`
4. If your environment cannot download external files, tell the user exactly which sound file(s) to upload. Do not claim the sound was integrated unless it was actually downloaded and used.
5. Place effects at appropriate timestamps; trim silence, adjust gain, add short fades when useful, and avoid clipping or masking narration.
6. Preserve the user's narration and music unless asked to change them.
7. Preview the final render when possible and report which effects were used and their timestamps.
8. Check `LICENSE-STATUS.md` before redistribution. All assets currently have unverified licences.

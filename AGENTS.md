# Professional Learning publication guidance

- The GitHub repositories are the master copies. Before publishing updates, run `git pull --rebase` in the relevant repository and work from its current pages.
- Do not regenerate `index.html` or `resources.html` from older local output folders or templates. Make bounded edits to the maintained repository pages.
- The Primary reference is `CraigWrenasmir/phase-5-primary-education`. Preserve changes made there by other collaborators.
- Embedded video playback uses same-site `media/session-1.mp4` through `media/session-6.mp4`. Web encodes must be under 100 MB each, H.264 High, AAC, and faststart. Keep each entire Pages site under its size limit.
- In workshop data, `video` is the same-site playback file and `download` is the full-quality GitHub Release URL. The download link uses `next.download || next.video`. GitHub Release media is for downloads only; never use it as the embedded player source. Full workshop videos stay in Releases.
- Keep the Positive Partnerships branding: dark purple `#330044` header with right-hand dot flourish and a 6 px `#712d90` bottom border, primary purple `#712d90` links and accents, `#e0d3e7` borders, `#f5f2f6` light panels, white cards with 8 px radius, Arial / Helvetica Neue, and headings at weight 400.
- Use the supplied `assets/pp-logo-white.svg` beside “Phase 5 · Professional Learning”. Page titles end with “· Positive Partnerships”. Do not restore the former navy/teal palette or four-square mark.
- Use plain hyphens in page copy, including dynamically displayed titles, labels and captions. Do not use em dashes or en dashes. Preserve original supplied resource files and their URL filenames.
- Preserve the caption switching fix, accessible controls, timed activity prompts, slide navigation, source gap notes and per-workshop playback storage.

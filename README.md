# Zora Reign — Concrete Honey

A complete, responsive fictional Black woman neo-soul / hip-hop artist website by Bklyn Custom Designs®.

## Start exploring
Open `index.html` in your browser. No dependencies, installation, build command, or external runtime scripts are required. For development, use VS Code Live Server or `python3 -m http.server 8000` in this folder.

## Included experiences
- Original fictional artist campaign portrait and biography.
- Concrete Honey album sleeve with a silver rotating CD revealed behind it. Pause/resume control and reduced-motion support.
- Release date: December 25, 2026. The countdown targets midnight America/New_York (05:00 UTC).
- Six streaming platform icons: Spotify, Apple Music, YouTube Music, TIDAL, Amazon Music, and SoundCloud. Links open platform homepages; replace them with verified release URLs for a real artist.
- Two original 24-second instrumental sketches with play/pause, seeking, measured waveform bars, elapsed/duration indicators, and exclusive playback. Starting one pauses the other. No auto-play. Native audio controls remain available if JavaScript is disabled.
- Tour-coming-soon and Brooklyn pop-up announcement sections.
- Fan form with optional ticket entry, validation, consent, and a personalized preview confirmation. **It does not send or store personal information.**
- Privacy, giveaway details, and custom 404 pages.

## Publish on GitHub Pages
1. Create a public GitHub repository called `zora-reign`. Suggested description: `A modern neo-soul artist website featuring original artwork, interactive audio previews, an animated album/CD presentation, and a fan-entry experience. Built by Bklyn Custom Designs®.`
2. Upload the contents of this folder at the repository root. `index.html` must sit beside `assets/`, rather than inside another nested folder.
3. Open repository **Settings → Pages**. Under Build and deployment choose **Deploy from a branch**, then **main** and **/(root)**, and Save.
4. Once GitHub finishes deploying, use the URL shown there: `https://YOUR_USERNAME.github.io/zora-reign/`.

Terminal route, after creating an empty repository:
```bash
cd /path/to/zora-reign
git init -b main
git add .
git commit -m "Build Zora Reign artist website"
git remote add origin git@github.com:YOUR_USERNAME/zora-reign.git
git push -u origin main
```
Replace YOUR_USERNAME and the local path. Use GitHub's supplied HTTPS remote instead if you do not use SSH. No remote repository or deployment is created by this package.

## Adapt it to an actual artist
Edit copy in `index.html`; palette, layouts, and CD animation in `assets/styles.css`; countdown, waveform data, and form behavior in `assets/app.js`. Replace the artwork and music with rights-cleared artist assets. Update every platform URL. Replace demo form handling with a properly configured signup integration and real giveaway terms before inviting actual entries. Never put service credentials or fan records in a public repository.

## Audio and artwork
Both clips are newly composed instrumental sound-design sketches (synthesized keys, bass, drums, and lead textures), not recordings of the reference artists, not vocal imitations, and not commercial mastered songs. Source WAV versions are included for editing. Each embedded MP3 is 24 seconds. Waveform data derives from those sketches. Artwork was generated for this fictional artist with the built-in image-generation tool. See CREDITS.md for assets, prompt, and icon sources.

## Files
`index.html`, `privacy.html`, `giveaway.html`, `404.html`; `assets/styles.css`, `assets/app.js`, `assets/artist.jpg`, `assets/favicon.svg`, six platform SVG icons, two MP3s and two WAVs, waveform JSON, README, CREDITS, LICENSE, .gitignore, .nojekyll.

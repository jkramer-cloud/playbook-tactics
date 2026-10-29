# Playbook Tactics — Basketball v2.1

Standalone GitHub Pages game. Replace the repository root `index.html` with the supplied version.

## What changed
- Corrected SVG pointer coordinate scaling at different screen sizes and fixed drag pointer capture.
- Drag placement uses minimum token spacing to limit overlapping players.
- Adjusted starting 5-on-5 spacing.
- Added optional reactive computer defenders during play animation (man-to-man and simplified zone tracking).
- Added scrollable saved-play cards, loading directly from the gallery.
- Added New play, optional arrow visibility, improved reset and play controls.
- Rebuilt all 12 Training Camp demonstrations with lesson-specific offensive and defensive movement, narrated steps, and visible ball transfers.
- Coaching instructions explain blue offense, red defense, and ball holder; questions unlock after watching each demonstration.
- Preserved the original 12 lesson subjects, progression, save key, saved plays, import and export.

## Training Camp
Select Watch demonstration to see the tactic unfold with a narrated sequence on the court. After the demonstration, answer the coaching question. Replay as needed.

## Controls
Open Play Designer; drag tokens in Move players mode. Select a tool, click an offensive token, then click the destination or another offensive player for a pass. Toggle computer practice and click Animate play. Name and save to store plays in the scrollable gallery. Export JSON to transfer between devices.

## Scope
The computer is a **reactive practice defender**, not a rules-complete basketball AI. It tracks offensive movement during animation, not a live competitive match. Browser data is stored locally.

## Deploy
Upload `index.html` and `README.md` to https://github.com/jkramer-cloud/playbook-tactics (root). GitHub Pages: https://jkramer-cloud.github.io/playbook-tactics/. The Learning Hub launch link does not need changing if it already points there.

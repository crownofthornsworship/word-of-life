# Word of Life — Improvement Roadmap

## Product goal

Make the handcrafted Bible word journey feel polished, fair, and replayable without turning it into an ad-driven mobile word clone.

## Phase 1 — Input and puzzle reliability

- Regression-test all 25 boards for repeated letters, two-letter words, drag reversal, fast taps, and accidental finger drift.
- Add a visible path preview and a forgiving touch radius that never selects the wrong duplicate letter.
- Prevent valid words from failing because of animation timing or pointer cancellation.
- Add puzzle validation tooling so every board is solvable before release.

## Phase 2 — Progression and variety

- Add themed mechanics gradually: branching paths, locked letters, reveal tiles, bonus words, and short phrase finales.
- Expand each chapter with optional challenge boards and a chapter mastery reward.
- Improve the daily challenge with a calendar streak that never punishes missed days.
- Add a parent-friendly story collection for replaying unlocked Scripture cards.

## Phase 3 — Presentation

- Add chapter-specific board frames, letter effects, success animation, and restrained sound themes.
- Improve story art transitions and make completed words contribute visually to the scene.
- Refresh hint, shuffle, selection, and completion feedback for small screens.

## Phase 4 — New content

- Expand from five chapters to a larger journey while preserving handcrafted puzzle quality.
- Add mini word challenges between chapters: missing word, scrambled verse theme, and picture clue.
- Add an end-of-journey celebration and replayable mastery page.

## Release gate

- Automated board validation plus complete manual playthrough on small phone, tablet, and desktop.
- Verify tap/drag parity, screen reader labels, reduced motion, sound, read-aloud, saves, reset, and daily rollover.
- Refresh `og.png`, metadata, README, Light & Life Games, and Salt & Light Web Studio.


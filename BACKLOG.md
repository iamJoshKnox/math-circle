# Math Circle Games — Improvement Backlog

Tracking improvements to the 9 interactive browser games in `/games/`.
Each game is a self-contained HTML file (no build tools, no dependencies).

**Target audience**: 7-8 year olds on school Chromebooks.

---

## Status Key

- [ ] Not started
- [x] Done
- [~] In progress

---

## 1. Cross-Cutting (All Games)

### 1.1 Session Persistence (localStorage)
Save progress so kids don't lose their place on page reload.
- [x] 01-odd-one-out
- [x] 02-symmetry-mirror
- [x] 03-logic-deduction
- [x] 04-tower-of-hanoi
- [x] 05-dice-roller
- [x] 06-magic-square
- [x] 07-euler-explorer
- [x] 08-code-breaker
- [x] 09-floor-plan

### 1.2 Back-to-Hub Navigation
Add a visible "Back to Games" link/button so kids can return to `index.html`.
- [x] 01-odd-one-out
- [x] 02-symmetry-mirror
- [x] 03-logic-deduction
- [x] 04-tower-of-hanoi
- [x] 05-dice-roller
- [x] 06-magic-square
- [x] 07-euler-explorer
- [x] 08-code-breaker
- [x] 09-floor-plan

### 1.3 Hint Systems
Add contextual hints to games that don't have them.
Games that already have hints: 06-magic-square, 08-code-breaker.
- [x] 01-odd-one-out
- [x] 02-symmetry-mirror
- [x] 03-logic-deduction
- [x] 04-tower-of-hanoi
- [x] 07-euler-explorer
- [x] 09-floor-plan

### 1.4 Keyboard Navigation
Support basic keyboard controls so mouse isn't required.
Each game has a keyboard legend (auto-hidden on touch devices) and visible focus indicators.
- [x] 01-odd-one-out — Arrow/number keys to select items, Enter to confirm, H hint, N next
- [x] 02-symmetry-mirror — Arrows to move grid cursor, 1-6 paint colors, E eraser, Enter check, H peek
- [x] 03-logic-deduction — Left/Right between creatures, Up/Down cycle options, Enter select, H hint, N next
- [x] 04-tower-of-hanoi — 1/2/3 select pegs, H hint, R reset, Left/Right change disk count
- [x] 05-dice-roller — Space/Enter roll, T 10x, H 100x, 2-9/0/-/= predict sums, R reset
- [x] 06-magic-square — Arrows move grid focus, 1-9 place numbers, Backspace remove, H hint, C clear
- [x] 07-euler-explorer — Left/Right cycle shapes, Tab between inputs, Enter check, H hint
- [x] 08-code-breaker — Left/Right between substitution inputs, Up/Down switch puzzles, H hint
- [x] 09-floor-plan — Arrows move grid cursor, 1-9 select furniture, R rotate, Enter place, Delete remove, P peek, C clear

### 1.5 Sound Effects
Add optional audio feedback (success chimes, clicks, dice rolls).
Respect system mute. Include a mute toggle.
- [ ] All games

### 1.6 Onboarding / Tutorial
Show a brief "How to Play" overlay on first visit (dismissible, stored in localStorage).
- [ ] All games

### 1.7 Reduced Motion / Colorblind Mode
Respect `prefers-reduced-motion`. Offer a colorblind-safe palette toggle.
- [ ] All games

---

## 2. Per-Game Improvements

### 01 Odd-One-Out
- [ ] Difficulty progression (more attributes per object in later puzzles)
- [ ] Let kids create their own "odd one out" sets
- [ ] Add more puzzle sets (currently 12)

### 02 Symmetry Mirror
- [ ] Diagonal mirror lines (harder mode)
- [ ] Show solution preview after failed attempt
- [ ] More level variety in patterns

### 03 Logic Deduction
- [ ] Track which clues have been "used" (visual indicator)
- [ ] Highlight contradictions in assignments
- [ ] Difficulty indicator before selecting puzzle

### 04 Tower of Hanoi
- [ ] Solution replay (step-by-step optimal solve)
- [ ] Explain the 2^n - 1 minimum moves pattern
- [ ] Timer / speed challenge mode

### 05 Dice Roller
- [ ] Overlay theoretical probability curve on chart
- [ ] "Blind prediction" mode — hide chart until 50+ rolls
- [ ] Explain why 7 is most common (combination counting)

### 06 Magic Square
- [ ] 4x4 variant for advanced kids
- [ ] Explain why the magic sum is 15
- [ ] Show all valid solutions (rotations/reflections)
- [ ] Undo button (not just clear all)

### 07 Euler Explorer
- [ ] 3D rotation (drag to spin shapes)
- [ ] More shapes: dodecahedron, icosahedron
- [ ] Shapes that break the formula (cylinder, torus) for discussion
- [ ] Better mobile canvas interaction

### 08 Code Breaker
- [ ] Connect messages into a story / treasure hunt
- [ ] Add Atbash cipher variant
- [ ] Show "common English words" as a hint strategy

### 09 Floor Plan
- [ ] Undo button (not just clear all)
- [ ] Show grid coordinates on hover
- [ ] Camera rotation in 3D view
- [ ] Snap-to-grid guide lines while placing

---

## 3. Infrastructure

- [ ] Parent/teacher progress dashboard (reads localStorage from all games)
- [ ] Print-friendly mode for puzzle states
- [ ] Automated visual regression tests

---

## Implementation Notes

- All games are single-file HTML (inline CSS + JS). Keep it that way — no build step, no dependencies. Teachers open these directly in a browser.
- Use `localStorage` with keys namespaced per game: `mathCircle_01_progress`, etc.
- Keep the existing visual style (gradients, emoji, confetti). Don't redesign.
- Test on Chrome (Chromebook target). Safari/Firefox are nice-to-have.
- All text should be readable by 2nd graders. Keep instructions short.

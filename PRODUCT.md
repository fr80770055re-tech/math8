# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Existing single-file `index.html` using Tailwind via CDN, no build step. User confirmed it stays this way.

## Users

Teacher/parent who generates a set of math problems, and elementary students in grades 3–6 (中高年級) who copy the problems by hand into a 數學8格本 (8-grid math notebook) and solve them there. The screen is a source to copy from, not the place answers are entered.

## Product Purpose

作業繳交小幫手 – 綜合數學出題. Generates randomized practice problems for homework: vertical multiplication/division, simplification/mental calculation, time conversion, factors, multiples, common factors/multiples, mixed factor-multiple sets, range-limited factors, and unlike-denominator fraction add/subtract. Success: a student can copy each problem cleanly into the 8-grid notebook and complete it, and the teacher can quickly regenerate, adjust, and save sets.

## Positioning

Problems are shaped for copying into an 8-grid notebook (vertical layouts, optional horizontal-form scaffolding hints that never reveal answers), tuned to Taiwanese elementary curriculum units.

## Operating Context

Used in a browser to produce a problem set; students transcribe by hand. Includes per-problem refresh, a history of saved sets that can be reloaded, a scaffold (鷹架) hint checkbox, and difficulty controls (digit counts, trailing-zero speed drill).

## Capabilities and Constraints

- Unit selector with basic vertical units (mix/mul/div) and special units (simplify, time, factors, multiples, common factor, common multiple, factor-multiple mix, factor range, fraction).
- Digit-count options for dividend/divisor and a "trailing 0" option.
- Scaffold hints shown without answers; answers left blank.
- Save current set to history and reload it.
- UI language: Traditional Chinese (Taiwan).
- Single static HTML file; no backend.

## Brand Commitments

Name: 作業繳交小幫手. Traditional Chinese copy, Taiwan math terminology.

## Evidence on Hand

Only the app itself (`index.html`). No testimonials, usage data, or external references exist; do not fabricate any.

## Product Principles

- Output must be easy to copy by hand into an 8-grid notebook; clarity of digits and layout beats decoration.
- Never reveal answers in hints; scaffolding supports reasoning only.
- Math content must stay correct and curriculum-appropriate for grades 3–6.
- Teacher workflow is fast: generate, tweak, save, reload with minimal steps.

## Accessibility & Inclusion

Readable for children: large, unambiguous numerals and Traditional Chinese text. No further requirement established.

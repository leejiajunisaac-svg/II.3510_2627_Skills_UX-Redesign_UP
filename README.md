# II.3510 — Topic #16: SwapCampus UX/UI Redesign (Unfinished Exercise)

## Objective
Upgrade this single-column KMP/Compose Multiplatform prototype into an ergonomic, accessible, Apple-inspired campus marketplace in `shared/src/commonMain`.

## Exercise Tasks (`// TODO`)
1. **WCAG AA Color System (`Theme.kt`)**: Implement Coral-Red (`#D92B2B`), Mint-Teal (`#006B5E`), and layered neutral surface tokens.
2. **Bilingual FR/EN & Euro Formatting (`ListingsScreen.kt` / `Formatters.kt`)**: Add a live `FR`/`EN` header toggle and locale-aware Euro formatting (`€25.00` vs `25,00 €`).
3. **2-Column Storefront Grid (`ListingsScreen.kt`)**: Convert `LazyColumn` into a 2-column `LazyVerticalGrid` with 1:1 media cards, spring press physics (`0.97f`), and animated status badges.
4. **Ergonomic Thumb Dock & Accessibility X-Ray (`ListingsScreen.kt`)**: Move search and category filter chips into `Scaffold.bottomBar` and verify `>= 48×48 dp` touch targets.

## Reference Solution & Slides
- **Completed Demo Repo**: https://github.com/leejiajunisaac-svg/II.3510_2627_Skills_UX-Redesign_DP
- **Presentation Slides**: Included in this repository root (`.pptx`).

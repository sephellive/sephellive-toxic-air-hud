# Changelog

## 1.6.1
- Reduced the BHS toxic-air bar to the original 3-pixel thickness while retaining the BHS width.

## 1.6.0
- Reduced the BHS toxic-air bar to a thin 71x4 line and scaled the left mask icon to match.

## 1.5.0
- Added a direct `ui_toxic_air_16.xml` override for the BHS option, so the base Toxic Air include chain cannot restore its original right-side mask icon.

## 1.4.0
- Replaced the unsupported long dash in English and Russian live-positioning headings with a safe hyphen.

## 1.3.0

- Refined the BHS layout: matching 71x10 bar proportions, left-aligned smaller mask icon, and even stack spacing.

## 1.2.0

- Fixed live Draggable movement by updating the real Toxic Air HUD instance rather than an isolated script reference.
- Fixed the BHS layout by applying its anchor inside the original Toxic Air HUD implementation.

## 1.1.0

- Added English and Russian localisation for the Draggable MCM page and controls.
- Replaced the inactive preview button with a live in-game X/Y positioning controller.
- Fixed BHS integration so it overrides Toxic Air's default position reliably.

Document notable addon changes here when needed. GitHub generated release notes provide the per-release commit summary.

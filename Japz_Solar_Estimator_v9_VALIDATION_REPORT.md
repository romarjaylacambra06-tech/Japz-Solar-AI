# Japz Solar Estimator v9 — Validation Report

Date: 2026-10-18

## Automated checks completed

- JavaScript syntax check: PASS (`node --check`).
- Chromium runtime test using embedded page content: PASS; no uncaught JavaScript page errors across tested flows.
- Diagram rendered: PASS.
- Animated SVG particles generated: PASS.
- Motion pause/resume, speed update and replay controls: PASS.
- Design update after changing PV module quantity: PASS.
- Day/night/grid-outage scenario selector and explanatory narrative: PASS.
- System-type change redraws the diagram: PASS.
- All five built-in profiles exercised without uncaught runtime errors: `micro100`, `sub1k`, `starter`, `balanced`, `expand`.
- Portable project JSON export: PASS (download generated as `JapzSolarEstimator_Project.json`).
- Portable project JSON import: PASS (test file restored system type, panel quantity and appliance load).
- Build summary rendered: PASS.
- Responsive viewport check at 390 px: PASS; no horizontal body overflow.
- Duplicate HTML IDs: none detected.

## Scope of testing

These tests cover selected interface flows and basic app runtime behavior. They do not exhaust every possible input combination, validate all manufacturer data, or certify electrical calculations. No field installation or electrical compliance certification was performed.

## Important limitation

The animated diagram is an illustrative conceptual energy-flow simulation. It does not represent measured electrical telemetry, physical cable routing, protection coordination, or an approved construction drawing. Component prices are planning estimates unless explicitly confirmed by a current seller quotation. Final equipment selection and installation require verification against exact product documentation, site conditions and applicable Philippine requirements.

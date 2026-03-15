---
layout: default
title: Changelog
description: Version history for Backyard Sap Tracker.
---

# Changelog

## v1.6.0

### Bug Fixes

- **Season filtering for boils** -- The Gal Boiled widget now correctly totals only the selected season. Boil dates are included in season detection so the app defaults to the right season on load.
- **Collection entry for pulled taps** -- You can now log sap collections for dates between a tap's install and pull date, even after the tap has been pulled. This allows entering historical or backdated collection data.
- **Historical weather for past seasons** -- Switching to a past season with tap dates now fetches historical weather data, even if some weather entries already exist for that season.
- **Weather source accuracy** -- Saving a collection no longer silently overwrites forecast or historical weather as a manual entry. Only weather values you actually change are saved as manual.
- **Tap pull date validation** -- The app now prevents setting a tap pull date before the tap install date.

---

## v1.5.0

### New Features

- **Celsius support** -- Temperature unit setting (Fahrenheit/Celsius) with auto-detection from location.
- **Canadian location support** -- Postal codes and city names with multi-tier geocoding fallback.
- **Boil batch tracking** -- Mark collections as boiled or discarded with automatic FIFO deduction.
- **Boil tab summary widgets** -- Available Sap, Estimated Output, Gallons Boiled, and Syrup Produced.
- **Syrup conversion modals** -- Tap any syrup amount for a volume breakdown.
- **Tap date correction prompt** -- Prompts to update tap or season dates when logging backdated collections.

### Bug Fixes

- Edge-to-edge display updated to current Android APIs.
- Tablet and foldable support added.
- Deprecated SplashActivity API replaced.

### Improvements

- Three-tier geocode fallback chain for better international coverage.
- Boiled/discarded status included in CSV exports.

---

## v1.4.0

### New Features

- **Per-season start and end dates** -- Each season has its own start and end date, editable per-year in Settings.
- **Default to Open-Meteo weather** -- New installs default to Open-Meteo instead of manual.
- **Default to calendar view** -- New installs open to calendar view instead of timeline.
- **Zip code fallback for location** -- Zip code / city name entry offered if GPS is skipped or denied.
- **Auto-fetch weather** -- Automatic weather fetch on source/location configuration and season switch.
- **Season average brix setting** -- Use weighted average of measured season brix as fallback instead of species defaults.
- **Projected syrup on boil modal** -- Live-updating projection using Rule of 86.
- **Species brix on dropdowns** -- Default brix percentage shown next to each species name.
- **Season average brix on tree cards** -- Weighted average measured brix per tree per season.

### Bug Fixes

- Boil brix estimate fixed with FIFO deduction.
- Manual flow overrides preserved during weather fetch.
- Version number in Settings now shows actual native app version.
- Boil volume not converted on unit change.
- iOS JS dialogs and date picker fixes.
- Scroll position preserved across tab switches.

### Improvements

- Compact dashboard controls.
- iOS parity with all Android features.
- iOS cache clearing on launch.

---

## v1.3.0

### New Features

- **Boil modal overhaul** -- Inline unit pickers with auto-calculated sap brix.
- **Tree and tap separation** -- Trees as permanent entities with taps installed per-season.
- **Missed flow indicator** -- Calendar and timeline show "MISSED" on sap flow days before tap install.
- **Scrollable calendar with week start setting.**
- **First-run setup wizard.**
- **Historical weather backfill** -- Auto-fetch weather for dates with collections but no weather.
- **Backdate historical data** -- Enter collections and weather for past dates.

### Improvements

- Dashboard shows actual syrup output instead of estimates when all sap is boiled.
- CSV export includes per-boil unit columns.
- Full season dashboard totals.
- Collections can be moved to a different date.
- Reorganized Settings screen.

---

## v1.2.0

### New Features

- **Tap pull date tracking** -- Optional "Date Pulled" field that deactivates the tap.
- **Per-table CSV export** -- Choose which tables to export (Collections, Weather, Taps, Boils, Fees).
- **Custom export filenames** -- Optional custom filename for JSON and CSV exports.
- **Version display** -- Version number on splash screen and in Settings.

---

## v1.1.0

### Bug Fixes

- Brix preserved on edit.
- Weather not forced on backdate.
- Brix mode detection on existing data.

### New Features

- **Manual sap flow override** -- Mark any day as flow/no-flow regardless of temperature.

### Improvements

- Backup resilience with direct file access fallback.
- Android Auto Backup rules for cloud and device-to-device transfer.

---

## v1.0.0

First public release. Dashboard, tap management, sap collection, boil tracking, weather integration, data export. All data stored locally with no account required.
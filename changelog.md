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
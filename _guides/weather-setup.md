---
title: Weather Setup
description: Configuring weather data in Backyard Sap Tracker.
order: 4
---

# Weather Setup

## Choosing a weather provider

The app supports two weather data sources:

- **Open-Meteo** -- Global coverage, no API key required.
- **National Weather Service** -- US-only, official NOAA data.

Select your provider in the settings screen. Both provide daily high and low temperatures used for sap flow prediction.

## Setting your location

Enter your location in any of these formats:

- GPS coordinates (auto-detected from your device)
- US zip code
- Canadian postal code
- City name

The app uses this location solely to fetch local weather forecasts. GPS coordinates are not stored or shared beyond this purpose.

## Temperature units

The app supports Fahrenheit and Celsius. It auto-detects the appropriate unit from your location but you can override this in settings.

## Auto-fetch

When enabled, the app automatically fetches weather data when you open it. This requires an internet connection. Without auto-fetch, you can manually trigger a weather update from the dashboard.

## Sap flow prediction

Sap flow days are determined by temperature patterns: a freeze overnight (below 32F / 0C) followed by a thaw during the day. The app uses historical 5-year temperature averages to extend predictions out to 45 days beyond the current forecast.

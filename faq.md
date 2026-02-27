---
layout: default
title: FAQ
description: Frequently asked questions about Backyard Sap Tracker.
---

# Frequently Asked Questions

## General

<details>
<summary>What is Backyard Sap Tracker?</summary>

A mobile app for hobby maple syrup makers to track sap collection, weather conditions, boiling sessions, and syrup production. It runs entirely on your phone with no account or internet connection required (except for weather data).

</details>

<details>
<summary>How much does it cost?</summary>

$1.99, one-time purchase. No subscriptions, no ads, no in-app purchases.

</details>

<details>
<summary>What platforms does it run on?</summary>

Android and iOS. Available on [Google Play](https://play.google.com/store/apps/details?id=com.saptracker.app) and the [App Store](https://apps.apple.com/us/app/backyard-sap-maple-syrup/id6759408463).

</details>

## Privacy and Data

<details>
<summary>Where is my data stored?</summary>

All data is stored locally on your device. Nothing is sent to a server, cloud, or third party. The app does not have accounts or logins.

</details>

<details>
<summary>Does the app track me?</summary>

No. There is no analytics, no telemetry, and no advertising SDKs. GPS coordinates are used solely to fetch local weather forecasts and are not stored or transmitted beyond that purpose.

</details>

<details>
<summary>What happens if I uninstall the app?</summary>

If auto-backup is enabled, your data is preserved on device storage and will be restored on reinstall. Without auto-backup, uninstalling deletes all app data. You can also export your data as JSON or CSV at any time from the settings screen.

</details>

## Features

<details>
<summary>How does sap flow prediction work?</summary>

The app calculates sap flow conditions from daily high and low temperatures. A freeze overnight (below 32F / 0C) followed by a thaw during the day signals a sap flow day. Historical 5-year temperature averages extend predictions out to 45 days.

</details>

<details>
<summary>What is the Rule of 86?</summary>

A formula used to estimate syrup yield from sap. Divide 86 by the Brix (sugar content) of the sap to get the number of gallons of sap needed to produce one gallon of syrup. The app uses this automatically when you log collections with Brix readings.

</details>

<details>
<summary>Can I track multiple trees and taps?</summary>

Yes. Trees and taps are managed separately. You can add any number of trees by species and location, then install one or more taps per tree each season.

</details>

<details>
<summary>Can I log multiple collections per day?</summary>

Yes. You can log multiple sap collections per tap per day. Each collection can have its own Brix reading.

</details>

<details>
<summary>What weather services does the app use?</summary>

Open-Meteo and the National Weather Service. Weather data is fetched automatically when configured and supports both Fahrenheit and Celsius with auto-detection from your location.

</details>

<details>
<summary>Can I export my data?</summary>

Yes. Export as JSON (full backup) or CSV (individual tables: Collections, Weather, Taps, Boils, or Fees). Both options are in the settings screen.

</details>

## Troubleshooting

<details>
<summary>Weather data is not loading</summary>

Check that you have an internet connection and that a valid location is set in the app. The app accepts GPS coordinates, US zip codes, Canadian postal codes, and city names. If the problem persists, try switching between Open-Meteo and National Weather Service in settings.

</details>

<details>
<summary>I lost my data after reinstalling</summary>

If auto-backup was not enabled before uninstalling, the data is not recoverable. Enable auto-backup in settings to prevent this in the future. You can also periodically export your data as JSON from the settings screen.

</details>

<details>
<summary>My question is not listed here</summary>

Check the [guides]({{ '/guides/' | relative_url }}) for step-by-step walkthroughs, or [submit a question](https://github.com/NotMilk/BackyardSapTracker-support/issues/new?template=feedback.yml) on GitHub.

</details>

# Fire TV app for a BoxCast OTT channel

An Amazon Fire TV app that mirrors an existing BoxCast-powered OTT channel, so the organization's TV presence on Roku, Apple TV, and Fire TV shows the same content with the same look.

**Status:** built in Android Studio, tested on a Fire TV over `adb`, and submitted to the Amazon Appstore on October 25, 2026 as an update to the organization's existing Fire TV listing. Awaiting review.

## Why

The organization's Roku and Apple TV apps and its web OTT player run on BoxCast. Fire TV needed to match them and stay in sync without separate curation.

## What it does

- Same content rows as the existing OTT app (live show, highlights, sponsors, segments, on-demand episodes).
- Live playback with quality selection; captions off by default.
- Matches the existing OTT app's look, including its font, so viewers see one product across devices.
- Content comes from the same source as the other apps: live, schedule, and episodes stay in sync with no extra work.

## Approach

- Fire TV app built as a wrapper around the existing OTT web app, so content and design stay identical.
- Shipped as an update to the existing Appstore listing rather than a new app, so current viewers get it automatically.
- Longer term, the plan is to put all TV platforms on one custom design system.

## What's in this repo

This README. Source is not public at this time.

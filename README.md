# Pilot Path — Complete 17-Chapter Website

## Open on Windows
Extract this ZIP. Double-click `index.html` in Chrome or Edge. No local server is required for the included lesson content.

## Publish on GitHub Pages
Upload all files and folders, preserving `index.html`, `assets/` and `chapters/` at the repository root. Enable Pages from your repository branch root. On iPhone, open the HTTPS site and use Safari → Share → Add to Home Screen.

## Navigation
Select a chapter from the home screen. Every chapter includes a `‹ All Chapters` link at the top. The original Chapter 1–17 lessons and practice/exam features are preserved. Chapter progress is stored locally per browser and origin. Existing results from the exact same browser origin and matching progress key may remain accessible; changing from file:// to a hosted domain usually creates a separate storage location.

## App icon
Your approved realistic front-facing airplane with compass/globe artwork (no wording), used across the site and PWA icon assets.

## Scope
A study companion based on FAA-H-8083-25C. Flight rules, safety requirements and weather information should be verified against current official FAA sources.

## Central Learning Dashboard

The opening screen now includes **Learning dashboard** and **All 17 chapters** tabs. The dashboard computes lesson completion, completed chapter count, total recorded exam attempts, average **latest** exam results for chapters actually attempted, and chapter-level latest/best exam percentages. It reads existing chapter progress from the same browser's localStorage; no migration/reset is required. It refreshes when you return to the homepage.

**Local opening caveat:** Browsers may isolate storage between individual `file://` HTML files. For dependable cross-chapter aggregation, serve the site through GitHub Pages or a local HTTP server. This limitation does not affect the offline availability of content.

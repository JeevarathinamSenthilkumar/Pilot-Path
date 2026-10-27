# Pilot Path · iPhone & Quality Review

## Changes
- Improved responsive sizing and tap targets for narrower iPhone screens across the home screen and all 17 chapter apps.
- Made the All Chapters link sticky and visible in all chapter views.
- Improved long-text wrapping, image containment, and accessibility focus states.
- Added root service worker for hosted installation and offline caching of site HTML, data, styles, scripts, figures and icon files.
- Preserved all existing localStorage progress and examination keys.
- Preserved examination content and curriculum.

## Important limitations
- Offline caching is available after the site is hosted via HTTPS, first opened online, and the service worker completes precaching. Local file:// mode works for reading but does not support a service worker.
- Progress does not synchronize automatically across different devices/browsers.
- Automated technical QA is not an expert FAA content validation. Aircraft limitations, FAA regulations and weather products must be checked against authoritative current sources before flight.
- Full physical-device iPhone testing must still be done by opening the hosted site in Safari.

## Verification results
- 17 of 17 chapter entry pages found.
- 52 JavaScript files passed `node --check`.
- Referenced chapter illustrations were checked against package paths; no missing paths found.
- ZIP integrity passed.
- Automated Chromium navigation was attempted but blocked by environment restrictions (`ERR_BLOCKED_BY_ADMINISTRATOR`) for both file URLs and localhost. Live browser and physical iPhone Safari behavior remain unverified.


## v6 bottom-navigation adjustment
- Removed floating Pilot Path · Knowledge Academy from home screen.
- Chapter tab navigation is edge-attached on iPhone (Home, Learn, Exams, Progress).
- Safe area padding added for iPhone Home indicator and status area.
- Updated CSS references and service-worker cache version.
- No chapter lesson or exam data modified.

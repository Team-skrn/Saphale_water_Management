# Saphale Water Management System

## Overview
Saphale Water Management System is a Progressive Web App (PWA) that allows users to monitor water levels and control valves across multiple locations. The system works both online and offline, providing a seamless user experience regardless of network connectivity.

## Features
- Water level monitoring in real-time
- Remote valve control (open/close)
- PWA functionality for offline access
- Network status indicator
- Installable on desktop and mobile devices

## Implementation Details
1. PWA components:
   - manifest.json: Defines app properties, icons, and installation behavior
   - service-worker.js: Handles offline caching and resource management
   - app.js: Controls service worker registration and PWA installation
   - offline.html: Displayed when a user tries to access an uncached page while offline

2. Installation:
   - The app can be installed on compatible devices by clicking the "Install App for Offline Use" button
   - Once installed, the app will function like a native application

3. Offline Functionality:
   - The app caches all essential resources for offline use
   - When offline, previously loaded data can still be viewed
   - New data fetching and actuator control requires internet connectivity

## Location Pages
- MBR: 2 sensors and 4 actuators
- Kurlai Mandir: 1 sensor and 1 actuator
- Makne: 1 actuator only
- Mande: 1 sensor and 1 actuator
- Vittalwadi: 1 sensor and 1 actuator
- Viradhan: 1 sensor and 1 actuator
- Jalsar: 1 sensor and 1 actuator
- Tembhikodave: 1 sensor and 1 actuator
- Umberpada: 1 sensor and 1 actuator
- Kardal: 1 sensor and 1 actuator
- ICSR: Based on the ICSR_eng.html template

## Future Improvements
- Add push notifications for critical water level alerts
- Implement background sync for offline data submission
- Add periodic sync for background data updates
- Enhance offline capabilities with IndexedDB for data storage

Last Updated: June 1, 2025
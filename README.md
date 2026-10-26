# Smart India Hackathon Workshop

**Date:** 26/10/2026  
**Register Number:** 212223040057  
**Name:** Harini N

## Problem Title
**SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations**

## Problem Creator's Organization
Ministry of Railways, Government of India

## Idea
**SmartRail AI – Railway Station Navigation System**

A smart navigation system that helps passengers locate platforms, ticket counters, restrooms, food courts, and exits using interactive maps, indoor positioning, and voice guidance.

## Proposed Solution / Architecture Diagram
Mobile App / Web App / Digital Kiosk → Backend Services → Navigation Engine → Station Database → Real-Time Directions.

The system uses QR codes or BLE beacons for indoor positioning and Dijkstra's or A* algorithms for route planning.
## Proposed Solution / Architecture Diagram
<img width="1536" height="1024" alt="VisionBridge AI Architecture Diagram" src="https://github.com/user-attachments/assets/78ae4ccf-728d-4852-b46c-635b77663637" />



## Use Cases
- Locate platforms and station facilities.
- Provide voice-guided navigation.
- Find wheelchair-accessible routes.
- Display real-time platform and facility updates.
- Support emergency exit navigation.
- Help administrators update station information.

## Technology Stack
- **Frontend:** Flutter, React.js
- **Backend:** Python, Django REST Framework
- **Database:** PostgreSQL, Firebase
- **Mapping:** OpenStreetMap, Mapbox
- **Algorithms:** Dijkstra's, A*
- **Accessibility:** Speech-to-text, text-to-speech
- **Infrastructure:** Docker, AWS/Azure

## Dependencies
**Frontend:** `flutter`, `provider`, `http`, `flutter_tts`, `speech_to_text`

**Backend:** `django`, `djangorestframework`, `psycopg2-binary`, `numpy`, `networkx`

**Mapping:** OpenStreetMap, Mapbox SDK, QR code libraries, BLE beacon SDK

**Database:** PostgreSQL, Firebase (optional)

**Hardware:** Smartphone, digital kiosk, QR markers or BLE beacons, and server infrastructure.

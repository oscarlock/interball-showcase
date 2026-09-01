# InterBall

InterBall is a mobile interval-training and workout-documentation application built with Flutter. The project explores a lap-centered training workflow in which each timed segment can carry its own exercise name, notes, photos, and videos.

> **Status:** Active prototype. Core stopwatch, lap, persistence, and media workflows are implemented. Navigation, automated testing, architecture refinement, product polish, and release preparation remain in progress.

## Product concept

Training sessions often produce more context than a conventional timer records. InterBall is designed to keep time, exercise context, notes, and visual media connected at the lap level so that a session can be reviewed as a chronological training record.

The current interaction model is:

1. Start or pause the session stopwatch.
2. Add laps as the workout progresses.
3. Name the exercise associated with a lap.
4. Record notes for that segment.
5. Capture photos or videos and attach them to the lap.
6. Review, reorder, annotate, play, or remove saved media.
7. Restore locally persisted session information when returning to the app.

## Implemented capabilities

- Start, pause, reset, and lap controls
- Continuously updated lap timing
- Exercise names and notes stored per lap
- Local persistence for timer and lap-session data
- Device-camera photo and video capture
- App-local storage for captured media
- Video-thumbnail generation and caching
- Reorderable per-lap media collections
- Full-screen swipeable media review
- Image text annotation
- Inline video playback, seeking, mute control, and filmstrip-style scrubbing
- Material 3 interface with custom SF Mono typography

## Technology

- **Framework:** Flutter
- **Language:** Dart
- **UI:** Flutter Material 3
- **Local state:** SharedPreferences
- **Device media:** Image Picker
- **Media storage:** Path Provider and application documents storage
- **Playback:** Video Player
- **Preview generation:** Video Thumbnail
- **Primary release focus:** iOS

## Current development priorities

- Replace the temporary routing-check entry screen with the intended product navigation
- Separate the primary stopwatch screen into smaller maintainable components
- Expand widget, routing, persistence, and media-flow tests
- Validate behavior on physical iOS devices
- Improve empty, error, permission, and recovery states
- Capture representative screenshots and a short product demonstration
- Complete release-readiness and App Store preparation

## Documentation

- [Product overview](docs/product-overview.md)
- [Technical overview](docs/technical-overview.md)

## Screenshots and demonstration

Representative screenshots and a short workflow demonstration will be added after the current navigation and presentation pass is complete.

## Source availability

InterBall is independently developed by Oscar Lock. The application source code and private development history are intentionally maintained in a separate private repository.

This public repository contains product documentation and, when available, demonstration media only. It does not contain the application source code.

## Contact

- [GitHub profile](https://github.com/oscarlock)
- [LinkedIn](https://www.linkedin.com/in/oscarlock/)

Copyright (c) 2024-2026 Oscar Lock. All rights reserved.

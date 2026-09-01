# Product Overview

## Purpose

InterBall is being developed to connect interval timing with the information produced during a training session. Instead of treating a lap as only a timestamp, the application treats it as a record that can include an exercise name, written notes, photos, and videos.

The goal is to make a workout easier to document while it is happening and easier to review afterward.

## Current user flow

1. The user opens the active stopwatch experience.
2. The stopwatch can be started, paused, reset, or divided into laps.
3. Each lap receives its own elapsed time.
4. A lap can be assigned an exercise name and notes.
5. Photos or videos can be captured and attached to that lap.
6. Attached media can be reviewed in a swipeable gallery.
7. Media can be reordered or removed, and images can receive text annotations.
8. Session state is saved locally for later restoration.

## Product principles

### Context belongs with time

Timing information becomes more useful when it remains connected to the exercise, observation, or media that produced it.

### Capture should remain inside the session

The media workflow is designed to reduce the need to leave the training context, use a separate camera workflow, and manually reconstruct which media belongs to which interval.

### Review should preserve chronology

Lap records provide a chronological structure for reviewing a session rather than presenting media as an unrelated collection.

### Development claims should remain verifiable

This showcase distinguishes between implemented prototype behavior and work that remains in progress. It does not represent InterBall as an App Store release or finished commercial product.

## Current scope

The active prototype includes the core stopwatch and lap model, locally persisted lap metadata, camera-based media capture, local media storage, thumbnail generation, media ordering, image annotation, gallery review, and video playback controls.

## Work remaining

- Complete the intended navigation and primary application entry flow
- Refine the product hierarchy and visual presentation
- Decompose large interface components into smaller units
- Expand automated testing and physical-device validation
- Improve permission, empty, failure, and state-recovery behavior
- Prepare screenshots, demonstration media, privacy information, and release materials
- Complete App Store release preparation

## Availability

InterBall is currently an independently developed active prototype. Its source code is private. This repository is limited to public product and engineering documentation.

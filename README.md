# 🏀 Task 6 — OpenCV (Basketball & Player Tracking)

A concise OpenCV project: build a complete computer-vision pipeline to detect, track, and visualize the basketball and all players visible in the provided video.

---

## 🎯 Objectives

- Detect and reliably track the basketball across all frames.
- Detect and track all players from both teams who appear on screen.
- Maintain live counts of players per team and update them as players enter/exit the frame.
- Distinguish players by team (e.g., using jersey color or clustering).

---

## Features to implement

- 🟠 Basketball Tracking
  - Draw a bounding box or clear visual marker around the ball in every frame.
  - Ensure robust tracking through fast motion, partial occlusions, and lighting changes.

- 👥 Player Detection & Tracking
  - Detect and draw bounding boxes (or markers) around each player.
  - Track players persistently across frames (assign unique IDs).
  - Maintain dynamic counts for each team (separate counts).
  - Attempt to distinguish teams (jersey color, clustering, or other features).

---

## ⚙️ Implementation Requirements

- Implement tracking logic yourself; use OpenCV primitives as building blocks.
- Allowed libraries:
  - cv2 (OpenCV)
  - numpy
- Do not use end-to-end black-box trackers / pre-made commercial tracking pipelines (implement the core logic).

---

## 📝 Deliverables

- A working script or notebook that:
  - Reads the provided video.
  - Outputs a processed video (or displays frames) with:
    - Ball bounding box/marker.
    - Player bounding boxes with unique IDs.
    - Team counts shown on-screen (e.g., overlay UI).
- Short README (this file) describing how to run the code and any assumptions.

---

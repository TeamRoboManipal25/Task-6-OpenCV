# Task-6-OpenCV

OpenCV Project Task Description

Using OpenCV, your objective is to build a complete computer-vision pipeline for tracking the basketball and all players visible in the given video. The system should perform the following tasks:

Basketball Tracking

Detect and track the basketball throughout the video.

Draw a bounding box (or any clear visual marker) around the ball in each frame.

Ensure that the tracking is stable and able to follow the ball even during fast motion, partial occlusions, or lighting changes.

Player Tracking and Counting

Detect and track all players from both teams who appear on the screen at any moment.

Maintain separate counts for each team, updating the numbers dynamically as players enter or exit the frame.

Use bounding boxes or visual markers to indicate each tracked player.

Your solution should attempt to distinguish the two teams based on features such as jersey color or clustering.

Algorithm Implementation Requirements

Implement the tracking logic from scratch, using OpenCV functions as building blocks.

You are allowed to use cv2 and numpy libraries.

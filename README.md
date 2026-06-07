# Volleymetrics
A computer vision tool for volleyball tracking using YOLOv5 and YOLOv8, designed for practice analysis of setters and hitters.
**What it does**
Volleymetrics detects a volleyball during practice footage and plots its trajectory frame-by-frame, enabling analysis of setting and hitting patterns for player development.
**Why I built it**
As a volleyball player, I wanted a way to give setters and hitters objective feedback during practice — tracking ball trajectory and movement in ways that aren't easily visible in real time.
**How it works**
Runs YOLOv5 or YOLOv8 depending on use case
YOLOv5 performs better on footage where the ball is clearly visible — higher accuracy and faster inference than v8 in those conditions
YOLOv8 handles more complex or lower-quality footage
Detects ball position per frame and plots trajectory over time
Currently supports video file input
**Performance**
~85% frame-level detection accuracy on standard practice footage
Known limitation: detection degrades after hard hits and sets, where the ball moves rapidly or becomes motion-blurred — an area for future improvement

**Planned improvements**
Live webcam/camera support
Improved detection on fast-motion frames (post-hit, post-set)

***Setup**
(coming soon)

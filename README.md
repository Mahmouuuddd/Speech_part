# Speech_part

massager_node.py
Purpose: Simple motion detection and alert system.
Key Features:
- Detects motion using OpenCV by comparing consecutive frames.
- Sends email alerts (via Gmail) and plays a beep sound when motion is detected.
- Displays live feed with bounding boxes around motion areas.
Components:
mail_alert(): Sends emails via SMTP.
Main loop: Captures frames, detects motion contours, and triggers alerts.


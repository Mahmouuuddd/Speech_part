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

speech.py
Purpose: Voice assistant (Sarah) with basic Q&A and web search capabilities.
Key Features:
- Answers questions about a faculty (e.g., departments, projects) using a predefined knowledge base.
- Tells jokes, provides the time, and plays YouTube videos.
- Uses Selenium to scrape Wikipedia for additional information.
Functions:
- take_command(): Listens for voice input.
- run_sarah(): Handles predefined questions.
- run_sara(): Searches Wikipedia for user queries.

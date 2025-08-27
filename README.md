#Smart Queue Manager

An AI-powered computer vision system designed to automate retail checkout queue monitoring. This solution uses real-time analysis of CCTV footage to dynamically count people in queues, identify congestion, and generate intelligent alerts for staff to open new counters—effectively reducing customer wait times and optimizing workforce allocation.

Key Features
Real-time People Counting: Leverages YOLOv8 object detection to accurately count individuals in predefined queue zones from live video feeds.
Automated Staff Alerts: Sends instant browser notifications when queue lengths exceed configurable thresholds, prompting timely intervention.
Dynamic Zone Management: Allows administrators to define and visualize custom monitoring zones directly through the web interface for precise analytics.
Dashboard Visualization: Provides a clean, web-based dashboard to view live queue status across all store counters.
Easy Integration: Works with standard IP CCTV cameras, requiring no specialized hardware.

Tech Stack
Backend: Python, Flask
AI Model: YOLOv8 (Ultralytics) for person detection
Computer Vision: OpenCV
Frontend: HTML, CSS, JavaScript, Jinja2 Templating

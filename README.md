# Safe-Path-App
Mobile safety system for teenagers built on Glide
Safe Path — Mobile Safety Ecosystem
Project Overview
Safe Path is a high-reliability mobile application designed to bridge the critical communication gap between teenagers in potential danger and their "Circle of Trust." The project addresses the lack of real-time safety infrastructure in urban environments by integrating digital SOS signals with a physical network of verified "Safe Points." Developed on the Glide No-code platform, it utilizes a serverless architecture to ensure rapid deployment and data integrity.

The Problem
Teenagers frequently face situations where they cannot quickly alert parents or identify safe havens (such as shops, pharmacies, or schools) during an emergency. Traditional emergency services may be too slow to reach, and parents often lack real-time visibility of their child's safety status.
Core Technical Features

Trust-Based Mapping: A dynamic geolocation interface powered by Google Maps API. It displays a curated network of "Verified Safe Points." Each location is an active partner (shops, pharmacies) where staff are trained to provide immediate refuge.

Smart SOS Trigger: A high-contrast, dominant action button designed for high-stress usability. Activating the SOS instantly updates the user’s database status to "DANGER," records precise GPS coordinates, and generates a time-stamped alert.

Guardian Safety Dashboard: A specialized administrative view for parents. This dashboard provides live location tracking, breadcrumb history of the child's path, and instant priority notifications when an alert is triggered.

Live Path Sharing: A "Companion Mode" allowing teenagers to share their active route in real-time, creating a continuous safety stream for the guardian.

Technical Implementation (Architecture)

Platform: Glide Apps (Progressive Web App).

Data Engine: Cloud-based Glide Tables with relational mapping between Users, Guardians, and Safe Points.

Security: Row-level privacy rules ensuring location data is accessible only to authorized "Circles of Protection."

Logic: Automated Workflows (Actions) for instant data synchronization and emergency alert dispatch.

Future Roadmap
The next phase includes "Evidence Collection" (automated background audio/video recording) and integration with municipal "Smart City" security systems to provide a 360-degree safety net for the youth.

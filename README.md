# ASL-to-Text Chrome Extension
A browser extension that translates American Sign Language (ASL) fingerspelling into text input in real-time, enabling deaf and hard-of-hearing users to interact with web forms and applications using sign language.
*Project Status:* Active Development
*Timeline:*

August 2024: Initial concept and research phase - explored OpenCV and TensorFlow approaches for gesture recognition.

October 2024: Paused due to academic commitments.

January 2025: Resumed development with refined technical approach using MediaPipe Hands for browser-based implementation.

# Motivation
Web accessibility for the deaf and hard-of-hearing community remains limited. While screen readers help blind users, there are few tools that allow ASL users to interact with web interfaces using their primary language. This extension aims to bridge that gap by enabling direct ASL input into any text field on the web.
Technical Approach

# Initial Exploration (August 2024)

Experimented with OpenCV for hand detection and tracking
Explored TensorFlow models for gesture classification
Prototyped Python-based recognition system

# Current Implementation (January 2025)
After research and experimentation, pivoted to a browser-native approach:

MediaPipe Hands: Real-time hand landmark detection
Client-side processing: All recognition happens in-browser for privacy and speed
Chrome Extension APIs: Seamless integration with web pages
Rule-based classification: Geometric analysis of hand landmarks for fingerspelling recognition


# Tech Stack
JavaScript/HTML/CSS
MediaPipe Hands API
Chrome Extension Manifest V3
TensorFlow.js (planned for advanced features)

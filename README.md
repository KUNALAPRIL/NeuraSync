cat > README.md <<'EOF'
# ZenPulse / NeuraSync

Interactive wearable-wellness prototype focused on emotion, stress, vitals, sleep, and calming experiences.

## Overview

ZenPulse is a front-end prototype for a conceptual smart wearable called **NeuraSync**. It presents an interactive smartwatch interface with simulated physiological sensor data, emotion states, stress alerts, sleep summaries, history, and guided breathing.

> **Prototype note:** sensor readings and emotion states in the current demo are simulated/mock data. They are not collected from physical ESP32 sensors yet.

## Features

- Interactive smartwatch interface
- Live analog clock
- Simulated emotion states
- Simulated heart rate, HRV, GSR, skin temperature, EMG, pulse oximeter, breathing, and stress score
- High-stress notification with vibration support where available
- Guided breathing / calming protocol
- Sleep summary UI
- Seven-day stress history visualization
- Responsive landing, dashboard, and technology pages
- Hardware/component concept presentation

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- SVG
- Chart.js
- Google Fonts

## Project Structure

- `home.html` — product landing page
- `index.html` — interactive dashboard
- `tech.html` — smartwatch technology/demo interface
- `home1.css` — landing page styles
- `home1.js` — reserved JavaScript file
- `*.png` — product, hardware, emotion, and UI assets

## How to Run

No build process is required.

Open `home.html` in a browser and navigate through the dashboard and technology demo.

## Project Status

**Interactive front-end prototype**

The current version uses simulated sensor data for demonstration.

## Future Scope

- ESP32 sensor integration
- Real sensor data collection
- Backend/API
- Persistent data storage
- Authentication
- Real emotion/stress inference

## Disclaimer

This is a conceptual software/hardware prototype for demonstration and educational purposes. It is not a medical device and should not be used for medical diagnosis or treatment.
EOF
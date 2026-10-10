🛡️ KAVACH — Vehicle-to-Pedestrian Safety System Simulation

A real-time visual simulation exploring low-latency Vehicle-to-Pedestrian (V2P) communication using edge computing concepts.

KAVACH demonstrates how a vehicle could detect a pedestrian, assess collision risk and deliver a safety alert through a simulated pipeline involving an on-vehicle controller, Multi-access Edge Computing (MEC) and 5G communication concepts.

The project focuses on the importance of low-latency processing in road safety scenarios.

🚦 Overview

At high vehicle speeds, even small delays can affect the time available to respond to a potential collision. KAVACH visualises a proposed safety architecture that combines local risk assessment with edge-assisted communication.

The simulation illustrates the following workflow:

Detect → Decide → Process → Alert

1. Radar detection: Represents a 77 GHz millimetre-wave radar detecting a pedestrian.
2. On-vehicle processing: Illustrates collision-risk assessment using Time-to-Collision (TTC).
3. Edge processing: Demonstrates a conceptual MEC stage with priority safety messaging, geographic filtering and message time-to-live (TTL) enforcement.
4. Pedestrian alert: Visualises the delivery of a warning to a pedestrian.

✨ Features

- 🎬 Animated, time-sequenced safety simulation.
- 🚗 Vehicle movement and pedestrian detection visualisation.
- 📡 Conceptual millimetre-wave radar detection.
- ⏱️ TTC and end-to-end latency displays.
- ⚡ Visualisation of on-vehicle processing and edge computing.
- 📱 Simulated pedestrian warning interface.
- 📊 Animated system pipeline with processing stages.
- 🔄 Replay functionality for repeated demonstrations.
- 🌌 Dark, futuristic dashboard with animated indicators.
- 📱 Responsive adjustments for different screen sizes.

🏗️ System Architecture

Vehicle Radar
     |
     v
On-Vehicle MCU
(TTC / Risk Assessment)
     |
     v
MEC / Edge Processing
(Priority / Geo-Filtering / TTL)
     |
     v
Pedestrian Alert
(Conceptual 5G Communication)

The simulation separates local risk assessment from the conceptual network communication stage to demonstrate the role edge computing could play in safety-critical applications.

🧰 Technologies Used

- HTML5 — Page structure and simulation components.
- CSS3 — Layout, animations, visual effects and responsive styling.
- JavaScript — Simulation timeline, UI state changes, latency animation and replay logic.
- Google Fonts (Inter) — Typography.

The current implementation runs in a web browser and does not require a backend server or JavaScript framework.

▶️ How to Run

Option 1: Open directly

1. Download or clone this repository.
2. Open "index.html" in a modern web browser.
3. Click BEGIN SIMULATION.
4. Observe the detection, processing and alert stages.
5. Click REPLAY after the summary screen to run the demonstration again.

Option 2: Run using a local server

If Python is installed, open a terminal in the project directory:

python -m http.server 8000

Open the following address in your browser:

http://localhost:8000

📁 Project Structure

KAVACH/
├── index.html
└── README.md

The HTML file contains the page structure, CSS styling and JavaScript simulation logic.

🎯 Applications and Motivation

KAVACH explores concepts relevant to:

- Vehicle-to-Pedestrian (V2P) safety.
- Intelligent Transportation Systems (ITS).
- Edge computing and low-latency communication.
- Collision-risk assessment.
- Human-centred road safety technologies.

The project is intended as an educational demonstration of how these concepts could fit together in a road-safety architecture.

⚠️ Limitations

KAVACH is a simulation and not a deployed road-safety system.

- Radar measurements and pedestrian detection are visually simulated.
- TTC and risk levels are illustrative rather than derived from live sensor measurements.
- MEC processing and 5G communication are represented through animations, not actual network infrastructure.
- The displayed 28 ms end-to-end latency is a configured demonstration value, not a measured benchmark.
- No real pedestrian smartphone notifications or vehicle-control operations are performed.

Real-world deployment would require hardware integration, validated collision-prediction algorithms, reliable communications, security safeguards and extensive safety testing.

🔮 Future Improvements

- Integrate a real-time pedestrian detection model using computer vision.
- Add a mathematical TTC calculation based on relative distance and velocity.
- Build a backend for exchanging vehicle and pedestrian messages.
- Simulate network latency, packet loss and message prioritisation.
- Add a configurable speed, distance and latency interface.
- Explore V2X communication protocols and edge-computing integration.

👨‍💻 Author

Aditya Raj
B.Tech — Artificial Intelligence and Data Science, IIIT Manipur

- GitHub: "aditya-raj149" (https://github.com/aditya-raj149)

📄 License

Choose an appropriate open-source license before distributing or reusing the project. For example, the MIT License may be suitable if you want to allow reuse with attribution.

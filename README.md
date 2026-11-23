# IoT Control Center - Frontend MVP 🚀

A responsive, professional, dark-themed IoT (Internet of Things) Control Center web dashboard MVP. This project is a high-fidelity **frontend simulation** designed to showcase how a modern IoT monitoring platform looks and feels before integrating real hardware, backend services, and databases.

![Dashboard Preview](https://via.placeholder.com/1200x600/0f172a/22d3ee?text=IoT+Control+Center+MVP+Preview) *(Replace with a real screenshot of your dashboard)*

## ⚠️ Important Disclaimer
**This is a 100% DEMO/SIMULATED environment.** 
All devices, sensor readings, network metrics, security scans, and database statistics are entirely simulated directly in your browser. This application does **not** connect to real hardware, MQTT brokers, cloud services, or databases. No secrets or API keys are required or exposed.

## ✨ Features
The MVP includes the following fully responsive pages and components:
*   **Overview Dashboard:** KPI cards for Total/Online/Offline devices, Active Alerts, Messages, and Network Uptime.
*   **Device Monitoring:** Searchable and filterable device table with registration form (simulates adding new devices).
*   **Live Sensor Readings:** Interactive charts (Chart.js) simulating real-time data for Temperature, Humidity, Motion, Air Quality, and Energy.
*   **Network Connectivity:** Visual representation of the Gateway, MQTT Broker, and Backend status.
*   **Cloud Status & Database Stats:** Simulated health metrics for PostgreSQL and TimescaleDB.
*   **Cybersecurity Control Center:** Mock audit logs, failed login attempts, MFA/TLS indicators, and remediation advice.
*   **Alerts Management:** Acknowledgeable and resolvable simulated critical/warning alerts.
*   **Command Panel:** A safe, simulated device-command execution panel with confirmation modals and activity logs.

## 🛠️ Tech Stack (Zero Build Step)
This project was intentionally built to be lightweight and run immediately without any complex build tools (like Webpack or Vite).
*   **HTML5** (Semantic structure)
*   **Tailwind CSS** (via CDN - for rapid, responsive styling)
*   **Vanilla JavaScript** (State management, interactivity, DOM manipulation)
*   **Chart.js** (via CDN - for dynamic, simulated data visualization)
*   **FontAwesome** (via CDN - for iconography)

## 🚀 Getting Started
Since this is a single-file application, getting it running is incredibly easy.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/iot-control-center-mvp.git

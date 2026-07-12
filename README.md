# SENEXA · Industrial Performance Intelligence

> **Treat your machines like elite athletes.**
> An AI-driven predictive maintenance platform designed for Indian MSMEs, preventing machine breakdowns before they happen by monitoring real-time IoT sensor data and ML anomaly detection.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)

## 📖 Overview

Many Indian MSMEs face significant productivity bottlenecks due to unexpected machine breakdowns. Traditional small factories rely on static maintenance schedules or manual inspections, leading to costly downtime. 

**Senexa** democratizes "smart maintenance" with a plug-and-play, budget-conscious alternative. It uses an IoT-cloud-AI pipeline to monitor machine vitals (vibration, temperature, current) and applies ML ensemble models to detect early warning signs of mechanical fatigue.

## ✨ Key Features

### 1. Premium Landing Page & Live Console
Instead of generic marketing graphics, the landing page features a **Live Operations Console**. It streams real-time simulated MQTT gateway logs, ML inference results, and live metric tiles (vibration, temperature, anomaly score), demonstrating the product's value instantly.

### 2. Seamless Auth & Hardware Onboarding
- **Authentication Modal**: Clean login/signup interface.
- **2-Step Onboarding**: Users select their organization type from a dropdown and simulate pairing IoT sensors (VIB-01, TEMP-01, CURR-01, RPM-01) to the gateway with an animated pairing sequence.

### 3. Comprehensive 6-Page Dashboard
Once onboarded, users access a dense, high-performance dashboard:
- **Dashboard**: KPIs, Featured Asset (CNC-01), Machine Health Matrix, Live Anomaly Feed, Sensor Telemetry Gauges, ML Ensemble Status, Vibration Charts, and Maintenance Queue.
- **Machines**: Full asset registry with health rings and vitals.
- **Anomalies**: Deep-dive into ML detection streams, detection rate charts, and top affected assets.
- **Analytics**: Plant health trends, OEE breakdown, anomaly pie charts, downtime cause analysis, and an asset performance leaderboard.
- **Maintenance**: AI-generated work orders, engineer workload management, and cost-savings analysis.
- **Settings**: Granular control over sensor thresholds, MQTT gateways, ML retraining, and alert channels (SMS, WhatsApp, Email).

## 🎨 Visual Strategy & Design System

Senexa uses a distinctive "Athletic Industrial" design language—treating machine data with the same intensity as elite sports analytics.

- **Color Palette**: Pure black/dark gray backgrounds with **Neon Orange** (`#ff5a00`) and **Metallic Silver** gradients for high contrast and premium feel. Professional off-white (`#efece6`) for light mode.
- **Typography**: 
  - `Space Grotesk` for powerful, geometric headings.
  - `DM Sans` for clean, condensed body text.
  - `JetBrains Mono` for technical telemetry data.
- **Information Density**: Minimal whitespace, packed data grids, and monospace telemetry numbers to create a "mission control" aesthetic.
- **Dark/Light Mode**: Full theme toggle support that respects professional environments.

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3 (Custom Properties, CSS Grid, Flexbox), Vanilla JavaScript (ES6)
- **Charts & Visualizations**: Chart.js
- **Icons**: Font Awesome 6
- **Fonts**: Google Fonts (Space Grotesk, DM Sans, JetBrains Mono)

## 🚀 Getting Started

This project is built entirely in a single `index.html` file with no build steps required.

1. Clone or download the repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Explore the landing page, click **Sign Up**, complete the onboarding simulation, and view the dashboard.

## 🧠 The ML Ensemble Architecture (Simulated)

The dashboard visualizes a 4-model ensemble approach to anomaly detection:
1. **Isolation Forest**: Flags vibration anomalies (94.2% accuracy).
2. **Autoencoder**: Detects pattern reconstruction failures (91.8% accuracy).
3. **Statistical Thresholding**: Rule-based fallback (88.5% accuracy).
4. **LSTM Sequence**: Time-series prediction (89.7% accuracy).

*The system uses a Majority Vote (3/4) to trigger critical alerts, simulating real edge-inference pipelines.*

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---
*Built for thin-margin factories that can't afford enterprise IoT.*

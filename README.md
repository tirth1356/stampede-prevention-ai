# AlertX 🛡️

### AI-Powered Crowd Intelligence & Stampede Prevention System

🎥 **Demo Video:** https://www.youtube.com/watch?v=x0mNapiKdto

AlertX is an AI-driven crowd monitoring and early warning platform designed to prevent stampedes and crowd-related disasters in high-density public spaces such as pilgrimage sites, festivals, stadiums, and large-scale events.

By combining crowd flow analytics, machine learning forecasting, real-time monitoring, and AI-assisted emergency coordination, AlertX enables authorities to identify potential risks before they escalate into critical incidents.

---

## 🚀 Features

### Real-Time Crowd Risk Monitoring

* Live monitoring of crowd density, movement velocity, and flow patterns.
* Continuous calculation of Crowd Pressure Index (CPI) and congestion metrics.
* Detection of abnormal crowd behavior and bottlenecks.

### Predictive Risk Forecasting

* Machine learning models trained on historical crowd movement data.
* Forecasts potential risk zones up to 45 minutes in advance.
* Early warning alerts for crowd surges and pressure accumulation.

### AI-Powered Emergency Coordination

* Generates tactical response recommendations using LLM-powered analysis.
* Provides agency-specific directives for:

  * Police & Security Teams
  * Event Organizers
  * Transportation Authorities
  * Emergency Response Units

### Operational Command Center

* Centralized dashboard for monitoring multiple locations simultaneously.
* Live incident tracking and escalation management.
* Timestamped audit logs for operational transparency.

### High-Performance Architecture

* Real-time WebSocket communication.
* Sub-100ms inference pipeline.
* Scalable backend optimized for continuous crowd monitoring.

---

## 🏗️ System Architecture

AlertX follows a decoupled architecture consisting of:

1. **Simulation & Analytics Engine**

   * Processes crowd movement data.
   * Calculates pressure and flow metrics.

2. **Machine Learning Layer**

   * Predicts future crowd conditions.
   * Generates risk classifications and forecasts.

3. **AI Coordination Layer**

   * Uses Llama 3.1 via Groq API.
   * Produces actionable emergency response recommendations.

4. **Frontend Command Dashboard**

   * Visualizes live metrics, forecasts, and operational alerts.
   * Supports monitoring across multiple venues and regions.

---

## 🛠️ Tech Stack

### Frontend

* React 18
* Tailwind CSS
* Framer Motion
* Recharts
* Lucide React

### Backend

* FastAPI
* Python 3.10+
* Pandas
* Scikit-Learn
* Joblib

### AI & Machine Learning

* Random Forest Regression
* Crowd Pressure Index Forecasting
* Llama 3.1 8B (Groq API)

### Infrastructure

* WebSockets
* REST APIs
* Real-Time Event Streaming

---

## 📦 Installation

### Prerequisites

* Python 3.10+
* Node.js 18+
* npm

---

### Backend Setup

```bash
git clone https://github.com/tirth1356/stampede-prevention-a.git
cd stampede-prevention-a

python -m venv venv

# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate

pip install -r requirements.txt

uvicorn backend.app.main:app --reload
```

---

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_groq_api_key
```

---

## 📊 Use Cases

* Religious Gatherings
* Pilgrimage Corridors
* Stadiums & Sporting Events
* Festivals & Concerts
* Transportation Hubs
* Public Safety Operations Centers

---

## 🎯 Key Benefits

* Early identification of crowd-related risks.
* Faster emergency response coordination.
* Improved situational awareness.
* Reduced likelihood of crowd crush incidents.
* Data-driven decision making for public safety teams.

---

## 📜 License

This project is developed for research, innovation, and public safety applications.

---

### Built to help save lives through proactive crowd intelligence and AI-assisted emergency response.

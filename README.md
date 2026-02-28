# 🌱 Agro Intelligence
> **Connecting Farmers with Future Tech | A Smart Farming Ecosystem**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Prototype_Active-success)

Agro Intelligence is a comprehensive, React-based Single Page Application (SPA) designed to empower smallholder farmers. By combining traditional farming knowledge with modern AI simulations and Data Analytics, this platform acts as a **"Digital Brain"**, protecting farmers from agricultural, climatic, and financial risks.

---

## 📑 Table of Contents
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Step-by-Step Installation](#-step-by-step-installation)
- [Application Flow (How to Use)](#-application-flow-how-to-use)
- [Folder Structure](#-folder-structure)
- [Future Scope](#-future-scope)
- [Developer](#-developer)

---

## ✨ Features

* 🧑‍🌾 **Farmer Digital Twin:** Creates a personalized profile (land size, soil type, crop history, risk tolerance) to tailor AI recommendations.
* 🎛️ **Command Center Dashboard:** A live hub displaying real-time weather (via OpenWeatherMap API), soil moisture estimates, and real-time Mandi price trends.
* 🔬 **AI Crop Doctor:** An intelligent diagnostic interface where farmers upload leaf images. The system identifies diseases, explains root causes, and recommends chemical/organic treatments.
* ⚙️ **What-If Risk Simulator:** A powerful predictive tool allowing farmers to simulate environmental stressors (rainfall drop, temperature spikes) to calculate potential financial loss and receive mitigation strategies.
* 🛒 **Agri Marketplace:** A dual-sided e-commerce module for buying high-quality agricultural inputs and selling fresh produce, complete with a simulated cart and UPI payment checkout.
* 🌐 **Smart Market Intelligence:** A geo-intelligent engine that compares two different market locations, analyzing transport costs, weather, and profit margins to suggest the best place to sell.
* 🏦 **Loan Access Portal:** A streamlined system for crop/tractor loan applications featuring document upload simulation, AI verification, and automated PDF Sanction Letter generation.
* 💬 **AgroBot & Bilingual Support:** An integrated AI chatbot for instant assistance, plus seamless English ↔ Tamil language toggling.

---

## 🛠️ Tech Stack

**Frontend Architecture:**
* **Core:** React.js (Create React App)
* **Styling:** Tailwind CSS (Custom dark-theme UI)
* **Icons:** Lucide-React
* **Data Visualization:** Recharts
* **Document Generation:** jsPDF & html2pdf.js
* **Live APIs:** OpenWeatherMap API (Weather Data)

> **Note on Prototype Data:** To ensure zero latency during presentations, modules like Market Prices and AI Disease Detection utilize an advanced **Algorithmic Simulation Engine (Mock Data)**. Real-world API integration (e.g., AGMARKNET) is scoped for the production phase.

---

## 🚀 Step-by-Step Installation

Follow these steps to run the Agro Intelligence project on your local machine.

### Step 1: Prerequisites
Ensure you have [Node.js](https://nodejs.org/) (version 16 or above) and `npm` installed on your system.

### Step 2: Clone the Repository
Open your terminal or command prompt and run:
```bash
git clone [https://github.com/your-username/Agro_Intelligence.git](https://github.com/your-username/Agro_Intelligence.git)
Step 3: Navigate to the Project Directory
Move into the frontend folder where the React application resides:

Bash
cd Agro_Intelligence/frontend
Step 4: Install Dependencies
Install all required NPM packages:

Bash
npm install
(This will install react, tailwindcss, lucide-react, recharts, and jspdf as defined in the package.json).

Step 5: Start the Development Server
Launch the application:

Bash
npm start
The application will automatically open in your default browser at http://localhost:3000.

📱 Application Flow (How to Use)
Onboarding: Start at the landing page and click "Get Started". Register a new farmer account or login.

Digital Twin Setup: Fill in your farm details (Location, Land Size, Soil Type). This saves locally and calibrates the dashboard.

Dashboard Navigation: View live weather and crop recommendations. Use the bottom right Arrow Button (➡️) to navigate to the next module.

Sequential Modules:

Scan a leaf in the AI Crop Doctor.

Simulate risks in the What-If Simulator.

Buy/Sell items in the Marketplace.

Compare selling locations in Market Intelligence.

Apply for financial aid in the Loan Portal and download your generated PDF receipt.

Submit your thoughts via the Feedback system.

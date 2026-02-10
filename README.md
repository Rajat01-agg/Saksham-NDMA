# SAKSHAM - Smart Alert and Knowledge System for Hazard Awareness and Management

## 🎯 Project Overview

**SAKSHAM** is a comprehensive disaster management platform developed for **Smart India Hackathon (SIH) 2025**. This project integrates AI-powered disaster prediction, real-time alerts, capacity building, and multi-platform accessibility to enhance disaster preparedness and response across India.

### Problem Statement
Enable effective disaster management through intelligent prediction systems, multi-platform alert delivery, and capacity building initiatives for vulnerable communities.

### Solution
A complete ecosystem of interconnected applications that provide:
- 🤖 AI-powered disaster prediction and alerts
- 📱 Multi-platform accessibility (Web, Mobile, USSD, Telegram)
- 🗺️ Interactive GIS mapping and visualization
- 📊 Comprehensive analytics dashboard
- 🎓 Capacity building and training management
- 🔔 Real-time notification system

---

## 📁 Project Structure

This repository contains **7 independent modules** that work together as a unified disaster management system:

```
FinalCode/
├── Disaster_Management_prediction(CBT)/   # Disaster prediction & capacity building
├── NDMA-Saksham-BackEnd-main/             # Main backend API server
├── SAKSHAM-dashboard-map/                 # GIS mapping & visualization
├── Saksham_Dashboard-main/                # Web dashboard frontend
├── Saksham_PWA-main/                      # Progressive Web App
├── Saksham_USSD-main/                     # USSD-based offline access
└── saksham-telegram-bot/                  # Telegram bot for alerts
```

---

## 🚀 Quick Start

### Prerequisites
- Node.js (v18 or higher)
- MongoDB
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd FinalCode
   ```

2. **Setup each module** (navigate to each folder and install dependencies)
   ```bash
   # Backend
   cd NDMA-Saksham-BackEnd-main/NDMA-Saksham-BackEnd-main
   npm install
   
   # Dashboard
   cd ../../Saksham_Dashboard-main/Saksham_Dashboard-main
   npm install
   
   # PWA
   cd ../../Saksham_PWA-main/Saksham_PWA-main
   npm install
   
   # And so on for other modules...
   ```

3. **Configure environment variables**
   - Each module has its own `.env` file requirements
   - Refer to individual module READMEs for specific configurations

4. **Start the services**
   ```bash
   # Backend (Port 3000)
   npm start
   
   # Frontend (Port 5173)
   npm run dev
   ```

---

## 🔧 Module Descriptions

### 1. **Disaster Management Prediction (CBT)**
AI-powered disaster prediction system with capacity building training recommendations.
- 🌊 Flood prediction
- 🏚️ Earthquake detection
- 🔥 Forest fire monitoring
- 🎓 Training gap analysis and resource allocation

### 2. **NDMA Saksham Backend**
Central API server handling all backend operations.
- RESTful API endpoints
- MongoDB integration
- Authentication & authorization (Clerk)
- Google Generative AI integration

### 3. **SAKSHAM Dashboard Map**
Interactive GIS mapping system for disaster visualization.
- Real-time mapping with Leaflet/Mapbox
- Cluster visualization
- Weather overlays
- Emergency resource locations

### 4. **Saksham Dashboard**
Main web dashboard for administrators and officials.
- React + TypeScript + Vite
- Data visualization with Recharts
- Real-time analytics
- User management

### 5. **Saksham PWA**
Progressive Web App for offline-first user experience.
- Offline functionality with IndexedDB
- Push notifications
- Service worker caching
- Mobile-responsive design

### 6. **Saksham USSD**
USSD-based system for feature phone users.
- No internet required
- SMS-based alerts
- Simple menu navigation
- Wide accessibility

### 7. **Saksham Telegram Bot**
Automated bot for instant disaster alerts.
- Real-time notifications
- Location-based alerts
- Supabase integration
- Multi-language support

---

## 🛠️ Technology Stack

### Frontend
- **React** 19.2.0 - UI framework
- **TypeScript** - Type safety
- **Vite** - Build tool
- **Tailwind CSS** - Styling
- **Leaflet/Mapbox** - Mapping
- **Recharts** - Data visualization

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **Mongoose** - ODM
- **Clerk** - Authentication
- **Google Generative AI** - AI integration

### Additional Tools
- **Telegraf** - Telegram bot framework
- **Supabase** - Backend as a service
- **Socket.io** - Real-time communication
- **PDFKit** - PDF generation

---

## 📊 Features

### Core Features
- ✅ Multi-disaster prediction (Flood, Earthquake, Fire, Cyclone)
- ✅ Real-time alert system
- ✅ Interactive maps with resource locations
- ✅ Training capacity analysis
- ✅ Historical data analytics
- ✅ Mobile-first responsive design
- ✅ Offline functionality
- ✅ Multi-platform accessibility

### Advanced Features
- 🔔 Push notifications
- 🗺️ GIS visualization
- 📈 Predictive analytics
- 🤖 AI-powered recommendations
- 📱 Progressive Web App
- 💬 Telegram integration
- 📞 USSD support
- 📄 PDF report generation

---

## 🏆 SIH 2025 Alignment

This project addresses key government requirements:
- **Accessibility**: Multi-platform support (Web, Mobile, USSD, Telegram)
- **Inclusivity**: Works on feature phones via USSD
- **Capacity Building**: Training recommendations and resource optimization
- **Data-Driven**: AI-powered predictions and analytics
- **Real-Time**: Instant alerts and notifications
- **Scalability**: Modular architecture for easy expansion

---

## 📝 License

This project is developed for Smart India Hackathon 2025.

---

## 🤝 Contributing

This is a hackathon project. For any queries or collaboration:
- Create an issue in this repository
- Submit pull requests for improvements

---

## 🙏 Acknowledgments

- National Disaster Management Authority (NDMA)
- Smart India Hackathon 2025
- All contributors and mentors

---

## 📞 Support

For technical support or queries:
- Create an issue in this repository

---

**Made with ❤️ for SIH 2025**


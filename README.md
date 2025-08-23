# 🌍 GlobeTrotter – Intelligent Travel Itinerary Planner

**GlobeTrotter** is a personalized, intelligent, and collaborative platform for creating, managing, and sharing travel itineraries.  
Built during the **Odoo Hackathon 2025** on the "GlobeTrotter – Empowering Personalized Travel Planning" problem statement, it enables users to plan multi-city trips, explore activities, stay within budget, and visualize journeys in a seamless end-to-end experience.

---

## 🚀 Features

### 🖥️ Web Platform
- **Landing Page** – Modern UI introducing the platform and its value proposition.
- **Authentication** – User registration & login with **JWT-based authentication**.
- **Dashboard** – Personalized trip overview, recent trips, suggested destinations.
- **Itinerary Creator** – Add destinations, stops, dates, activities, and reorder trips interactively.
- **Trip Suggestion Engine** – AI-powered recommendations for destinations, budgets, and activities.
- **Travel Calendar** – Visual representation of the trip timeline.
- **Activity Selection Page** – Filter and add activities to specific destinations.
- **Trip View Page** – View detailed itineraries with budgets, images, and activities.
- **Admin Panel** – CRM dashboard for user & trip analytics, engagement metrics, and content moderation.
- **User Profile Page** – Manage account details, saved destinations, and preferences.

### 🤖 AI & APIs
- **OpenAI API** – LLM-driven itinerary suggestions, budget predictions, and activity recommendations via chat prompts.
- **Google Places API** – Fetches real-time POIs (Points of Interest) to ground AI recommendations in actual data.
- **SERP API** – Retrieves high-quality images of recommended places.
- **Hybrid Stack** – TypeScript for web development, Python for AI-driven backend services.

---

## 🛠️ Tech Stack

### Frontend
- **TypeScript**, **React.js** (Next.js App Router)
- **TailwindCSS** for styling
- **React Query** for API data fetching

### Backend
- **Python (Flask)** for AI integration services
- **Node.js / Next.js API routes** for web backend
- **MongoDB** for storing user profiles, trips, and activities
- **JWT** for secure authentication

### APIs & Services
- **OpenAI API** – AI itinerary generation
- **Google Places API** – Real-time location and POI data
- **SERP API** – Place images
- **REST & GraphQL** endpoints for frontend integration

---

## ⚙️ Setup & Installation

### Prerequisites
- Node.js 18+
- Python 3.10+
- Google Places API Key
- SERP API Key
- OpenAI API Key

### 1. Clone Repository
```bash
git clone https://github.com/Rishi2003Das/GlobeTrotter.git
cd globetrotter
```

### 2. Install requirements
```bash
npm install
pip install -r requirements.txt
```

### 3. To run the project:
```bash
npm run dev
```
## Hackathon Highlights

- Real-time data grounding – Google Places ensures accuracy.

- AI-powered personalisation – OpenAI LLM tailors trips based on preferences.

- Visual appeal – SERP API images make itineraries more engaging.

- End-to-end flow – From landing page to full itinerary visualisation.

## Deployed version
- Deployed on VERCEL - https://globe-trotter-nitrous.vercel.app/
- Demo video - https://drive.google.com/file/d/1507H7ckTVyKEK1FmQmIzAZdatwuiWDxW/view?usp=sharing

## Contributors

**TEAM NITROUS**
- Pratiki
- Rishi
- Ashwani



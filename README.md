RoomBridge – AI-Powered Room & Roommate Matching Platform

RoomBridge is a full-stack web platform designed to simplify room and roommate discovery for students and working professionals relocating to new cities. The platform leverages AI-driven matching algorithms, geolocation services, and real-time communication to connect users with the most compatible rooms and roommates.

🚀 Features

🏠 Smart Room & Roommate Matching
AI-powered compatibility scoring (0–100)
Personalized recommendations based on location, profession, college, hometown, and preferences
Smart feed with categorized recommendations

🤖 AI Assistant
Gemini AI-powered chatbot for platform guidance
Instant support and query resolution
Context-aware assistance for users

📍 Location Intelligence
Google Maps Geocoding API integration
Real-time distance calculations
Nearby room recommendations

🚨 Emergency Listings
Dedicated urgent room postings
Auto-expiration after 72 hours
Notification alerts for expiring listings

💬 Real-Time Communication
Instant messaging between users
Real-time notifications
Persistent chat history

✅ Identity Verification
Aadhaar verification
PAN verification
Student ID verification
Live selfie verification

🛡️ Trust & Safety
Ratings and reviews system
User reporting and moderation
Automated flagging and temporary bans
Admin dashboard for platform management


🛠️ Tech Stack
Frontend
React.js
TypeScript
Vite
Tailwind CSS
shadcn/ui
Framer Motion
React Router
Backend & Database
Firebase Authentication
Cloud Firestore
Firebase Storage
Firebase Security Rules
AI & APIs
Google Gemini AI
Google Maps Geocoding API


🏗️ System Architecture
React + TypeScript Frontend
            │
            ▼
Firebase Services
(Auth + Firestore + Storage)
            │
            ▼
AI Matching Engine
            │
            ├── Gemini AI API
            └── Google Maps API

            
⭐ Key Features
Feature	Description
AI Match Score	Personalized compatibility score for every listing
Smart Feed	Categorized recommendations and personalized discovery
Room Requests	Users can post room requirements
Room Listings	Owners can post available rooms
Real-Time Chat	Instant communication between users
Notifications	Alerts for messages, matches, and verification
Verification System	Secure identity verification
Admin Dashboard	Platform monitoring and moderation


🔐 Security Features
Firebase Authentication
Role-Based Access Control
Protected User Data
Verification Workflows
Moderation & Reporting System


⚙️ Installation
Clone Repository
git clone https://github.com/Sakshi0313/RoomBridge.git
cd RoomBridge
Install Dependencies
npm install
Configure Environment Variables

Create a .env file:

VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id

VITE_GEMINI_API_KEY=your_gemini_api_key
VITE_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
Run Application
npm run dev

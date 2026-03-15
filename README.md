# Trezzo – Community Based Food Spot Locator App

Trezzo is a community-driven food spot locator platform that helps users discover restaurants and hidden food gems while enabling food businesses to increase their visibility and reach new customers.

The platform combines restaurant discovery, reservation management, and feedback systems into a single interface designed for both customers and restaurant owners.

---

## Problem Statement

Many small food vendors struggle to compete with large restaurant chains due to limited visibility and digital presence. At the same time, customers often find it difficult to discover unique local food spots that match their preferences.

Trezzo addresses this problem by providing a centralized platform where users can discover restaurants, make reservations, and explore hidden culinary experiences.

---

## Objectives

- Enable easy discovery of restaurants through an interactive map.
- Allow users to book tables with time-slot management.
- Improve visibility for small and local food businesses.
- Provide a platform for feedback and ratings.
- Offer dashboards for restaurant owners and administrators.

---

## Target Users

### Customers
- Discover nearby restaurants and food spots
- Book tables in advance
- View reviews and ratings

### Restaurant Owners
- List their restaurant or food spot
- Manage offers, events, and menus
- Track user engagement

### Admin
- Approve or reject restaurant listings
- Manage platform content
- Monitor analytics and activity

---

## Technology Stack

**Frontend**
- React (Vite)

**Backend**
- Firebase Authentication

**Database**
- MongoDB

**APIs**
- Google Maps API

---

## Core Features

### User Authentication
Secure login and registration using Firebase Authentication.

### Restaurant Discovery
Interactive map interface showing nearby food spots.

### Reservation System
Users can book tables using a time-slot system that prevents booking conflicts.

### Owner Dashboard
Restaurant owners can manage listings, menus, and promotional offers.

### Feedback and Ratings
Users can leave reviews and ratings for restaurants.

---

## Key Functionalities

### Recommendation Logic
Highlights both trending restaurants and small-scale food vendors to ensure fair visibility.

### Sentiment Analysis
Analyzes user reviews to determine positive and negative sentiment percentages.

### Table Availability Management
Ensures accurate real-time table availability and prevents overlapping bookings.

---

## System Architecture
                 +----------------------+
                 |        Users         |
                 +----------+-----------+
                            |
                            v
                 +----------------------+
                 |   React Frontend     |
                 |   (User Interface)   |
                 +----------+-----------+
                            |
            -------------------------------------
            |                  |                |
            v                  v                v
    +--------------+   +---------------+  +---------------+
    | Firebase     |   | Google Maps   |  |   Backend     |
    |Authentication|   | API (Location)|  |  Services     |
    +--------------+   +---------------+  +---------------+
                                            |
                                            v
                                     +--------------+
                                     |   MongoDB    |
                                     |   Database   |
                                     +--------------+


---

## System Modules

1. **User Authentication Module**
2. **Restaurant Discovery Module (Map Based)**
3. **Reservation and Time Slot Booking**
4. **Restaurant Owner Dashboard**
5. **Feedback and Rating System**
6. **Admin Management Panel**

---

## Challenges Faced

- Integrating Firebase Authentication with the backend system.
- Managing multiple APIs including Google Maps.
- Designing a dual-interface system for both users and restaurant owners.
- Transitioning from Expo workflow to React Web during development.

---

## Results

The project produced a working prototype with:

- Map-based restaurant discovery
- Table reservation functionality
- Owner dashboard for listing and event management
- Admin panel for restaurant approvals and analytics
- Smooth UI performance with fast data retrieval

---

## Future Scope

- Voice-based search and smart assistant integration
- AI-driven demand prediction and trend forecasting
- Monetization strategies for restaurants
- Customer support and chat integration

---

## Project Team

- Aysha Nabeel  
- Naveena Joy  
- Nikitha Tom  
- Sanaa Mariya Nisan  

**Project Guide**  
Mr. Ajith Jacob

---

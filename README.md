# AI Smart Weekend Trip Planner ✈️🗺️

An intelligent multi-agent weekend trip planner that takes user preferences, budget, and constraints, and generates a personalized day-by-day travel itinerary with estimated costs and transparent reasoning.

## 🚀 Version 1.0 Features

* **User Preference Form:** Input your destination, duration, budget, interests (e.g., nature, food, culture), and constraints (e.g., minimal walking).
* **AI Trip Generation:** Backend logic processes constraints to assemble an optimized daily schedule with recommended order and estimated costs.
* **Mock Database:** Built-in curated database of locations to test and validate itineraries without external API dependencies.
* **Interactive Flow:** Fill out preferences -> Send to server -> Receive structured itinerary.

---

## 🛠️ Tech Stack

* **Frontend:** React (Form input and itinerary display UI)
* **Backend:** Node.js, Express (REST API and agent orchestration logic)
* **Database:** MongoDB (Planned for user profiles and saved itineraries storage)

---

## 🔄 Core Agent Workflow

1. **Intake & Validation:** Receives destination, days, budget cap, interests, and physical constraints.
2. **Filtering & Matching:** Filters the local repository of activities against user constraints (e.g., budget limits, low-walking options).
3. **Itinerary Assembly:** Sequences activities logically by day and time, calculating total estimated costs.
4. **Explanation Layer:** Generates clear reasoning for why each activity was chosen based on the user's profile.

---

## 🎯 Example Scenario

* **Input:** 
  * Budget: Up to 500 NIS
  * Constraints: Minimal walking
  * Interests: Nature & Food
* **Output:** A customized weekend plan featuring low-walking scenic spots and budget-friendly local dining, complete with cost breakdowns and rationale.

---

## 📦 Getting Started (Coming Soon)

Instructions for setting up and running the project locally will be added as development progresses.

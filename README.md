# AI Weekend Trip Planner ✈️🗺️

An AI-powered weekend trip planner that creates personalized itineraries from a user's destination, interests, budget, and constraints.

## Version 1.0

- **Preference form:** Enter a destination, trip length, budget in NIS, interests, and constraints such as minimal walking.
- **Personalized itinerary:** Get a day-by-day plan with activities, suggested order, estimated costs, and explanations.
- **Curated activity catalogue:** The planner uses local sample data, so no external API is needed for the first version.
- **Editable results:** Review the plan and request changes.

## Tech Stack

- **Frontend:** React
- **Backend:** Node.js and Express
- **Database:** MongoDB, planned for saving user profiles and itineraries

## How the Planner Works

1. The server validates the user's preferences and constraints.
2. The AI agent searches the activity catalogue for suitable options.
3. The server checks the proposed itinerary against the budget and other rules.
4. The agent explains why the activities fit the user's preferences.

## Example

**Input:** A two-day trip, budget up to 500 NIS, interests in nature and food, and minimal walking.

**Output:** A suggested two-day itinerary with suitable activities, estimated costs, and a short explanation for each choice.

## Getting Started

Setup instructions will be added as development progresses.

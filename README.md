# Trip
Planner
# AI Trip Planner

## Summary
AI Trip Planner is a simple AI-inspired travel planning website that creates personalized trip itineraries based on the user's destination, number of days, budget, travel style, and interests.

## Background
* **The problem:** Planning a trip can take a lot of time because travelers need to consider destinations, activities, budget, interests, and the number of days available. Different travelers also want different experiences—for example, one person may prefer adventure activities while another prefers relaxing places, food, or cultural experiences.
* **Project overview:** AI Trip Planner is a web-based travel planning prototype (`HTML`, `CSS`, `JavaScript`) hosted on GitHub Pages that creates a personalized day-by-day travel itinerary. The goal is to explore how an AI-based system can use personal preferences to make travel planning faster and more convenient.

## Data and AI techniques
* **Data sources:** A full AI version would use travel-related datasets containing tourist attractions, locations, activity types, average costs, popularity, user ratings, travel durations, opening hours, user preferences, and previous recommendations. The current frontend prototype does not require an external dataset because it focuses on demonstrating the interface and basic personalization logic.
* **AI techniques:** The main AI concept behind this project is personalized recommendation. Future versions could use **Recommendation Systems** (matching destinations and activities based on similar users or preferences) and **Machine Learning** models that learn from user ratings and feedback to improve future itineraries.
* **Workflow:** `User Preferences (Destination, Budget, Travel Style, Interests) → Recommendation System → Personalized Activities → Day-by-Day Itinerary`

## How is it used
* **Users & Context:** Travelers open `index.html` (or the GitHub Pages site), enter their destination, number of days, budget, travel style, and personal interests, and click **Generate My Trip** to receive a customized day-by-day itinerary.
* **Project structure:**
  ```text
  AI-Trip-Planner/
  ├── index.html
  ├── style.css
  ├── script.js
  └── README.md
  ```

## Challenges
* **Personalization complexity:** Travel preferences vary widely from person to person, and recommendations must balance multiple preferences and budget limits at the same time.
* **Dynamic data & accuracy:** Travel information, opening hours, and budget estimates change over time, and high popularity does not always mean a place suits a specific user.
* **Current limitations:** The current version is a frontend prototype that relies on predefined personalization logic rather than a live AI model or real-time travel database.

## What next
* Connect real AI recommendation models and a natural-language AI travel assistant.
* Integrate live weather information, real-time travel costs, map views, hotel recommendations, and transportation suggestions.
* Add user accounts to save previous trips, collect user ratings and feedback, and support automatic itinerary optimization.

## Acknowledgments
* Inspired by the **Building AI** course by the University of Helsinki and Reaktor.
* Built using standard web technologies (`HTML`, `CSS`, `JavaScript`) and hosted with GitHub Pages.

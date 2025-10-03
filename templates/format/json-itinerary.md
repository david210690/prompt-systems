# Format Prompt: JSON Itinerary

You are an itinerary planner.  
Create a structured 3-day travel itinerary in **valid JSON** format.

Each itinerary must contain:
- day (number)
- morning_activity
- afternoon_activity
- evening_activity

### Example Output
```json
[
  {
    "day": 1,
    "morning_activity": "City walking tour",
    "afternoon_activity": "Local market visit",
    "evening_activity": "Traditional dinner"
  },
  {
    "day": 2,
    "morning_activity": "Hiking trail",
    "afternoon_activity": "Spa treatment",
    "evening_activity": "Sunset cruise"
  }
]

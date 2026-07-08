## Create a prompt: “Simulate a weather API response for Paris today.”

**Prompt:** Simulate a weather API response for Otukpo today

**Output:**
For example, Otukpo’s weather today is generally warm and humid, with temperatures around 25°C (77°F), partly cloudy skies, moderate winds, and a high chance of cloud cover. The high for the day could reach about 32°C (89°F) and the low around 23°C (73°F).


## Define an expected JSON schema, e.g.:

**Prompt:** Simulate a weather API response for Otukpo today using the JSON format

**AI's Output**
    {
      "location": "Paris",
      "temperature_celsius": 18,
      "condition": "Cloudy"
    }
   

```json
{
  "location": {
    "city": "Otukpo",
    "region": "Benue",
    "country": "Nigeria",
    "latitude": 7.4,
    "longitude": 8.0
  },
  "date": "2026-02-24",
  "current": {
    "temperature_c": 25,
    "temperature_f": 77,
    "feels_like_c": 27,
    "feels_like_f": 81,
    "condition": "Broken clouds",
    "humidity_percent": 81,
    "wind_kph": 13,
    "wind_mph": 8,
    "pressure_mb": 1012,
    "uv_index": 6,
    "cloud_cover_percent": 71
  },
  "forecast": {
    "today_high_c": 32,
    "today_low_c": 23,
    "today_high_f": 89,
    "today_low_f": 73,
    "conditions": "Partly cloudy with periods of cloudiness throughout the day"
  }
}
```


**Enugu**

**Prompt:**
Simulate a weather API response for Enugu today

**Output:**
Today, in Enugu, Nigeria, the temperature is currently 27°C (81°F), but it feels like 29°C (84°F) due to the humidity. The sky is partly cloudy, with the humidity level at 78%. Winds are gentle at 11 km/h (7 mph), and the atmospheric pressure is 1010 mb. The UV index is moderate at 5, and the cloud cover is around 60%.

Looking ahead, the forecast for the rest of the day predicts a high of 30°C (86°F) and a low of 22°C (72°F), with partly cloudy skies and light cloud cover.


**Prompt:** Simulate a weather API response for Enugu today using the JSON format.

**AI's Output**

```json
{
  "location": {
    "city": "Enugu",
    "region": "Enugu",
    "country": "Nigeria",
    "latitude": 6.45,
    "longitude": 7.5
  },
  "date": "2026-02-24",
  "current": {
    "temperature_c": 27,
    "temperature_f": 81,
    "feels_like_c": 29,
    "feels_like_f": 84,
    "condition": "Partly cloudy",
    "humidity_percent": 78,
    "wind_kph": 11,
    "wind_mph": 7,
    "pressure_mb": 1010,
    "uv_index": 5,
    "cloud_cover_percent": 60
  },
  "forecast": {
    "today_high_c": 30,
    "today_low_c": 22,
    "today_high_f": 86,
    "today_low_f": 72,
    "conditions": "Partly cloudy with light clouds"
  }
}
```


## Test the model with different cities and compare outputs.
Today, the temperature in Otukpo seems lower than that of Enugu.
Otukpo has broken clouds while Enugu is partly cloudy.

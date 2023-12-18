```
//help for functions in OPENAI
//https://api.openai.com/v1/chat/completions
{
  "model": "gpt-3.5-turbo",
  "messages": [
    {
      "role": "system",
      "content": "You are a helpful assistant."
    },
    {
      "role": "user",
      "content": "london"
    }
  ],
  "functions": [
    {
      "name": "displayData",
      "description": "Get the current weather in a given location.",
      "parameters": {
        "type": "object",
        "properties": {
          "country": {
            "type": "string",
            "description": "Country name."
          },
          "countryCode": {
            "type": "string",
            "description": "Country code. Use ISO-3166"
          },
          "USstate": {
            "type": "string",
            "description": "Full state name."
          },
          "state": {
            "type": "string",
            "description": "Two-letter state code."
          },
          "city": {
            "type": "string",
            "description": "City name."
          },
          "unit": {
            "type": "string",
            "description": "location unit: metric or imperial."
          }
        },
        "required": [
          "countryCode",
          "country",
          "USstate",
          "state",
          "city",
          "unit"
        ]
      }
    }
  ],
  "function_call": "auto"
}
```

Message:

```
const sysMsg = `In a conversational professional tone, answer the [Question] based on the [Weather Data].

- Provide an opinion about what the weather feels like.
- Provide temperature in either Celsius or Fahrenheit, whichever is more appropriate.
- Never display the temperature in Kelvin.
- Provide a recommendation on how to prepare and what to wear (e.g. bring an umbrella, wear a wind breaker, a warm jacket, etc.)`;

Question: how should I dress for the weather today?


Weather Data: {
  "coord": {
    "lon": 10.99,
    "lat": 44.34
  },
  "weather": [
    {
      "id": 501,
      "main": "Rain",
      "description": "moderate rain",
      "icon": "10d"
    }
  ],
  "base": "stations",
  "main": {
    "temp": 298.48,
    "feels_like": 298.74,
    "temp_min": 297.56,
    "temp_max": 300.05,
    "pressure": 1015,
    "humidity": 64,
    "sea_level": 1015,
    "grnd_level": 933
  },
  "visibility": 10000,
  "wind": {
    "speed": 0.62,
    "deg": 349,
    "gust": 1.18
  },
  "rain": {
    "1h": 3.16
  },
  "clouds": {
    "all": 100
  },
  "dt": 1661870592,
  "sys": {
    "type": 2,
    "id": 2075663,
    "country": "IT",
    "sunrise": 1661834187,
    "sunset": 1661882248
  },
  "timezone": 7200,
  "id": 3163858,
  "name": "Zocca",
  "cod": 200
}

```

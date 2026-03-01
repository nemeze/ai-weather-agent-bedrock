# AI Weather Agent (AWS Bedrock + Claude 4.5)

An intelligent AI-powered weather assistant that:

- Uses Claude 4.5 Sonnet via AWS Bedrock
- Dynamically generates National Weather Service API calls
- Fetches real-time forecast data
- Converts raw JSON into human-readable summaries using AI

---

## 🛠 Tech Stack

- Python
- AWS Bedrock
- Anthropic Claude 4.5
- National Weather Service API
- Git & GitHub

---

## 🚀 How It Works

1. User enters a location
2. Claude generates the correct NWS API endpoint
3. The agent fetches live weather data
4. Claude processes and summarizes the forecast
5. Clean weather report is displayed to the user

---

## ▶️ Run Locally

```bash
python weather_agent_cli.py

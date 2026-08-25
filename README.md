# 🌍 AI Travel Planner Agent

An AI-powered travel planning application that generates personalized trip itineraries, budget estimates, accommodation suggestions, and travel recommendations using an agentic AI workflow.

## Features

* 🗺️ Personalized travel itineraries
* 💰 Budget and cost estimation
* 🏨 Hotel recommendations
* 🍽️ Food and attraction suggestions
* 💱 Currency conversion
* 🤖 AI-generated travel plans
* 🌐 FastAPI backend with Streamlit frontend

## Tech Stack

* **Frontend:** Streamlit
* **Backend:** FastAPI
* **AI Framework:** LangChain, LangGraph
* **LLM:** OpenAI / Groq
* **APIs:** Google Places API, Exchange Rate API

## Installation

```bash
git clone https://github.com/your-username/travel-planner-agent.git
cd travel-planner-agent

python -m venv .venv

# Windows
.venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file:

```env
OPENAI_API_KEY=your_api_key
GOOGLE_PLACES_API_KEY=your_api_key
EXCHANGE_RATE_API_KEY=your_api_key
```

## Run the Application

### Start Backend

```bash
uvicorn main:app --reload --port 8000
```

### Start Frontend

```bash
streamlit run app.py
```

## Example Query

```text
Plan a 5-day trip to Goa with a budget of ₹30,000.
```

## API Endpoint

**POST** `/query`

```json
{
  "question": "Plan a trip to Goa for 5 days"
}
```

## Future Enhancements

* PDF itinerary download
* Flight and hotel booking integration
* Interactive maps
* Weather forecasting
* Multi-city trip planning


## Author

**Hemant Kumar Bajaj**
B.Tech, NITK Surathkal

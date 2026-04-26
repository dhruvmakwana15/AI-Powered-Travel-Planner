# ✈️ AI-Powered Travel Planner (LangChain Agent + HuggingFace)

An intelligent travel planning assistant built using LangChain Agents, HuggingFace LLaMA-3, and DuckDuckGo Search Tool.
The system generates personalized travel plans including transport options, hotel suggestions, and itineraries based on user input.

## 🚀 Features
- 🤖 AI-powered travel planning using LLM (LLaMA-3)
- 🧠 ReAct-based agent (Reasoning + Acting)
- 🔍 Real-time web search using DuckDuckGo tool
- 📍 Personalized trip planning (origin → destination)
- 💰 Budget-aware recommendations
- 📅 Generates structured 3-day itinerary

## 🛠️ Tech Stack
- Python
- LangChain (Agents, Tools, Prompting)
- HuggingFace (LLaMA-3 model)
- DuckDuckGo Search Tool
- dotenv (API key management)

## ⚙️ Setup Instructions
 1. Clone Repository  
git clone https://github.com/username/repo-name.git  
cd your-repo-name
 2. Create Virtual Environment  
python -m venv venv  
venv\Scripts\activate   
 3. Install Dependencies  
pip install -r requirements.txt
 4. Add API Key  
Create a .env file:  
HUGGINGFACEHUB_API_TOKEN=your_api_key_here
 5. Run Application  
python travel_agent.py

## 💡 How It Works
- Uses ReAct Agent framework for reasoning + action
- Integrates DuckDuckGo search tool to fetch real-time data
- LLM analyzes user query and decides:
  - When to search
  - What to generate
- Produces a structured travel plan including:
  - Transport options
  - Hotel suggestions
  - Daily itinerary

## 🧪 Example Interaction  
Enter your origin city: Ahmedabad  
Enter your destination city: Goa  
Enter your budget: 15000 INR  
Preferred transport: flight  
 ✅ Output:  
  ✈️ Travel options  
  🏨 Hotel recommendations  
  📅 3-day itinerary  


Emerging Tech Research Assistant 🚀

This project uses CrewAI with multiple AI agents to automatically research and summarize emerging technologies. It integrates LLMs (Gemini) with Firecrawl Search Tool to fetch real-time data, analyze trends, and provide easy-to-read summaries.

📌 Features

🤖 AI Agents:

Tech Researcher – Finds top emerging technologies gaining traction.

Tech Summarizer – Converts complex findings into simple one-liners.

🔎 Web Search Integration using Firecrawl API.

📊 Trend Analysis for technologies in 2025 and beyond.

⚡ Sequential Task Execution with CrewAI.

🛠️ Installation

Clone this repository and install dependencies:

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

pip install "crewai[tools]"
pip install firecrawl-py

🔑 API Keys

This project requires API keys:

FIRE_CRAWL_API_KEY – for Firecrawl search.

GOOGLE_API_KEY (Gemini API) – for LLM access.

Set them in your environment or Colab:

from google.colab import userdata
SEARCH_API_KEY = userdata.get("FIRE_CRAWL_API_KEY")
GEMINI_API_KEY = userdata.get("GOOGLE_API_KEY")

▶️ Usage

Run the notebook in Google Colab or locally:

from crewai import Agent, Task, Crew, LLM
from crewai_tools import FirecrawlSearchTool

# Define agents and tasks
# Run crew.kickoff() to get results


Output:

Top 5 emerging technologies with descriptions.

Simplified one-line summaries for quick reading.

📂 Project Structure
├── Emerging_Tech_Research.ipynb   # Main notebook
├── README.md                      # Project documentation
└── requirements.txt               # Dependencies (optional)

🚀 Example Results

Quantum Computing – Transforming secure communications and finance.

AI-Driven Drug Discovery – Speeding up medical breakthroughs.

Edge AI – Smarter devices at the network edge.

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss.

📜 License

This project is licensed under the MIT License.

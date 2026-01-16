# Deep Research Agent (Gemini DevPost)

## Overview
An automated deep research agent leveraging the Gemini 1.5 Pro context window. This tool automates the process of gathering, analyzing, and synthesizing vast amounts of information on complex topics, producing comprehensive research reports.

## Features
-   **Deep Search**: Recursively crawls web sources for relevant data.
-   **Context Analysis**: Utilizes Gemini's 1M+ token window to digest multiple documents.
-   **Report Synthesis**: Generates structured, citation-backed research papers.
-   **Fact Checking**: Cross-verifies information across multiple sources.

## Technology Stack
-   **Model**: Gemini 1.5 Pro.
-   **Framework**: LangChain for agent orchestration.
-   **Search**: Google Custom Search API / Tavily API.
-   **Language**: Python.

## Usage Flow
1.  **Query**: User inputs a research topic (e.g., "Future of Solid State Batteries").
2.  **Plan**: Agent creates a research plan and search queries.
3.  **Gather**: System scrapes and reads pertinent articles.
4.  **Synthesize**: AI compiles findings into a detailed report.

## Quick Start
```bash
# Clone the repository
git clone https://github.com/Nytrynox/Gemini-DevPost.git

# Install dependencies
pip install -r requirements.txt

# Run the agent
python research_agent.py --topic "Your Topic"
```

## License
MIT License

## Author
**Karthik Idikuda**

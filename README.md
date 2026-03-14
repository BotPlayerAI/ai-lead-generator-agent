# **AI Lead Generation Agent**

A simple **AI-powered sales agent** built with Python and LangChain that automatically:

- Finds potential business leads
- Researches their websites
- Extracts useful information
- Generates personalized outreach messages
- Saves the results to a text file

This project demonstrates how to build a **tool-using AI agent** capable of performing real-world tasks like web search, scraping, and structured data generation.

---

# **Project Overview**

This project implements a simple **AI agent architecture** using Python and LangChain.

The agent can:

1. Search for businesses online
2. Scrape website content
3. Analyze company information
4. Generate outreach messages
5. Save the results automatically

Large Language Models alone cannot access live data. By giving the model tools, we enable it to retrieve information and act on it dynamically.

This approach allows the agent to combine reasoning with external data sources.

---

# **How the Agent Works**

The workflow of the AI agent is:

```
User Query
     ↓
LLM Reasoning
     ↓
Tool Selection
     ↓
Tool Execution
     ↓
Information Analysis
     ↓
Structured Output
     ↓
Save Results
```

## **Step-by-step process**

1️. The user provides a query requesting leads.
2. The AI agent uses a **search tool** to find businesses.
3️. The agent retrieves company information from search results.
4️. Website content is scraped and cleaned.
5️. The AI analyzes the content to identify potential IT needs.
6️. The agent generates an outreach message.
7️. The results are formatted into structured JSON.
8️. The agent saves the output to a text file.


---

# **Tech Stack**

- Python
- LangChain
- OpenAI / LLM API
- DuckDuckGo Search
- BeautifulSoup (Web scraping)
- Pydantic (Structured output)
- dotenv (Environment variables)

The project uses LangChain tools so the model can interact with external systems like search engines and web pages.

---

# **Features**

- Tool-based AI agent
- Web search capability
- Website scraping
- Structured data generation
- Automated outreach generation
- Output saved to file

---

# **Installation**

Clone the repository:

```
https://github.com/BotPlayerAI/ai-lead-generator-agent.git
cd simple-ai-lead-agent
```

Install dependencies:

```
pip install -r requirements.txt
```

---

# **Environment Variables**

Inside the ```.env``` file, put your OpenAI API Key:

```
OPENAI_API_KEY=your_api_key_here
```

---

# **Running the Agent**

Run the program:

```
python main.py
```

Example query:

```
Find and qualify 5 local businesses that might need IT services.
```

The agent will:

1. Search for businesses
2. Research their websites
3. Generate summaries
4. Produce outreach messages
5. Save the results to ```leads_output.txt```

---

# **Example Output**

```
Company: XYZ Construction
Contact Info: xyzconstruction.com/contact
Email: info@xyzconstruction.com

Summary:
Local construction company that could benefit from
cloud infrastructure and website modernization.

Outreach Message:
Hi XYZ Construction team,
I noticed your company specializes in construction
services in Vancouver. We help businesses modernize
their IT infrastructure and websites...
```

---

# **Tools Used by the Agent**

## **Search Tool**

Searches the internet for company information using DuckDuckGo.

## **Scraping Tool**

Extracts readable text from company websites.

## **Save Tool**

Stores structured lead data in a local text file.

---

# **Example Use Cases**

This project can be adapted for many applications:

- Lead generation
- Market research
- Customer discovery
- Competitive analysis
- Automated outreach
- Sales prospecting

---

# **Learning Goals**

This project demonstrates:

- How AI agents work
- Tool-based reasoning
- LangChain agent architecture
- Web scraping with AI
- Structured LLM outputs

Even a simple AI agent can automate complex workflows by combining **LLM reasoning with external tools**.

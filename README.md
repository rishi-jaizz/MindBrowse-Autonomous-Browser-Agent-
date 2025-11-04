#  MindBrowse – Autonomous Browser Agent

MindBrowse is an **AI-powered browser agent** that can understand natural language commands and autonomously perform web tasks such as navigating, clicking, typing, and extracting data — acting as an **AI co-pilot for browsing the web**.



---

##  Overview

**MindBrowse** combines the power of **GPT-4**, **LangChain**, and **Airtop** to automate repetitive browser actions intelligently.
Instead of writing code or scripts, you can simply type commands like:

> “Go to LinkedIn and search for AI jobs.”

The agent will open the browser, perform the search, and return the results automatically.

---

## Features

* **Natural Language Understanding** – Uses GPT-4 to interpret user instructions.
* **LangChain Agent Framework** – Handles reasoning, tool routing, and memory for multi-step tasks.
* **Real-Time Browser Automation** – Airtop executes live browser actions like clicking, typing, navigation, and scraping.
* **Modular Workflows** – Built with Node.js to support reusable subflows for sessions and interactions.
* **Practical Use Cases** – Job application autofill, lead scraping, price comparison, and data research.

---

##  Tech Stack

| Component          | Technology                                            |
| ------------------ | ----------------------------------------------------- |
| Language Model     | OpenAI GPT-4                                          |
| Agent Framework    | LangChain                                             |
| Browser Automation | Airtop                                                |
| Backend            | Node.js, JavaScript                                   |
| Memory             | Simple Memory                                         |
| Architecture       | Modular subflows for session, window, and DOM control |

---

## How It Works

1. **User Input** – The agent receives a natural language instruction.
2. **Task Parsing** – GPT-4 interprets the request and identifies actions.
3. **Tool Selection** – LangChain routes the task to the correct Airtop tool (e.g., load page, click, type, extract).
4. **Execution** – Airtop performs the browser actions in real-time.
5. **Result Extraction** – The agent queries the page and returns structured data or confirmation.

---

## Example Command Flow

**Input:**

> “Open Amazon and search for laptops under ₹60,000.”

**Steps Executed:**

1. Start a browser session in Airtop
2. Load Amazon
3. Type “laptops under 60000” in the search box
4. Click the search button
5. Extract product titles and prices

---

## Results & Impact

* Automated repetitive browsing workflows saving significant manual effort.
* Created a **flexible alternative** to traditional automation tools like Selenium.
* Showcased integration of **LLMs + browser automation** for real-world use cases.

---

## Author

Rishi Jaiswal

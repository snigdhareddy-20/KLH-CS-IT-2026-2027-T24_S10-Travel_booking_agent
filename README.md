# Safe Tool-Calling Travel Booking Agent with Allow-Lists

## 1. Project Overview

**Project Domain:** Travel  
**Project Title:** Safe Tool-Calling Travel Booking Agent with Allow-Lists

## 2. Team Members

| Student ID | Name |
|---|---|
| 2520090190 | A Sumanjali |
| 2520090160 | B Snigdha |
| 2520090046 | G Shivani |

**Project Supervisor:** Dr. Y. Lakshmi Prasanna

## 3. Abstract

The Safe Tool-Calling Travel Booking Agent is a Generative AI-based application designed to assist users in planning their travel through natural language interactions. The system uses a Large Language Model (LLM) to understand user requests and invoke predefined tools for travel-related activities such as searching destinations, checking hotel availability, exploring transportation options, and generating travel itineraries.

To ensure safe and controlled execution, the system implements an allow-list mechanism that restricts the AI agent to authorized tools and operations. Unauthorized tool calls are rejected, preventing unintended actions and improving system reliability.

The project aims to demonstrate how Generative AI agents can interact with external tools while maintaining security, transparency, and controlled execution.

## 4. Technologies Used

- **Programming Language:** Python
- **Frontend:** Streamlit
- **Backend:** Python
- **AI Model:** Gemini API / compatible LLM
- **Agent Framework:** Python-based tool-calling implementation
- **Security:** Allow-list-based tool validation
- **Development Environment:** Visual Studio Code

## 5. Project Features

- Natural language-based travel assistance.
- Destination and travel information search.
- Hotel and transportation availability checks using simulated or permitted tools.
- Automated travel itinerary generation.
- Controlled AI tool execution through allow-lists.
- Rejection of unauthorized tool calls.
- User-friendly interactive interface.

## 6. Project Setup and Execution

### Prerequisites

- Python 3.10 or above
- Visual Studio Code
- Internet connection
- Gemini API key (if using Gemini)

### Step 1: Clone the Repository

```bash
git clone <repository-url>
cd <project-folder>
```

### Step 2: Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows:**
```bash
venv\Scripts\activate
```

**Linux / macOS:**
```bash
source venv/bin/activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Configure Environment Variables

Create a `.env` file in the project directory.

```env
GEMINI_API_KEY=your_api_key_here
```

Do not upload API keys or other credentials to GitHub.

### Step 5: Run the Application

```bash
streamlit run app.py
```

Open the local URL displayed in the terminal to access the application through your browser.

*Note: The repository structure, dependencies, and execution commands will be finalized during implementation.*

## 7. Current Project Phase Status

**Current Phase: Phase 1 – Project Selection and Planning**

| Phase | Description | Status |
|---|---|---|
| Phase 1 | Project selection and team formation | Completed |
| Phase 2 | Requirement analysis and system design | Pending |
| Phase 3 | AI model and tool integration | Pending |
| Phase 4 | Allow-list security implementation | Pending |
| Phase 5 | Frontend and backend development | Pending |
| Phase 6 | Testing and evaluation | Pending |
| Phase 7 | Final demonstration and documentation | Pending |

## 8. Expected Outcome

The expected outcome is a functional AI-powered travel assistant capable of understanding user requests, invoking authorized travel-related tools, generating travel itineraries, and rejecting unauthorized operations through an allow-list-based security mechanism.

The project will demonstrate the practical implementation of Generative AI agents, tool calling, and secure AI application development.

---

**Project Supervisor:** Dr. Y. Lakshmi Prasanna  
**Department:** Computer Science and Engineering  
**Academic Year:** 2026–2027

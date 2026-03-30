# Advanced AI Prompt Generator

**Advanced AI Prompt Generator** is a browser-based tool that helps users create **structured, optimized prompts for AI models** such as ChatGPT, Claude, Gemini, and other large language models.

Instead of writing prompts manually, the generator guides the user through a structured interface where they define:

* the **task**
* the **audience**
* the **reasoning method**
* the **output format**
* the **language**
* the **specific task parameters**

The tool then automatically generates a **fully structured prompt** ready to be copied and used with AI systems.

---

# Purpose

Large language models perform significantly better when instructions are **clear, structured, and explicit**.

Most users write vague prompts like:

> "Write a blog post about AI."

But high-quality prompts usually contain multiple components:

* role instructions
* audience targeting
* reasoning guidance
* output formatting
* contextual information

This project solves that problem by turning prompt creation into a **guided workflow**.

The generator ensures that the AI understands:

* **what the task is**
* **how it should think**
* **who the output is for**
* **how the result should be formatted**

---

# Key Features

### 1. 50 Predefined Prompt Templates

The generator includes **50 structured templates** covering common AI use cases, such as:

* Academic Research Organizer
* Advertisement Copy Generator
* AI Chatbot Response Generator
* AI Prompt Repository
* Blog Post Outline Generator
* Book Library Organizer
* Budget & Expense Tracker
* Code Snippet Organizer
* Competitor Analysis Template
* Content Idea Brainstormer
* Customer Feedback Analyzer
* Customer Journey Map
* Customer Support Ticketing
* E-commerce Product Listing
* Email Marketing Campaign
* Employee Onboarding Checklist
* Event Planning Checklist
* Event RSVP Tracker
* Fitness Routine Builder
* Goal Tracker
* Habit Tracker
* Influencer Collaboration Tracker
* Influencer Marketing Report
* Inventory Management
* Job Application Tracker
* Learning Module Creator
* Marketing Strategy Blueprint
* Meeting Agenda Planner
* Meeting Minutes Recorder
* Multimedia Content Library
* Personal Goal Planner
* Personal Journal Entry
* Podcast Episode Planner
* Press Release Generator
* Product Comparison Table
* Product Review Collector
* Product Roadmap Planner
* Project Task Manager
* Recipe Organizer
* Risk Assessment Planner
* Sales Lead Tracker
* SEO Keyword Planner
* Social Media Content Planner
* Software Bug Tracker
* Story Plot Generator
* Survey Data Collector
* Translation Project Tracker
* Travel Itinerary Planner
* Video Script Creator
* Workshop Agenda

Each template dynamically generates **custom input fields** tailored to that task.

---

### 2. Dynamic Form Generation

When a user selects a template:

* the interface automatically loads the relevant fields
* the user fills in task-specific information
* the generator builds a structured prompt

Example:

Template:

```
Advertisement Copy Generator
```

Fields generated:

```
Headline
Body Text
Call To Action
Target Audience
```

---

### 3. AI Behavior Configuration

The generator includes advanced **AI behavior controls**.

Users can define:

#### Target Audience

Adjusts tone and complexity.

Examples:

* General Audience
* Beginners
* Business Owners
* Developers
* Educators
* Engineers
* Entrepreneurs
* Executives
* Investors
* Marketing Teams
* Policy Makers
* Product Managers
* Professionals
* Researchers
* Students
* Technical Teams

---

#### Reasoning Method

Controls how the AI processes the request.

Options include:

* Standard Reasoning
* Chain of Thought
* Comparative Analysis
* Creative Thinking
* Critical Thinking
* Decision Tree Reasoning
* First Principles Thinking
* Root Cause Analysis
* Scenario Analysis
* Step-by-Step Reasoning
* Structured Analysis
* Systems Thinking

---

#### Response Format

Defines the structure of the final output.

Examples:

* Structured Text
* Bullet Points
* Checklist
* Detailed Report
* Executive Summary
* JSON Structure
* Markdown Document
* Numbered Steps
* Strategy Framework
* Table
* Technical Specification

---

#### Language

The generator supports **65 languages**.

Examples:

* English (default)
* Amharic
* Arabic
* Azerbaijani
* Bengali
* Bhojpuri
* Bulgarian
* Burmese
* Catalan
* Chinese
* Croatian
* Czech
* Danish
* Dutch
* Estonian
* Finnish
* French
* Georgian
* German
* Greek
* Gujarati
* Hausa
* Hebrew
* Hindi
* Hungarian
* Indonesian
* Italian
* Japanese
* Kannada
* Kazakh
* Korean
* Kyrgyz
* Latvian
* Lingala
* Lithuanian
* Malayalam
* Marathi
* Mongolian
* Nigerian Pidgin
* Norwegian
* Odia
* Pashto
* Persian
* Polish
* Portuguese
* Punjabi
* Romanian
* Russian
* Serbian
* Slovak
* Slovenian
* Spanish
* Swahili
* Swedish
* Tagalog
* Tamil
* Telugu
* Thai
* Turkish
* Turkmen
* Ukrainian
* Urdu
* Uzbek
* Vietnamese
* Yoruba

---

### 4. Custom Context Sections

Users can add unlimited **additional context blocks** to refine prompts.

Each section allows the user to include:

* background information
* additional constraints
* domain knowledge
* special instructions

This allows the prompt to become **highly detailed and precise**.

---

### 5. Smart Data Protection

If a user changes the selected template while fields contain data:

* the system displays a **warning modal**
* it shows the content that may be lost
* the user can **copy the data before switching**

This prevents accidental loss of work.

---

### 6. Prompt Output Panel

Once the prompt is generated, it appears in a dedicated output panel.

Users can:

* copy the prompt
* review the structure
* export the prompt
* use it directly with an AI model

---

# How It Works

The generator follows a simple workflow.

### Step 1 — Select a Template

Choose one of the predefined prompt templates from the dropdown menu.

This determines which fields will appear.

---

### Step 2 — Configure AI Behavior

Set the AI instructions:

* Target Audience
* Reasoning Method
* Response Format
* Language

These parameters strongly influence the quality of the AI output.

---

### Step 3 — Fill Template Fields

Provide detailed information for the selected template.

Example for a blog template:

```
Topic
Tone
Target keywords
Word count
Audience
```

---

### Step 4 — Add Additional Context (Optional)

Users may add custom sections to provide extra instructions.

Examples:

```
Include SEO best practices
Avoid technical jargon
Use real world examples
```

---

### Step 5 — Generate Prompt

Click the **Generate Prompt** button.

The system compiles all input fields and settings into a **fully structured AI prompt**.

---

# Project Structure

```
project-folder/
│
├── index.html
│   Main application interface
│   Contains UI, generator logic and prompt output panel
│
├── instruction-of-use.html
│   Full documentation explaining how to use the generator
│
└── README.md
    Project documentation (this file)
```

The project runs entirely in the **browser** and does not require a backend.

---

# Installation

No installation is required.

Simply open the generator in a browser.

### Option 1 — Local Use

Download the project and open:

```
index.html
```

in any modern browser.

---

### Option 2 — GitHub Pages

You can host the generator online.

Steps:

1. Upload files to a GitHub repository
2. Go to **Repository Settings**
3. Open **Pages**
4. Select:

```
Deploy from branch → main
```

5. Save

Your tool will be available at:

```
https://stomatoloq.github.io/Advanced-AI-Prompt-Generator/
```

---

# Browser Compatibility

The generator works in all modern browsers:

* Chrome
* Edge
* Firefox
* Safari

No external libraries or frameworks are required.

---

# Who This Tool Is For

This generator is useful for:

### AI Users

People who want **better responses from AI models**.

### Prompt Engineers

Users who want **structured prompt design**.

### Developers

Teams building AI workflows.

### Researchers

People who need **precise AI instructions**.

### Content Creators

Writers generating:

* articles
* marketing content
* documentation
* various plans

---

# Advantages of Structured Prompts

Structured prompts improve AI performance by:

* reducing ambiguity
* guiding reasoning
* controlling output format
* providing context
* specifying audience

This often leads to:

* better accuracy
* more relevant responses
* more consistent results

---

# Example Generated Prompt

Example output from the generator:

```
Act as a professional marketing strategist.

Target audience: small business owners.

Reasoning method: structured analysis.

Response format: numbered steps.

Language: English.

Task:
Create a marketing campaign for a new AI automation software.

Details:
Headline: Stop wasting time on manual tasks
CTA: Start your free trial
Target audience: small business accountants

Provide a clear strategy and explain each step.
```

---

# Future Improvements

Possible enhancements:

* export prompts as JSON
* prompt library saving
* template editor
* collaborative prompt sharing
* integration with AI APIs
* prompt version history

---

# License

This project can be distributed and modified freely unless specified otherwise by the author.

---

# Author

Created as a **structured prompt engineering tool** to improve the way humans interact with AI systems.

---

# Final Note

High-quality prompts dramatically improve AI output quality.

This generator helps transform **basic requests into professional AI instructions**.

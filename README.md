# AI Market Research Agent 

An automated market research workflow built with n8n that discovers startup trends, identifies business opportunities, simulates customer interviews, and generates a full market research report using AI.

This project demonstrates how AI agents can replace hours of manual research.

---

##  Overview

Market research normally requires:
- Trend analysis
- Competitor research
- Customer interviews
- Opportunity validation

This workflow automates the entire process end-to-end.

---

##  Features

- Fetch startup trends from Reddit
- Scrape Product Hunt launches
- Extract emerging business opportunities using LLMs
- Simulate realistic customer interviews
- Generate a full market research report

---

##  Workflow Pipeline

### Step 1 — Collect Trends
- Pulls top posts from r/startups on Reddit  
- Scrapes Product Hunt homepage launches  

### Step 2 — Identify Opportunities
LLM analyzes trends to extract:
- Emerging markets
- Unmet customer pain points
- Potential startup ideas

### Step 3 — Simulate Customer Interviews
AI generates realistic interview responses including:
- Pain points
- Desired solutions
- Willingness to pay

### Step 4 — Generate Final Report
Creates a one-page research report including:
- Market size estimate
- Target customer profile
- Key pain points
- Proposed solution
- Competitor notes

---

## Tech Stack

- n8n (Workflow Automation)
- Reddit API (JSON endpoint)
- Product Hunt Web Scraping
- Local LLM (Ollama / Llama 3)

---

## 📂 Workflow Architecture

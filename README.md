# LPI Smart Agent

## Overview
This project implements an intelligent agent that dynamically selects and executes LPI tools based on user query intent.

The agent analyzes the query, chooses relevant tools, executes them, and returns structured outputs.

---

## Features

- Dynamic tool selection based on query type  
- Multi-tool execution  
- Structured JSON output  
- Simple CLI-based interaction  

---

## How It Works

The agent maps queries to tools:

- "how", "implement" → get_methodology_step + get_insights  
- "example", "case" → get_case_studies  
- "what", "explain", "overview" → smile_overview  
- get_insights is always included  

---

## Setup

Install dependencies:

```bash
npm install

# Agent Router

A demonstration project showcasing intelligent agent routing capabilities using Microsoft Semantic Kernel. This repository contains a collection of plugins and agents designed to route user queries to appropriate specialized handlers for testing and experimentation.

## Overview

This project demonstrates how to build an agent routing system that can intelligently distribute user queries to specialized plugins based on content and context. The system uses Semantic Kernel's agent framework with ChatCompletionAgent implementations to simulate real-world data retrieval scenarios.


## Project Structure

```
├── agent_router.ipynb    # Main Jupyter notebook with routing logic
├── plugins.py           # Collection of Semantic Kernel plugins
├── requirements.txt     # Python dependencies
├── .env.sample         # Environment variables template
└── README.md           # This file
```

## Setup

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Copy `.env.sample` to `.env` and configure your API keys
4. Open `agent_router.ipynb` to start experimenting

## Usage

The main functionality is demonstrated in the Jupyter notebook, which shows how queries are routed to appropriate plugins based on their content. Each plugin returns mock/simulated data for testing purposes.

## Note

This is a testing and demonstration project. All data returned by the plugins is fake and generated for educational purposes only.

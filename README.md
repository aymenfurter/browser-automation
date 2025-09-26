# Browser Automation with Azure AI Foundry

This repository demonstrates how to use Azure AI Foundry's Browser Automation tool for automated web testing and data extraction.

## 🎯 Overview

The project showcases end-to-end browser automation using Azure AI agents to:
- Automate web navigation and data extraction
- Run parallel testing sessions across multiple configurations
- Generate consolidated reports using AI-powered analysis

## 📁 Repository Structure

- **`browser_automation_demo.ipynb`** - Main demonstration notebook that:
  - Creates an AI agent with Browser Automation capabilities
  - Runs automated sessions to extract job counts from Microsoft Careers site for different countries
  - Consolidates results using Code Interpreter to generate Excel reports
  - Includes complete error handling and session tracing

- **`.env.example`** - Template for required environment variables

- **`requirements.txt`** - List of Python dependencies
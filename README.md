# Browser Automation with Azure AI Foundry

This repository demonstrates how to use Azure AI Foundry's Browser Automation tool for automated web testing and QA workflows using Gherkin scenarios.

## 📁 Repository Structure

- **`ai_agent_qa_gherkin_demo.ipynb`** - Main demonstration notebook that:
  - Creates Gherkin feature files for different test scenarios (Switzerland, Germany, and fictional Latveria)
  - Sets up a Browser Automation agent (`qa-browser-runner`) to execute QA tests
  - Runs automated testing sessions against Microsoft Careers website
  - Uses Code Interpreter agent (`qa-report-writer`) to generate Excel test reports with Pass/Fail analysis
  - Demonstrates complete QA workflow from scenario definition to reporting and cleanup

- **`requirements.txt`** - Python dependencies for running the notebook

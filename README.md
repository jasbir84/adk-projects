# Agent Development Kit (ADK) projects
This repository showcases Agent Development Kit (ADK) projects, designed for demonstration and as practical examples.

| Folder Name                          | Description                                 |
|-------------------------------------- |---------------------------------------------|
| 1-helpful-assistant                  | Example agent project for helpful assistant. This agent only uses the Gemini model to answer questions. No tools or specific instructions. |
| 2-travel-planner-agent               | Agent for planning travel itineraries. This agent uses Gemini model and a specific system instruction to answer queries about travel only. |
| 3-travel-planner-pdf-agent           | Agent for planning travel itineraries and generating a PDF report. This agent uses the Gemini model, a system instruction, and tools to create a travel plan and save it as a PDF in Google Cloud Storage. |
| 4-renovation-agent                   | Agent to assist with renovation tasks. This is a kitchen remodelling/renovation agent that is provided a sample planner and asked to create one and store in Google Cloud Storage as a PDF document. |
| 5-google-search-tool-agent           | Agent utilizing Google Search tool. This agent uses the in-build Google Search tool to ground results to Google Search results based on the query provided.          |
| 6-rag-engine-agent                   | Retrieval-Augmented Generation (RAG) agent. This agent demonstrates how you can ground the responses to a set of PDFs documents that have been created as a corpus in Google Cloud's RAG Engine managed service. The answers will be provided only from about 5 Agent whitepapers uploaded into the corpus.  |
| 7-bigquery-mcp-toolbox-agent         | Hotel Agent using MCP Toolbox for Cloud SQL. This project demonstrates how an ADK Agent can use the MCP Toolbox to integrate with a Cloud SQL (PostgreSQL) database. It simplifies connecting to traditional relational databases by providing a standardized MCP layer for data access. |
| 8-google-tasks-agent                 | Agent to interact with Google Tasks. This Agent uses a Tool that connects to the Google Tasks API and allows you to perform maintenance operations with your tasks. |
| 9-news-distribution-multi-agent      | Multi-agent system for news distribution. This is a multi-agent scenario that uses one agent to retrieve the current news and then uses a Parallel Execution Workflow to execute several agents that translate the aggregated content into different languages. |
| 10-gcp-release-notes-multi-agent     | Multi-agent project for GCP release notes using BigQuery. This is a multi-agent scenario that uses one agent to retrieve Google Cloud release notes from a BigQuery public dataset. It leverages the MCP toolbox for BigQuery integration (building on the toolbox concepts introduced in Project #7) and includes automated summarization and translation agents. |

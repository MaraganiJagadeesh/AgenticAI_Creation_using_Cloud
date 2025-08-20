🚀 Agentic AI on IBM Cloud
📌 Overview

This project demonstrates how to build and deploy an AI Agent on IBM Cloud using Watsonx.ai Studio.
The agent is powered by foundation models (like Mistral-Large) and supports document-based Q&A, tool integrations, and deployment as an API.

🛠️ Features

Create and manage projects in IBM Watsonx.ai Studio.

Integrate with Watsonx.ai Runtime.

Upload documents and build a vector index for knowledge retrieval.

Use foundation models (Mistral-Large) for intelligent responses.

Add and enable tools for task automation.

Deploy the agent with an accessible API endpoint.

⚡ Prerequisites

IBM Cloud account → Sign Up

IBM Watsonx.ai Studio access

Cloud Object Storage (Lite plan is sufficient)

📝 Setup Instructions
Step 1: IBM Cloud Setup

Log in to IBM Cloud
.

Search for Watsonx.ai Studio and create a project (Region: London recommended).

Create a Cloud Object Storage (Lite plan).

Step 2: Configure Watsonx.ai Runtime

Go to Services & Integrations → Associate Service.

Add Watsonx.ai Runtime.

Step 3: Build the AI Agent

Select Build AI Agent to automate tasks.

Choose Mistral-Large foundation model.

Upload your document → Create a vector index.

Add tools and test with sample queries.

Step 4: Deployment

Save your agent.

Create a New Deployment Space (delete old ones if needed).

Deploy the agent and check deployment status.

Access your API references and preview the deployed agent.

🎯 Usage

Upload any document and ask questions directly.

Interact with your deployed agent using the API endpoint provided in Watsonx.

Use sample agents or overwrite them with your custom agents.

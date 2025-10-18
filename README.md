# SmartAI Agent

## Overview
SmartAI Agent is a **Smart AI Assistant / Smart API Executor** built on AWS. Users type instructions into the web page and get AI-generated responses powered by Claude via AWS Bedrock.

## Features
- Chat interface with animated bubbles and timestamps.
- AWS Lambda backend handles requests and communicates with Claude.
- API Gateway exposes the Lambda for web access.
- Fully working CORS support and error handling.

## Architecture
Frontend → API Gateway → Lambda → Claude LLM → Response → Frontend

## Installation
1. Deploy Lambda using `lambda/smartapi_lambda.py`.
2. Connect Lambda to API Gateway (POST method).
3. Open `frontend/index.html` in browser.
4. Replace `YOUR_API_ENDPOINT` in `index.html` with your API Gateway URL.

## Demo
Include your YouTube / Vimeo demo link here.

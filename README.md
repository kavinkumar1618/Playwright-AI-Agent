# Playwright-AI-Agent for Salesforce Automation

This project automates Salesforce UI workflows using the Playwright testing framework together with an AI agent to assist with intelligent test generation, element selection, and adaptive flows.

## Features
- End-to-end UI automation of Salesforce pages with Playwright.
- AI-assisted test generation and element resolution (e.g., using an OpenAI-compatible agent).
- Configurable credentials and environment support for multiple Salesforce orgs.
- Example test suites and CI-friendly run commands.

## Prerequisites
- Node.js (LTS) on Windows
- `npm` or `pnpm`
- A Salesforce developer org or sandbox account
- API key for the AI provider (e.g., OpenAI) if using an external agent

## Installation
1. Clone the repository:
   - `git clone <repo-url>`
2. Install dependencies:
   - `npm install`
3. Install Playwright browsers:
   - `npx playwright install`

## Configuration
Create a `.env` file at the project root with the following variables:
- `SALESFORCE_USERNAME`
- `SALESFORCE_PASSWORD`
- `SALESFORCE_SECURITY_TOKEN` (if required)
- `AI_API_KEY` (for the AI agent)

Example `.env`:# Playwright-AI-Agent
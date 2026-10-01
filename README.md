# Kira

Kira is an AI agent for creating frontend UI components using Next.js and Tailwind CSS. It helps turn natural-language prompts into usable component code and supports iterative improvements to generated UI.

## Overview

Kira is designed to make frontend development faster by letting a user describe a component in plain English and have the agent generate an implementation that matches the request. The project is built around TypeScript, OpenAI-compatible agent tooling, and component generation workflows.

## Features

- Generate frontend components from text prompts
- Refine or modify existing component ideas
- Work with Next.js + Tailwind CSS based UI patterns
- Use an AI agent workflow for component reasoning and code generation
- Support iterative development through prompt-driven improvements

## Tech Stack

- Node.js
- TypeScript
- OpenAI Agents SDK
- LangChain
- Groq integration
- Tailwind CSS (for frontend component styling)
- Next.js (for the UI ecosystem target)

## Project Goal

The goal of Kira is to act like a frontend design-to-code assistant that can:

1. Understand a user request
2. Generate a component structure
3. Apply Tailwind-based styling
4. Produce code that can be used in a Next.js app
5. Support further modifications from follow-up prompts

## Typical Workflow

```text
User Prompt
   ↓
AI Agent interprets the requirement
   ↓
Generates or updates component code
   ↓
Component is rendered in a Next.js + Tailwind UI
   ↓
User provides feedback for iteration
```

## Getting Started

### Prerequisites

- Node.js 18+
- pnpm
- An OpenAI or compatible API key

### Installation

```bash
git clone <your-repository-url>
cd kira
pnpm install
```

### Environment Variables

Create a `.env` file in the project root:

```env
OPENAI_API_KEY=your_api_key_here
```

If your setup uses a different provider or model, update the configuration accordingly.

### Run the project

```bash
pnpm dev
```

### Build the project

```bash
pnpm build
```

## Scripts

```bash
pnpm dev      # start the project in development mode
pnpm build    # compile TypeScript
pnpm start    # run the built project
```

## Git Workflow

```bash
git status
git add .
git commit -m "Add feature or fix"
git push origin main
```

## Current Status

This project is in active development and is focused on building an AI-based frontend component generation workflow.

## License

This project is licensed under the ISC license.

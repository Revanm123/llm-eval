# LLM Evaluation Framework with PromptFoo

## Overview
A comprehensive evaluation system to test multiple Large Language Models (LLMs) on generating accurate GitHub API curl commands using automated testing and quality assessment.

## Features
- Multi-provider LLM testing (OpenAI GPT-4o-mini, GPT-4.1-nano, Google Gemini)
- Automated assertion validation for API command accuracy
- LLM-based rubrics for qualitative assessment
- Configurable testing pipeline with caching
- AIPipe integration for API access

## Technologies Used
- **PromptFoo** - LLM evaluation framework
- **YAML** - Configuration management
- **Node.js** - Runtime environment
- **AIPipe** - LLM API integration

## Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- npm package manager
- AIPipe API token

### Installation
1. Clone the repository:
2. git clone https://github.com/yourusername/llm-evaluation-promptfoo.git
cd llm-evaluation-promptfoo

text

2. Install dependencies:
npm install promptfoo

text

3. Set environment variable:
export AIPIPE_TOKEN=your_aipipe_token_here

text

### Usage
1. Run evaluation:
npx promptfoo eval -c promptfooconfig.yaml

text

2. View results:
npx promptfoo view

text

## Configuration
The `promptfooconfig.yaml` file contains:
- **Prompts**: GitHub API curl command generation tasks
- **Providers**: Three LLM models for comparison
- **Tests**: 7 assertions including endpoint validation, parameter checking, and LLM rubric evaluation

## Project Structure
llm-evaluation-promptfoo/
├── promptfooconfig.yaml # Main configuration file
├── package.json # Dependencies
├── .gitignore # Git ignore rules
└── README.md # This file

text

## Key Achievements
- Designed automated evaluation framework for LLM prompt performance
- Implemented robust assertion validation system
- Resolved complex YAML configuration parsing issues
- Built production-ready testing pipeline with error handling

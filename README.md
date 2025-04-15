# Research-Paper-Analysis-Bot-UI-PATH-STUDIO
An automated UiPath solution for processing and analyzing research papers using AI and RPA technologies.

## Overview

This bot streamlines the research paper analysis process by:
1. Processing research summaries
2. Generating relevant search phrases using AI
3. Extracting content from research papers
4. Analyzing papers using advanced AI
5. Organizing results in a structured format

## Features

- **AI-Powered Analysis**: Integrates with Grok AI for intelligent content processing
- **PDF Processing**: Automated extraction of text from research papers
- **Structured Output**: Organized storage of analyzed content
- **Search Phrase Generation**: AI-generated relevant academic search terms

## Prerequisites

- UiPath Studio ≥ 25.0
- Python 3.x
- Required UiPath Packages:
  - Document Understanding ML Activities
  - Intelligent OCR Activities
  - Python Activities
  - PDF Activities
  - UI Automation Activities
  - Web API Activities

## Project Structure

```plaintext
Research Paper Implementation Project Bot/
├── Main.xaml           # Primary workflow
├── NLP.py             # Natural Language Processing component
├── Summary.txt        # Input research summary
├── Research Papers/   # Source PDF directory
├── Data to GPT/       # Processed text files
└── Generated_Research_Phrases.txt  # Output search phrases



```

## Setup
1. Clone the repository
2. Open the project in UiPath Studio
3. Install required packages from Dependencies
4. Configure input/output directories
5. Run Main.xaml
## Usage
1. Place your research summary in Summary.txt
2. Add research papers to the Research Papers folder
3. Execute the workflow
4. Find analyzed results in Data to GPT folder
5. Use generated search phrases from Generated_Research_Phrases.txt
6. Add the correcr file paths at each stage based on your computer
## Workflow
1. Input Processing
   
   - Reads research summary
   - Processes content for AI analysis
2. AI Integration
   
   - Connects with Grok AI
   - Generates search phrases
   - Analyzes paper content
3. Document Processing
   
   - Extracts text from PDFs
   - Creates structured text files
   - Maintains processing logs
4. Content Analysis
   
   - Processes extracted text
   - Generates analytical insights
   - Stores structured results

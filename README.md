# company_broucher_generator

# Company Website Scraper & Brochure Generator

## Overview
This project is a web scraping and AI-powered tool that extracts information about a company from its website and generates a summarized brochure. The tool leverages **BeautifulSoup** for web scraping, **Gradio** for an interactive UI, and **Large Language Models (LLMs)** like **OpenAI GPT via API** and **local Llama models** to process and summarize content.

## Features
- **Web Scraping:** Extracts relevant company details from a given website using BeautifulSoup.
- **AI-Powered Summarization:** Utilizes OpenAI's GPT API and locally downloaded Llama models to generate a structured brochure.
- **Interactive UI:** Provides a user-friendly interface via Gradio to input URLs and receive AI-generated summaries.
- **Flexible AI Model Usage:** Supports both API-based LLMs and locally hosted models for cost-effective processing.

## Technologies Used
- **Python**
- **BeautifulSoup** (for web scraping)
- **Gradio** (for UI interaction)
- **OpenAI API** (for GPT-based summarization)
- **Ollama (Local Llama Model)** (for offline AI processing)
- **Requests & Typing** (for API handling and type hints)

## Installation
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. **Install Dependencies**
   ```bash
   pip install openai beautifulsoup4 requests gradio python-dotenv
   ```
3. **Set Up API Keys**
   - Create a `.env` file and add your OpenAI API key:
     ```plaintext
     OPENAI_API_KEY=your_api_key_here
     ```
   - Ensure **Ollama** is installed and running if using local models:
     ```bash
     ollama run llama3.2
     ```

## Usage
1. **Run the application**
2. **Enter the company website URL** in the Gradio UI.
3. **Choose AI model** (GPT API or Local Llama).
4. **Generate and download the summary brochure.**

## Future Improvements
- Add multi-page PDF generation for brochures.
- Improve prompt engineering for more structured outputs.
- Enhance scraping logic for more accurate company details.

## Author
- **Pouria Ebrahimnezhad**
- LinkedIn: [Pouria Ebrahimnezhad]([https://linkedin.com/in/your-profile](https://www.linkedin.com/in/pouria-ebram/))



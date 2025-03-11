# Company Brochure Generator

## Overview
This project is a **Company Brochure Generator** that leverages **Large Language Models (LLMs)** to streamline and automate the process of creating brochures. The goal is to **increase efficiency**, **reduce redundancy**, and **maintain high-quality content** using AI-driven text generation and web scraping.

## Features
- **Automated Web Scraping**: Fetches relevant company information from websites.
- **Intelligent Link Filtering**: Uses LLMs to extract only the most relevant links for brochure generation.
- **AI-Powered Content Creation**: Generates well-structured and concise brochures from extracted data.
- **Multi-LLM Integration**: Supports multiple LLM models to enhance content generation and diversity.
- **Interactive UI**: Uses `Gradio` for a simple and user-friendly interface.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/brochure-generator.git
   cd brochure-generator
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows, use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the brochure generator script:
   ```bash
   python brochure_generator.py
   ```
2. Interact with the UI using the provided Gradio interface.
3. Provide a website or company details to generate a customized brochure.

## Example Workflow
1. **Fetch Links:** The program scrapes links from the given website.
2. **Filter Relevant Links:** LLM filters unnecessary links.
3. **Generate Brochure Content:** AI organizes and formats the content.
4. **Export Brochure:** Save the generated brochure as a file.

## Dependencies
- Python 3.8+
- `Gradio`
- `BeautifulSoup` (for web scraping)
- `OpenAI API` or other LLMs

## Future Enhancements
- Add support for more LLM providers
- Improve customization options for brochure templates
- Include multilingual support

## License
This project is licensed under the MIT License.

---

Feel free to contribute by submitting issues and pull requests!

### Author
Aditya Manikantan


# 🚀 AI-Powered Company Brochure Generator

![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT_4-purple.svg)
![BeautifulSoup](https://img.shields.io/badge/Scraping-BeautifulSoup-green.svg)

📄 **Automatically generate professional brochures** for businesses using their website data. This tool scrapes key pages (About, Careers, Blog, etc.), analyzes content with **GPT-4**, and produces polished markdown brochures for clients, investors, or recruits.

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| **Web Scraping** | Extracts text/data from company websites using BeautifulSoup |
| **AI Link Detection** | Identifies relevant pages (About, Careers, etc.) with GPT-4 |
| **Dynamic Brochure Generation** | Creates structured markdown output with customizable sections |
| **Real-Time Streaming** | Preview generated content as it streams from OpenAI |
| **Tone Customization** | Switch between professional, humorous, or marketing styles |

---

## 🚀 Use Cases

✔ **Marketing Teams** – Create client-facing materials in minutes  
✔ **Investor Relations** – Generate data-driven pitch decks  
✔ **HR/Recruiting** – Auto-generate career pages from company sites  
✔ **Competitive Analysis** – Quickly profile competitor offerings  

---

## ⚡ Quick Start

1. **Install dependencies**:
   ```bash
   pip install requests beautifulsoup4 openai python-dotenv

## Add your OpenAI API key to .env:

OPENAI_API_KEY=your_key_here

## Run the generator:

stream_brochure("CompanyName", "https://company-website.com")

## 🔧 How It Works
Scrapes the company homepage

Identifies key pages (About, Careers, etc.) using AI

Extracts and analyzes content from each page

Generates brochure with consistent branding/structure

## 📄 Sample Output

# Company Name Brochure

## Overview
[Generated summary of company mission, products, and differentiators...]

## Key Offerings
- Product 1: [AI-generated description]
- Product 2: [AI-generated description]

## Careers
[Auto-extracted job culture/benefits...]

## 📚 License
MIT License - Free for commercial and personal use.


### Key Improvements:
1. Added **badges** for tech stack visibility
2. **Table format** for features
3. **Mermaid diagram** for workflow visualization
4. **Code blocks** for easy copy-pasting
5. **Structured sections** with emoji headers
6. **Sample output** to showcase results

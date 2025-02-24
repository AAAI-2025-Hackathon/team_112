# Hackathon Theme: AI in Finance

# AI-Driven ESG Investment Advisor

An innovative platform designed to evaluate companies' Environmental, Social, and Governance (ESG) performance by aggregating data from financial reports, news articles, and social media. Leveraging Yahoo Finance’s sustainability API, this project generates composite ESG scores and provides actionable investment recommendations—perfectly aligned with the hackathon theme: **AI in Finance**.

# Check-In

- Title of your submission: **[AI-Driven ESG Investment Advisor]**
- Team Members: [Rajdeep Mazumder](mailto:mazumder.rajdeep@gmail.com), [Joydeep Ghatak](mailto:joycode17@gmail.com), [Gabriello Tanhueco](mailto:gabriellotanhueco@outlook.com)
- [x] All team members agree to abide by the [Hackathon Rules](https://aaai.org/conference/aaai/aaai-25/hackathon/)
- [x] This AAAI 2025 hackathon entry was created by the team during the period of the hackathon, February 17 – February 24, 2025
- [x] The entry includes a 2-minute maximum length demo video here: [Link](https://your-link.com)
- [x] The entry clearly identifies the selected theme in the README and the video.

# Goal 

Develop an AI-driven platform that evaluates companies' Environmental, Social, and Governance (ESG) performance using data from financial reports, news articles, and social media. The platform will aggregate data—leveraging Yahoo Finance’s sustainability API—to generate ESG scores and provide actionable investment recommendations for sustainable investing.

## Why ESG Investment? ## 

Growing Investor Demand: ESG-focused investment strategies are becoming mainstream, with more investors seeking sustainable portfolios.
Regulatory Pressure: Financial institutions face increasing regulatory requirements for ESG disclosures, making accurate ESG evaluation crucial.
Data Overload: Investors must process vast amounts of unstructured data—from financial reports to social media—to assess companies’ ESG performance.

## Proposed Solution ## 

Develop an AI-powered ESG Investment Advisor that:
- Aggregates & Analyzes ESG Data: Uses multiple data sources with a strong emphasis on Yahoo Finance’s sustainability data to extract ESG metrics.
- Computes ESG Scores: Generates composite ESG scores by combining sustainability metrics (environmental, social, governance) and relevant financial indicators.
- Provides Investment Recommendations: Offers insights and personalized recommendations based on ESG performance, aiding investors in building sustainable portfolios.
- Iterates & Enhances: Allows iterative improvements such as integrating sentiment analysis from news/social media and refining scoring algorithms.

## Features & Functionalities ## 
Feature	                                 Description
ESG Score Calculation	                 AI-based scoring system that computes a composite ESG score using Yahoo Finance sustainability data and other metrics.
News & Social Media Sentiment	         (Optional Future Enhancement) NLP-based analysis to gauge public sentiment from financial news and Twitter.
ESG Financial Risk Analysis	             AI-driven risk assessment using ESG factors alongside traditional financial metrics.
Interactive Dashboard	                 A user-friendly web interface (built using Dash/Streamlit) for visualizing ESG scores and trends.
Personalized Investment Recommendations	 AI-powered recommendations based on ESG scores, investor preferences, and risk profiles.

## Technical Architecture ## 
**Data Sources**
- Financial Reports: SEC Filings, Bloomberg, Yahoo Finance API (via yfinance)
- ESG Data: Yahoo Finance’s sustainability metrics, providing ESG-related scores and ratings.
- News & Articles: (Optional) Google News API for sentiment analysis.
- Social Media: (Optional) Twitter/X API, Reddit for additional sentiment data.
- Regulatory Data: SEC ESG reports, World Bank datasets for industry benchmarks.

## Tech Stack ## 
**Component	                     Technology**
Backend :                        AI Models	Python (Scikit-Learn, TensorFlow, Hugging Face Transformers)
Data Processing :	             Pandas, NumPy, BeautifulSoup (for web scraping, if needed)
Natural Language Processing : 	 BERT, GPT-based models for sentiment analysis (for future enhancements)
Database :	                     PostgreSQL, MongoDB
Web Application	:                Flask/Django for backend; React for frontend (or use Dash/Streamlit for rapid prototyping)
Visualization :	                 Plotly, Dash, Matplotlib
APIs & External Data :	         Yahoo Finance API (yfinance), Alpha Vantage (for supplementary data), Google News API, Twitter API

## Enhancements & Future Iterations ## 
- Composite ESG Score: Combine multiple sustainability metrics (environmental, social, governance) into a single composite score.
- Sentiment Analysis: Integrate NLP models to analyze ESG news and social media sentiment.
- Investment Recommendations: Build a recommendation engine that factors in both ESG and traditional financial metrics.
- Interactive Dashboard: Develop a real-time dashboard using Dash or Streamlit to visualize ESG data and investment insights.

## Summary ## 
This project leverages Yahoo Finance’s sustainability data via the yfinance API to:

- Aggregate and analyze ESG performance for leading companies.
- Visualize sustainability scores to highlight industry leaders in environmental, social, and governance practices.
- Iterate on the solution by integrating sentiment analysis and financial risk metrics for a comprehensive AI-driven investment recommendation platform.
- This solution not only meets the hackathon theme of AI in Finance but also addresses the growing demand for sustainable, data-driven investment strategies. - - The iterative enhancements ensure that the project can evolve into a robust, full-fledged platform.

# To Run the Hack :

fetch_esg_data_using_yfinance.ipynb

# Directory Structure/Implementation Plan

```plaintext
ESG_Investment_Advisor/
├── data/                     
│   └── real_time_esg_data.csv  # Saved ESG data from Alpha Vantage
|   └── yahoo_sustainability_data.csv # Saved ESG data from Yahoo Finance
├── notebooks/                 
│   └── 1_fetch_esg_data.ipynb
│   └── 2_visualize_esg_data.ipynb
|   └──3_fetch_esg_data_using_yfinance.ipynb
├── api/                       
│   └── app.py                  # ESG API (optional)
├── README.md                   # Project documentation
└── requirements.txt            # Python dependencies

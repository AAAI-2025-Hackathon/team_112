# Hackathon Theme: AI in Finance
- Goal: Develop an AI-driven platform that evaluates companies' Environmental, Social, and Governance (ESG) performance using financial reports, news articles, and social media data. The platform will generate ESG scores and provide investment recommendations.
  
# Check-In

- Title of your submission: **[AI-Driven ESG Investment Advisor]**
- Team Members: [Rajdeep Mazumder](mailto:mazumder.rajdeep@gmail.com), [Joydeep Ghatak](mailto:joycode17@gmail.com), [Gabriello Tanhueco](mailto:gabriellotanhueco@outlook.com)
- [x] All team members agree to abide by the [Hackathon Rules](https://aaai.org/conference/aaai/aaai-25/hackathon/)
- [x] This AAAI 2025 hackathon entry was created by the team during the period of the hackathon, February 17 – February 24, 2025
- [x] The entry includes a 2-minute maximum length demo video here: [Link](https://your-link.com)
- [x] The entry clearly identifies the selected theme in the README and the video.


# AI-Driven ESG Investment Advisor

An innovative platform designed to evaluate companies' Environmental, Social, and Governance (ESG) performance by aggregating data from financial reports, news articles, and social media. Leveraging Yahoo Finance’s sustainability API, this project generates composite ESG scores and provides actionable investment recommendations—perfectly aligned with the hackathon theme: **AI in Finance**.

## Directory Structure

```plaintext
ESG_Investment_Advisor/
├── data/                     
│   └── real_time_esg_data.csv  # Saved ESG data from Alpha Vantage
├── notebooks/                 
│   ├── 1_fetch_esg_data.ipynb
│   └── 2_visualize_esg_data.ipynb
├── api/                       
│   └── app.py                  # ESG API (optional)
├── README.md                   # Project documentation
└── requirements.txt            # Python dependencies

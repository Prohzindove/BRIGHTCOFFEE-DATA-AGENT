# BRIGHTCOFFEE-AI-DATA-AGENT
<p align="center">
  <img src="IMAGE/brightcoffee-ai-agent.jpg" width="350">
</p>

An AI-powered Business Intelligence Agent built using Databricks AI/GenAI to provide business insights from the Brightlearn Coffee dataset. The agent enables business users to ask natural language questions and receive data-driven insights, executive summaries, visual explanations, and actionable recommendations.

## Project Overview

This project demonstrates how Generative AI can be integrated with business analytics to create an intelligent data assistant.

The Brightlearn Coffee AI Agent was designed to:
- Answer business questions using natural language
- Generate meaningful business insights
- Explain visualisations in simple business language
- Recommend actions based on analytical findings
- Compare business performance across different dimensions
- Support executive decision-making

## Features

- 🤖 AI-powered Business Intelligence Agent
- 📊 Natural language querying
- 📈 Revenue and sales analysis
- 🏪 Store performance comparison
- ☕ Product performance analysis
- 📅 Time-based sales analysis
- 📉 Executive summaries
- 💡 Business recommendations
- 📊 KPI reporting
- 📉 Visualisation explanations

## Technologies Used

- Databricks
- Databricks AI Agent
- SQL
- Delta Tables
- Machine Learning
- Business Analytics
- Data Cleaning
- Data Transformation
- Data Visualisation
- Prompt Engineering

## Dataset

The project uses the Brightlearn Coffee Sales Dataset, containing transaction-level sales information including:

- Transaction Details
- Store Information
- Product Information
- Revenue
- Quantity Sold
- Date & Time
- Customer Spend Bucket

The dataset was prepared by:

- Cleaning missing values
- Standardising formats
- Converting data types
- Creating derived columns
- Adding metadata/comments
- Categorising records for analysis

## Data Schema

### Transaction
- Transaction ID
- Transaction Date
- Transaction Quantity

### Store
- Store ID
- Store Location

### Sales
- Clean Unit Price
- Revenue
- Spend Bucket

### Product
- Product ID
- Product Category
- Product Type
- Product Detail

### Time
- Clean Time
- Time Bucket
- Day Type
- Day Name
- Day of Month
- Month Name
- Month Period

## AI Agent Instructions

The AI agent was configured to:

- Respond as a Business Analyst
- Use simple business language
- Base responses strictly on the dataset
- Calculate product performance using Revenue
- Explain every visualisation
- Provide recommendations
- Identify business opportunities
- Compare stores, products, and time periods
- Generate executive summaries
- Never fabricate data

## Example Business Questions

The AI agent can answer questions such as:

- Which store generated the highest revenue?
- What are the top-performing products?
- Which product categories underperform?
- Compare revenue across store locations.
- Which days generate the most sales?
- Which time buckets are busiest?
- What business opportunities exist?
- Show an executive summary of business performance.
- Recommend strategies to improve revenue.

## Business Value

This solution demonstrates how AI can transform raw transactional data into strategic business insights by enabling:
- Faster decision making
- Self-service analytics
- Improved operational efficiency
- Better revenue optimisation
- Enhanced customer understanding
- Executive-level reporting

## Project Workflow

1. Upload dataset into Databricks
2. Create Catalog, Schema and Tables
3. Clean and transform data
4. Configure AI Agent
5. Define business instructions
6. Test with natural language questions
7. Generate insights and recommendations

## Skills Demonstrated

- Business Intelligence
- Data Analytics
- SQL
- Databricks
- Data Cleaning
- Data Transformation
- Prompt Engineering
- AI Agents
- Business Analysis
- Executive Reporting
- Data Storytelling
- Decision Support Systems

### Technical Skills

- SQL
- Python
- Databricks
- Power BI
- Excel
- Machine Learning
- AI Agents
- Data Visualisation
- Business Analytics

## Future Improvements

- Power BI Dashboard Integration
- Streamlit Front-End
- Real-time Data Connection
- Predictive Analytics
- Customer Segmentation
- Sales Forecasting
- Automated KPI Monitoring

## License

This project was developed for educational and portfolio purposes.

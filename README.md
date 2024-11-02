# Unstructured Data Analytics: Competitive Analysis of the Entry-Level Luxury Car Market

## Project Overview
This project was conducted as part of an assignment for JD Power and Associates to perform a competitive analysis of the entry-level luxury car market in the USA. The analysis involved extracting and processing social media conversations from Edmunds.com forums to provide insights and advice for strategic decision-making. 

## Tasks Breakdown

### Task A: Data Extraction and Zipf's Law Test
- **Objective**: Write a scraper in Python to extract around 5,000 posts from the Edmunds.com forum. The posts were analyzed to test their compliance with Zipf's Law and to visualize the most common 100 words.
- **Method**: Data was fetched using a custom-built web scraper, and word frequency distribution was plotted and tested against the theoretical Zipf's Law.
- **Note**: Stopwords were not removed, and no stemming or lemmatization was applied.

### Task B: Brand Identification and Frequency Count
- **Objective**: Identify the top 10 brands discussed in the forum posts by counting word frequencies (excluding stopwords). Replace mentions of car models with their respective brands to simplify the analysis.
- **Method**: Developed a Python script to count word frequencies and map car models to their brands. Each brand was counted once per post, even if mentioned multiple times.

### Task C: Lift Ratio Calculation
- **Objective**: Calculate the lift ratios to measure associations between the top 10 brands.
- **Method**: A Python script was written to compute lift ratios, ensuring that mentions were only counted once per post. Mentions were excluded if separated by more than 5–7 words to maintain relevance.

### Task D: Multi-Dimensional Scaling (MDS) Map
- **Objective**: Create an MDS map to visualize the relationships between the top brands.
- **Method**: Used Python scripts and libraries to generate a 2D MDS map based on the calculated lift ratios, showing the proximity of brands to one another.

### Task E: Insights from Tasks C and D
- **Objective**: Provide insights into the competitive landscape based on the lift ratios and MDS map analysis.
- **Method**: Analyzed the MDS map and lift ratios to draw conclusions about brand associations and competitive positioning.

### Task F: Top Attributes and Brand Association
- **Objective**: Identify the five most frequently mentioned attributes of cars and determine which brands these attributes are most strongly associated with.
- **Method**: Used frequency analysis and attribute mapping to associate key attributes with the top brands.

### Task G: Client Advice from Attribute Analysis
- **Objective**: Provide strategic advice to the client based on the analysis in Task F.
- **Method**: Summarized key findings and recommended strategies based on the association between brands and attributes.

### Task H: Determining the Most Aspirational Brand
- **Objective**: Identify the most aspirational brand based on consumer discussions and provide business implications.
- **Method**: Measured the aspirational nature of brands by analyzing positive indicators related to desire and ownership mentioned in posts. Detailed the analysis and implications for the top aspirational brand.

## Deliverables
- Python scripts for scraping data, analyzing word frequencies, calculating lift ratios, and generating MDS maps.
- CSV file with the extracted data containing post dates and messages.
- Frequency tables and lift ratio tables.
- MDS visualization.
- Summary and strategic advice based on the analysis.
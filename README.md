# New York Times Article Analysis

## Introduction

This project uses the NYT Article Search API to collect article data, including titles and thumbnail images, which are then analyzed using machine learning.

The goal is to examine the distribution of article sentiment (negative, neutral, positive) and to measure the representation of men vs. women in article thumbnail images.
## Setup

### 1. Clone the repository
git clone https://github.com/Darius-Varnelis/nyt_article_analysis.git

### 2. Install dependencies
pip install requests python-dotenv transformers torch Pillow tqdm pandas

### 3. Configure API key
Create a `.env` file in the project root based on `.env.example`:
NYT_API_KEY=your_key_here

You can get a free NYT API key at https://developer.nytimes.com.

### 4. Run the notebook
Open `NYT_article_analysis.ipynb` in Jupyter or Google Colab and run all cells in order.

> Note : The data collection step takes ~2 minutes due to NYT API rate limiting. Additionally, the image captioning step takes ~8 minutes (100 thumbnails). Total runtime is about 10 minutes. 

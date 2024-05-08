# Module 8 Challenge - Mercado Libre Analysis

## Overview

You are a growth analyst at Mercado Libre, the most popular e-commerce site in Latin America with over 200 million users. Your task is to analyze the company's financial and user data to promote growth, specifically by examining if search traffic predictions can guide successful stock trading strategies.

## Getting Started

1. **Repository Setup:**
   - Create a new repository named `prophet-challenge`.
   - Clone this repository to your computer.
   - Add the starter files provided in the challenge to your local Git repository.
   - Push the changes to GitHub or GitLab.

2. **Environment Setup:**
   - Complete the challenge using Google Colab.
   - Ensure you download your notebook file and place it in your repository after completing the challenge.

## Challenge Instructions

### Step 1: Analyze Google Search Traffic

- **Objective:** Identify any unusual patterns in Google search data for Mercado Libre and link these patterns to corporate financial events.
- **Tasks:**
  1. Load the search data into a DataFrame and focus on May 2020, the month MercadoLibre released its quarterly financial results.
  2. Visualize the data to spot unusual patterns.
  3. Calculate and compare the total search traffic for May 2020 against the monthly median.

### Step 2: Mine the Search Traffic Data for Seasonality

- **Objective:** Identify predictable patterns in the hourly search data to optimize marketing efforts.
- **Tasks:**
  1. Group and plot the average hourly search traffic.
  2. Compare search traffic across different days of the week.
  3. Analyze weekly search traffic patterns, especially during the winter holiday period (weeks 40-52).

### Step 3: Relate Search Traffic to Stock Price Patterns

- **Objective:** Explore any correlations between search traffic and stock price movements.
- **Tasks:**
  1. Load and visualize stock price data.
  2. Merge search data with stock price data in a single DataFrame.
  3. Analyze the trends in the data for the first half of 2020.
  4. Introduce new DataFrame columns: Lagged Search Trends, Stock Volatility, and Hourly Stock Return.

### Step 4: Create a Time Series Model with Prophet

- **Objective:** Develop a time series model using Prophet to forecast and analyze search traffic patterns.
- **Tasks:**
  1. Prepare the search data for Prophet.
  2. Estimate the model and visualize the forecast.
  3. Analyze the time series components to determine peak times for search popularity, the busiest day of the week, and the annual low point in search traffic.

## Submission

Submit your completed notebook file by placing it in your repository. Ensure all steps are documented and clearly explained.

## Resources

- Norman, Ryan. "UNC AI Bootcamp." Instructor.
- OpenAI. "ChatGPT-4."
- "Prophet Documentation." Python API, Prophet, [https://facebook.github.io/prophet/docs/quick_start.html#python-api](https://facebook.github.io/prophet/docs/quick_start.html#python-api).

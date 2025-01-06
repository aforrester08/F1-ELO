# F1-ELO

This Python script calculates the Elo ratings of Formula 1 drivers over a specified time span.

## Prerequisites

Ensure you have Python 3.7 or later installed. You can download it from the [official Python website](https://www.python.org/downloads/).

## Installation

1. Clone this repository to your local machine:
   git clone https://github.com/yourusername/F1-ELO.git
   cd F1-ELO
2. Install the required packages:
    pip install -r requirements.txt
3. Run all cells in the Juypter Notebook

## Rate Limiting
The fastf1 library has a rate limit of 60 requests per minute. To avoid hitting this limit, the script processes data for the 2020 to 2024 seasons. You can adjust the years variable in the script to analyze a different time span. Be mindful of the rate limit when changing the period
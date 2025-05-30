# EURO 2024 - Swisslos Betting Odds Analyzer

A web scraping tool that collects and analyzes betting odds from Swisslos for EURO 2024 matches.

![Python Version](https://img.shields.io/badge/python-3.10%2B-blue)


## Features

- Automated odds collection for match outcomes
- Probability calculation from decimal odds
- CSV export with timestamped files
- ChromeDriver version validation

## Installation

### Prerequisites

- Python 3.10+
- Google Chrome ≥ 114

### Setup

```bash
git clone https://github.com/yourusername/euro2024-odds.git
cd euro2024-odds

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

pip install selenium
pip install beautifulsoup4
pip install pandas
```

### download chrome driver

In the repo, there is already a chromedriver for Windows. If you are using another device, check out [google chrome labs](https://googlechromelabs.github.io/chrome-for-testing/) and download the lates version of chromedriver for your device. 


## Stats

See the three most likely results for each game:
[odds.csv](src/odds/odds_11_06_2024.csv)

# Disclaimer

- Important: Web scraping may violate website terms of service
- Use at your own risk - consult legal counsel if unsure

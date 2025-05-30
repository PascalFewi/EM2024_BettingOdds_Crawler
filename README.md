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


## Disclaimer

- Important: Web scraping may violate website terms of service
- Use at your own risk - consult legal counsel if unsure

## Odds 11. June 2024

|FIELD1|Game Title                      |Result|Odds|
|------|--------------------------------|------|----|
|0     |Spanien – Kroatien              |1:0   |5.7 |
|1     |Spanien – Kroatien              |2:0   |6.99|
|13    |Spanien – Kroatien              |1:1   |5.5 |
|29    |Deutschland – Schottland        |1:0   |5.84|
|30    |Deutschland – Schottland        |2:0   |5.11|
|32    |Deutschland – Schottland        |3:0   |6.54|
|58    |Italien – Albanien              |1:0   |4.69|
|59    |Italien – Albanien              |2:0   |4.82|
|61    |Italien – Albanien              |3:0   |7.26|
|99    |Ungarn – Schweiz                |0:0   |7.41|
|100   |Ungarn – Schweiz                |1:1   |5.27|
|103   |Ungarn – Schweiz                |0:1   |5.89|
|132   |Serbien – England               |0:1   |5.76|
|133   |Serbien – England               |0:2   |5.8 |
|134   |Serbien – England               |1:2   |7.15|
|158   |Polen – Niederlande             |1:1   |6.47|
|161   |Polen – Niederlande             |0:1   |5.63|
|162   |Polen – Niederlande             |0:2   |6.19|
|186   |Rumänien – Ukraine              |0:0   |7.43|
|187   |Rumänien – Ukraine              |1:1   |5.47|
|190   |Rumänien – Ukraine              |0:1   |5.51|
|203   |Belgien – Slowakei              |1:0   |6.21|
|204   |Belgien – Slowakei              |2:0   |6.05|
|216   |Belgien – Slowakei              |1:1   |7.16|
|248   |Österreich – Frankreich         |0:1   |6.71|
|249   |Österreich – Frankreich         |0:2   |6.42|
|250   |Österreich – Frankreich         |1:2   |7.11|
|261   |Türkei – Georgien               |1:0   |5.07|
|262   |Türkei – Georgien               |2:0   |6.34|
|274   |Türkei – Georgien               |1:1   |5.8 |
|290   |Portugal – Tschechische Republik|1:0   |5.83|
|291   |Portugal – Tschechische Republik|2:0   |6.03|
|303   |Portugal – Tschechische Republik|1:1   |6.68|
|319   |Kroatien – Albanien             |1:0   |4.75|
|320   |Kroatien – Albanien             |2:0   |5.29|
|332   |Kroatien – Albanien             |1:1   |6.73|
|348   |Deutschland – Ungarn            |1:0   |5.73|
|349   |Deutschland – Ungarn            |2:0   |5.25|
|351   |Deutschland – Ungarn            |3:0   |7.05|
|390   |Schottland – Schweiz            |1:1   |5.51|
|393   |Schottland – Schweiz            |0:1   |6.21|
|395   |Schottland – Schweiz            |1:2   |7.65|
|419   |Slowenien – Serbien             |1:1   |5.48|
|422   |Slowenien – Serbien             |0:1   |6.03|
|423   |Slowenien – Serbien             |0:2   |7.55|
|448   |Dänemark – England              |1:1   |6.06|
|451   |Dänemark – England              |0:1   |5.41|
|452   |Dänemark – England              |0:2   |6.09|
|464   |Spanien – Italien               |1:0   |6.83|
|466   |Spanien – Italien               |2:1   |8.14|
|477   |Spanien – Italien               |1:1   |5.15|
|505   |Slowakei – Ukraine              |0:0   |7.34|
|506   |Slowakei – Ukraine              |1:1   |5.31|
|509   |Slowakei – Ukraine              |0:1   |5.64|
|535   |Polen – Österreich              |1:1   |5.43|
|538   |Polen – Österreich              |0:1   |6.9 |
|540   |Polen – Österreich              |1:2   |7.67|
|564   |Niederlande – Frankreich        |1:1   |5.61|
|567   |Niederlande – Frankreich        |0:1   |6.55|
|569   |Niederlande – Frankreich        |1:2   |7.45|
|593   |Georgien – Tschechische Republik|1:1   |5.67|
|596   |Georgien – Tschechische Republik|0:1   |5.76|
|597   |Georgien – Tschechische Republik|0:2   |6.89|
|622   |Türkei – Portugal               |1:1   |6.68|
|625   |Türkei – Portugal               |0:1   |6.1 |
|626   |Türkei – Portugal               |0:2   |6.41|
|638   |Belgien – Rumänien              |1:0   |5.85|
|639   |Belgien – Rumänien              |2:0   |5.81|
|651   |Belgien – Rumänien              |1:1   |7.07|
|680   |Schweiz – Deutschland           |1:1   |6.28|
|683   |Schweiz – Deutschland           |0:1   |6.39|
|685   |Schweiz – Deutschland           |1:2   |7.15|
|712   |Albanien – Spanien              |0:1   |5.47|
|713   |Albanien – Spanien              |0:2   |5.0 |
|715   |Albanien – Spanien              |0:3   |6.69|
|738   |Kroatien – Italien              |1:1   |5.75|
|741   |Kroatien – Italien              |0:1   |6.09|
|743   |Kroatien – Italien              |1:2   |7.47|
|754   |Schottland – Ungarn             |1:0   |7.78|
|767   |Schottland – Ungarn             |1:1   |5.73|
|770   |Schottland – Ungarn             |0:1   |7.07|
|783   |Niederlande – Österreich        |1:0   |7.56|
|785   |Niederlande – Österreich        |2:1   |7.62|
|796   |Niederlande – Österreich        |1:1   |5.87|
|812   |Dänemark – Serbien              |1:0   |6.98|
|825   |Dänemark – Serbien              |1:1   |5.35|
|828   |Dänemark – Serbien              |0:1   |8.01|
|841   |England – Slowenien             |1:0   |5.74|
|842   |England – Slowenien             |2:0   |5.29|
|844   |England – Slowenien             |3:0   |7.16|
|870   |Slowakei – Rumänien             |1:0   |6.84|
|883   |Slowakei – Rumänien             |1:1   |4.96|
|886   |Slowakei – Rumänien             |0:1   |6.85|
|912   |Ukraine – Belgien               |1:1   |6.06|
|915   |Ukraine – Belgien               |0:1   |7.06|
|917   |Ukraine – Belgien               |1:2   |7.27|
|944   |Georgien – Portugal             |0:1   |6.44|
|945   |Georgien – Portugal             |0:2   |5.32|
|947   |Georgien – Portugal             |0:3   |6.45|
|957   |Frankreich – Polen              |1:0   |6.05|
|958   |Frankreich – Polen              |2:0   |5.56|
|959   |Frankreich – Polen              |2:1   |7.36|
|986   |Tschechische Republik – Türkei  |1:0   |8.34|
|999   |Tschechische Republik – Türkei  |1:1   |5.13|
|1002  |Tschechische Republik – Türkei  |0:1   |7.38|
|1028  |Slowenien – Dänemark            |1:1   |5.67|
|1031  |Slowenien – Dänemark            |0:1   |5.17|
|1032  |Slowenien – Dänemark            |0:2   |6.29|

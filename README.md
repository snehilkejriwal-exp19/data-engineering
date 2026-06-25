# DATA PIPELINE/ENGINEERING

Applied scheduled pipelines and storage through API's on real time stock data

## Notebooks

### data_pipeline_fundamentals.ipynb

| Section | Concept | Method |
|---------|---------|--------|
| F1 |JSON Parsing| Navigating nested dictionary and converting JSON raw response into clean dataframes|
| F2 |Pipeline| Simulating incremental pipeline storage with duplicate prevention logic |

## Limitations

Scheduling logic was tested by manually re-running the pipeline twice rather than true OS-level automation (cron/Task Scheduler), since this requires a persistent local environment outside Colab

**Stack:** Python, pandas, numpy, requests, yfinance
**Data:** IBM, TCS.NS, RELIANCE, INFOSYS

## Author
Snehil Kejriwal — Economics + B.Tech, BITS Pilani Hyderabad
github.com/snehilkejriwal-exp19

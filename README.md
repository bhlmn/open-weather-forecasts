# open-weather-forecasts
Democratizing numerical weather forecast data.

## Setup
1. Create and activate a new anaconda environment
``` bash
conda create --name open-weather-forecasts python=3.8 pandas jupyterlab numpy
conda activate open-weather-forecasts
```
2. [Install Google Cloud SDK](https://cloud.google.com/sdk/docs/quickstart)
3. Setup the SDK
``` bash
gcloud init
```
4. Install the Google Cloud python libraries we'll use
``` bash
pip install google-cloud-bigquery
```
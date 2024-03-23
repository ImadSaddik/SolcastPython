# Solcast Solar Irradiance and Weather Data Access

This repository contains resources and code snippets to facilitate the access of solar irradiance and weather data from the Solcast platform. With Solcast's extensive dataset, users can gather valuable insights for research, analysis, and applications in the renewable energy sector.

## Overview

Accessing solar irradiance and weather data is essential for various purposes such as solar energy forecasting, climate analysis, and environmental studies. Solcast offers a user-friendly platform and an API for retrieving historical and real-time solar data.

This repository provides:

- Python code snippets for accessing data programmatically through the Solcast API.
- Guidelines for setting up the necessary environment and dependencies.
- Demonstrations of data manipulation and analysis using Python libraries.

## Dependencies

To run the Python scripts for accessing Solcast data, ensure you have the following dependencies installed:

- Python (3.x recommended)
- `python-dotenv` package
- `requests` package
- `pandas` package

You can install the dependencies using pip:

```bash
pip install -r requirements.txt
```

## API Key

Make sure to copy the API Key from the Solcast platform and add paste in the `.env` file, like this

```python
SOLCAST_API_KEY=your_api_key
```
## Acknowledgements

We extend our sincere gratitude to the Solcast team for their dedication to advancing renewable energy research and for providing free access to their extensive solar irradiance and weather datasets.

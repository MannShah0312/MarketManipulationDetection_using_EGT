# Market Manipulation Detection using Evolutionary Game Theory (EGT)

This project leverages concepts from Evolutionary Game Theory (EGT) and recommender systems to detect manipulations in commodity markets. The current implementation focuses on the wheat market in Central India.

## Table of Contents

* [Overview](#overview)
* [Methodology](#methodology)
* [Dataset](#dataset)
* [Project Structure](#project-structure)
* [Requirements](#requirements)
* [Usage](#usage)
* [Results](#results)
* [Contributing](#contributing)
* [License](#license)

## Overview

Commodity markets are susceptible to manipulative practices that can distort prices and affect stakeholders. This project aims to identify such manipulations by modeling market behaviors using Evolutionary Game Theory and validating findings through recommender system techniques.

## Methodology

1. **Evolutionary Game Theory (EGT):** Models the strategic interactions among market participants, capturing how strategies evolve over time.
2. **Recommender Systems:** Validates the EGT findings by analyzing patterns and suggesting potential anomalies based on historical data.

## Dataset

The analysis utilizes real-world data from the wheat market in Central India, including:

* `agmarknet.csv`
* `agmarknet2.csv`
* `hoshangabadmarket.csv`
* `selling.csv`
* `sitedata.csv`

These datasets encompass market prices, transaction volumes, and other relevant metrics.

## Project Structure

* `check.py`: Initial data validation and preprocessing scripts.
* `finalmodel.py`: Implements the core EGT model for detecting market manipulations.
* `model2.py`: Alternative modeling approach or supplementary analysis.
* `process_selling.py`: Processes selling data for integration into the main model.

## Requirements

Ensure you have the following installed:

* Python 3.x
* Required Python libraries (listed in `requirements.txt` or as per script imports)

Install dependencies using pip:

```bash
pip install -r requirements.txt
```



## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/MannShah0312/MarketManipulationDetection_using_EGT.git
   cd MarketManipulationDetection_using_EGT
   ```



2. **Run the main model:**

   ```bash
   python finalmodel.py
   ```



3. **Explore alternative analyses:**

   ```bash
   python model2.py
   ```


Ensure all dataset files are in the same directory as the scripts or adjust file paths accordingly.

## Results

The model outputs indicators of potential market manipulations, highlighting anomalies in pricing and transaction patterns. These results can aid stakeholders in making informed decisions and implementing corrective measures.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.
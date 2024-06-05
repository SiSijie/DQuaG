# Automated Data Quality Validation Using Graph Representation Learning

## Overview

This repository contains the implementation of DQuaG (Data Quality Graph), a novel approach for automated data quality validation using graph representation learning. Our method leverages Graph Neural Network (GNN) and Variational Autoencoder (VAE) to detect and infer underlying data quality issues in datasets. This approach is designed to overcome limitations of traditional data quality validation methods which often fail to capture complex interdependencies within the data.

![DQuaG Framework](path/to/framework_image.png)
*Figure 2: Framework of DQuaG approach*

## Installation

To run the code, please follow these steps to set up your environment:

1. Clone the repository
2. Install the required packages


## Experimental Setup

Our experiments were conducted using the following environment:

- **Programming Language**: Python 3.11
- **Deep Learning Framework**: PyTorch 1.12.1
- **Hardware**: NVIDIA A100 GPU

### Datasets

We evaluate our approach using datasets with varied error types and data structures:

- **Datasets with Ground-Truth Errors**:
- *Airbnb Data*: Contains listings for New York City.
- *Chicago Divvy Bicycle Sharing Data*: Includes trip data from the Divvy bike-sharing program in Chicago.

- **Datasets Without Ground-Truth Errors**:
- *New York Taxi Trip Data*: Comprises taxi trip records in New York City.
- *Hotel Booking Data*: Booking information for city and resort hotels.
- *Credit Card Data*: Contains information on credit card applications.

### Usage

To execute the validation process, use the following command:

```bash
python validate_data.py



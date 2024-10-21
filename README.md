# The Watch Pages Partial Dataset

This repository contains an initial dataset extracted from [TheWatchPages.com](https://www.thewatchpages.com/), featuring details about various watch brands, collections, and models. The dataset currently contains **350 records** but is expected to be expanded as more data is crawled and added.

## Dataset Overview

The dataset includes structured information on a limited set of watches from various brands and models, covering core specifications and pricing details. This partial version serves as a starting point for researchers, watch enthusiasts, and developers interested in the watch industry.

### Key Features
- **Brands**: Information on different brands listed on TheWatchPages.com.
- **Models**: Model names, reference numbers, and collection details.
- **Specifications**: Details like case size, material, movement type, water resistance, and more.
- **Pricing**: Estimated prices in USD.

## Data Fields
The dataset currently includes the following fields:
- `Brand Name`
- `Model Name`
- `Reference Number`
- `Case Size (mm)`
- `Case Material`
- `Dial Color`
- `Movement Type` (Automatic, Manual, Quartz)
- `Water Resistance` (meters)
- `Power Reserve` (hours)
- `Strap Material`
- `Price` (USD)

## File Details
- **File Name**: `dataset.csv`
- **Format**: CSV
- **Size**: Contains 350 rows and 12 columns
- **Date of Extraction**: (Include the date, e.g., "October 20, 2024")

## Next Steps for Completing the Dataset

The current dataset is partial, and additional data crawling is needed to make it comprehensive. Future updates will involve:
1. **Further Crawling** using advanced scraping tools (e.g., Scrapy, BeautifulSoup).
2. **Data Cleaning and Validation** to ensure data consistency and accuracy.
3. **Updating the Dataset** in this repository with new records as they are collected.

## Usage
This dataset is provided for free use under the MIT License. It can be used for:
- Preliminary research and analysis of watch trends.
- Testing and development of watch-related applications or tools.
- Building sample models for data analysis.

## Getting Started
1. **Download the dataset**: Clone the repository and download the `dataset.csv`.
   ```bash
   git clone https://github.com/your-username/TheWatchPages-Partial-Dataset.git

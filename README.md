# Airfare Booking System

## Overview
This project aims to predict the optimal time to book flight tickets based on a traveler’s destination and departure date, by analyzing historical pricing data. The optimal booking time is defined as the period when the fare falls below the 25th percentile of historical price distributions for similar routes. This helps travelers identify the lowest possible fare for their desired routes. Flight prices fluctuate due to various factors, making it difficult for travelers to determine the best time to book. By leveraging machine learning techniques, our project helps to provide data-driven insights to optimize travel planning. This can benefit both individual travelers looking for cost savings and businesses managing corporate travel budgets.

### Focus Areas
- Predicting future flight ticket prices based on historical data.
- Identifying trends and patterns that indicate the best time to purchase tickets.
- Analyzing factors such as seasonality and booking windows.

### Exclusions
- Real-time tracking of ticket prices.
- External factors like airline-specific promotional deals, last-minute fare changes, or global events and government regulations.

## Dataset
### Source
We will use the "Flight Prices 2M" dataset for this project, which is available at Flight_Price. This dataset is a randomly sampled subset (2 million rows) of the larger original "Flight Prices" dataset: Flight_Price_2M. The original dataset is a 31.09 GB CSV file recording purchasable flight tickets on Expedia between 2022-04-16 and 2022-10-05.

### Estimated Size
- **Rows**: 2,000,000
- **Columns**: 27
- **File Size**: 744.5 MB

## Installation
## 📂 Downloading the Repository with Git LFS
This repository uses **Git Large File Storage (LFS)** to manage large files such as `flight.csv`. Follow these steps to properly clone the repository and retrieve all LFS files.

### 🛠 Step 1: Install Git LFS
Before cloning, ensure Git LFS is installed on your system:

- **Windows / Mac / Linux**  
```sh 
  git lfs install
```

### 📥 Step 2: Clone the Repository
```sh 
git clone https://github.com/tngjody/bt4221-airfare-booking.git
cd bt4221-airfare-booking
git lfs pull
```

⚠ Important: The git lfs pull command is required to download the actual LFS files (e.g., flight.csv).
If skipped, you will only get small pointer files instead of the real dataset.

### 🔄 Step 3: Already Cloned? Fetch LFS Files
If you have already cloned the repository without LFS and see placeholder pointer files instead of actual data, run:
```sh
git lfs install
git lfs pull
```

### ✅ Step 4: verify LFS Files
To check whether `flight.csv` and other LFS files have been correctly downloaded, run:
```sh
git lfs ls-files
```
If the file appears in the output, it has been successfully retrieved via LFS.





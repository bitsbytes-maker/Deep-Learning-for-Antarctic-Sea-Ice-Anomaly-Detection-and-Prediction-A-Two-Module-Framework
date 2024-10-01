# Sea Ice Anomaly Detection

This repository contains Python scripts and resources for detecting sea ice anomalies using various training, testing, and validation periods. The analysis is structured around different sets of timeframes, enabling a comprehensive evaluation of the model's performance.

## Training, Testing, and Validation Periods

| **Training Period**         | **Testing Period** | **Validation Period** |
|-----------------------------|--------------------|------------------------|
| 2000 - 2004, 2011 - 2022    | 2005 - 2009        | 2010                   |
| 2006 - 2022                 | 2000 - 2004        | 2005                   |
| 2000 - 2010, 2017 - 2022    | 2011 - 2015        | 2016                   |
| 2000 - 2016                 | 2017 - 2021        | 2022                   |

The script `_70_2000_2005.py` specifically focuses on the testing period from 2005, allowing you to evaluate the model's performance against anomalies detected during this timeframe. Each row in the training table corresponds to different Python files that handle the training process and the resultant image processing outputs.

## Usage

To utilize the scripts, clone the repository and run the appropriate Python files corresponding to your chosen training and testing periods. Ensure you have the necessary libraries installed, and refer to the README for specific instructions on setup and execution.


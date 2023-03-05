# time_series_imputation

A common challenge encountered during working with time series is the presence of missing data. To address this issue, imputation is a widely used approach that involves
filling in missing values rather than dropping them. However, the key challenge in imputation is determining the appropriate values to use for filling in the missing data. 

In this project, we propose to assess the effectiveness of applying deep learning-based models in time series imputation compared to statistical methods that do not require prior
training.

# Data

The data is accessible through the link: https://drive.google.com/drive/folders/10OYuhaT3nEaJmoGJLNMzOiSVPCtMJJtW?usp=sharing

!!! The data is a csv file of name 'household_power_consumption.csv' to be placed in the `data` folder before any execution.

# Project Structure

The project is structured as follows:

- `data`: contains the data used in the project and needs to be filled with a csv file from the drive link provided in the report
- `trained_models`: contains the finaled trained models of each structure
- `data_generation`: generates the split of the data into train, validation and test sets
- `data_analysis`: commented notebook with the analysis of the data
- `main`: contains the majority of the code (preprocessing, datasets and dataloaders generation, code for statistical methods, deeep learning based models Pytorch implementation, training and evaluation)
- `TimeGanDataAugmentation`: contains the code for the TimeGAN data augmentation method
- `requirements.txt`: contains the list of packages required to run the code
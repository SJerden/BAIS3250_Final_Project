# BAIS3250_Final_Project
Final project for data wrangling. 
This is for providing info about the project.

Preliminary Dataset: https://www.kaggle.com/datasets/taeefnajib/used-car-price-prediction-dataset/data

Scraped Website:  https://www.cars.com/shopping/results/?stock_type=used&makes%5B%5D=&models%5B%5D=&maximum_distance=250&zip=52242

# Jupyter Files
| File Name | Description |
| ------ | ------ |
| sjerden_projectscrape | Jupyter Notebook used to scrape data from cars.com |
| sjerden_kaggleclean | Jupyter Notebook used to clean Kaggle dataset |
| sjerden_projectCheckIn | Jupyter Notebook used to do preliminary analysis |
| sjerden_combine | Jupyter Notebook used to vertically integrate scraped and kaggle data |

# Data Dictionary (Incomplete)
| Column Name | Type | Description |
| ------ | ------ | ------ |
| brand | object | The brand that makes the vehicle, examples may include Ford, Honda, or Mitsubishi. Sometimes referred to as “Make”. |
| model | object | model	object	The model of the vehicle. The specific name or initials given to the vehicle to differentiate it from others made by the same company. Examples may include Civic, Model Y, or F-150. |
| model_year | int64 | model_year	int64	The year the vehicle was manufactured.  |
| mileage | int32 | mileage	int32	The miles that the vehicle has already been driven.  |
| price | int 32 | The price of the vehicle |


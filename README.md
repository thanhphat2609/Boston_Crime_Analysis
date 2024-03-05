# Boston Crime Analysis using Microsoft Fabric

This is a project that I use Microsoft Fabric (All in one) for ETL the dataset from KaggleApi. After ETL I create Data Warehouse and show the Report of Boston Crime. Furthermore, I will use Machine Learning and Pipeline Machine Learning for predict label of column 'UCR_PART'.

## Installation

Clone the repository:

```
https://github.com/thanhphat2609/Boston_Crime_Analysis.git
cd source
```

## Architecture
Basically, this architecture base on the architecture from my previous work on Hadoop and applied it to Fabric with a more streamlined and powerful structure.
![Fabric_Architect](https://github.com/thanhphat2609/Uber_Analytics/assets/84914537/af1f1c7e-cc73-40bf-b4de-baedc16365b4)

## Data Model
![DataModel](https://github.com/thanhphat2609/Boston_Crime_Analysis/assets/84914537/4127767c-4224-4819-84bc-13709916bebc)

## Data Warehouse in Lakehouse of Microsoft Fabric
![DataWarehousel](https://github.com/thanhphat2609/Boston_Crime_Analysis/assets/84914537/53c538d7-7944-4079-b388-53e513c5b27a)

## Semantic Model
![SemanticModel](https://github.com/thanhphat2609/Boston_Crime_Analysis/assets/84914537/bc8582aa-bfe7-438f-9bde-27c3254adcae)

## Boston Crime Report with Power BI

## Pipeline of Machine Learning

## File Structure

- `boston_crime_etl.ipynb`: File for Extract data from Kaggle by using KaggleApi. After that is Transformation and Load into Data Warehouse.
- `boston_crime_ml.ipynb`: File for machine learning anh using pipeline machine learning in Spark for predict label of column 'UCR_PART'

Feel free to explore and enhance the project as needed!


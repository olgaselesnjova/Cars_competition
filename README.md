# Car price prediction 
Competition on [Kaggle]([url](https://www.kaggle.com/competitions/gsom-23sm1-ml-hometask-1/overview))  
Datset: [100,000 UK Used Car Data set]([url](https://www.kaggle.com/adityadesai13/used-car-dataset-ford-and-mercedes)) 


Dataset description: 
>100K used cars postings from the British used cars site separated into two files: train and test data sets.

`cars.csv` contains instances with the target variable (price) included. You should use these data to train your models and check their quality before making a submission.

`cars_test.csv` contains instances without associated values of the target variable. You should predict prices for every example from this file and upload the results to Kaggle. Correct answers are already stored in the system, and the system will use these answers to evaluate the quality of your solution.

`sample_submission.csv` is an example of how a submission prediction results should look like. You need to replace price estimations in this file with predictions produced by your own model.

Features description:

- **brand** car manufacturer
- **model** car model
- **year** registration year
- **transmission** type of gearbox (Manual, Semi-Auto, Automatic, Other)
- **mileage** distance used, miles
- **fuelType** engine fuel type (Diesel, Petrol, Hybrid, Electric, Other)
- **tax** road tax, £
- **mpg** miles per gallon (how many miles car can cover using 1 gallon of fuel; more miles -- less money spent on fuel)
- **engineSize** engine size (volume) in litres
- **tax(£)** road tax, £
- **price** car price, £

# A Data Analysis on SportsCars and CommonCars 

Created by John Hu, Aidan Han, Kwanchi Loo, and Zack Lu

**Link to dataset: https://www.kaggle.com/datasets/rkiattisak/sports-car-prices-dataset and https://github.com/sassoftware/sas-viya-programming/blob/master/data/cars.csv**

Using the supercar and common car datasets, we analyzed car variables with prices. 

**For the common car dataset**, we cleaned and sorted cars into categories including Sedans, SUVs, Wagons, etc and computed their corresponding average retail price in USD. We found that Common sports cars cost on average the most, at 50+k, and that most common cars cost from 20-30k. Using seaborn python library, we found a proportial relationship between engine size and retail price. We also found that the higher the price, the worse fuel efficency. 

**For the sports (Hyper & Super Cars included) car dataset**, there is no relationship between acceleration 0-60 and price. Brands like W Motors, Bugattis, Koenigseggs, and Paganis cost the most on average. 

**For both models**, we built and trained the first using common car dataset, and the second with sports car dataset to display the price of cars affected by seat capability, by fuel tank capability, and horsepower vs torque. For each graph, the model gave price prediction for each variable combination. Using weights and biases machine learning, we also provided loss graph links below each model. 


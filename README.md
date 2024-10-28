# Final-Project
This project aims to improve the customer experience on a travel booking website by predicting flight delays due to weather. Using historical flight and weather data, the model helps customers anticipate delays, enhancing trip planning and satisfaction.

## Approach
The dataset includes flight details like date, time, airline, origin, destination and weather information such as wind, precipitation, temperature and so on from 2014 to 2018. Key steps:
- Data preprocessing: cleaning, handling missing values, one-hot encoding categorical variables.
- Feature engineering: added indicators for holidays and weather conditions at origin and destination airports.
- Model training: a Logistic Regression model was trained and evaluated using metrics like accuracy, precision, and recall.

## Results and Future Work

While the model reached a high accuracy, it still struggles with recall due to class imbalance. Adding weather data slightly improved predictions, but further tuning or using advanced techniques could enhance performance.

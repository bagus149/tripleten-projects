## Project Description:
There is a used car buying and selling company that is developing an application to attract new buyers. In this application, you can quickly determine the market value of your car. You have access to historical data, vehicle technical specifications, vehicle model versions, and vehicle prices.

The company is interested in:
- Prediction quality
- Prediction speed
- Time required to train the model

# Dataset:
Features:
- _DateCrawled_ — the date when the profile was crawled from the database.
- _VehicleType_ — the type of vehicle body.
- _RegistrationYear_ — the year of vehicle registration.
- _Gearbox_ — the type of transmission.
- _Power_ — the power of the vehicle (in horsepower).
- _Model_ — the model of the vehicle.
- _Mileage_ — the mileage of the vehicle (measured in kilometers based on a specific regional dataset).
- _RegistrationMonth_ — the month of vehicle registration.
- _FuelType_ — the type of fuel.
- _Brand_ — the brand of the vehicle.
- _NotRepaired_ — whether the vehicle has been repaired before.
- _DateCreated_ — the date when the profile was created.
- _NumberOfPictures_ — the number of pictures of the vehicle.
- _PostalCode_ — the postal code of the profile owner (user).
- _LastSeen_ — the date of the last user activity.
  
Target:
- _Price_ — price (in Euro)

# Libraries:
- pandas
- matplotlib
- seaborn
- sklearn
- catboost
- lightgbm
- xgboost

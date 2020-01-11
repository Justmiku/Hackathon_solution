# Hackathon_solution
Solution of hackathon for predicting the cost of used cars on machinehack.com

Data_train.xlsx and Data_test.xlsx contains the original dataset provided by the organisers.
Details of the dataset are listed below.


Size of training set: 6,019 records

Size of test set: 1,234 records

FEATURES:

Name: The brand and model of the car.

Location: The location in which the car is being sold or is available for purchase.

Year: The year or edition of the model.

Kilometers_Driven: The total kilometres driven in the car by the previous owner(s) in KM.

Fuel_Type: The type of fuel used by the car.

Transmission: The type of transmission used by the car.

Owner_Type: Whether the ownership is Firsthand, Second hand or other.

Mileage: The standard mileage offered by the car company in kmpl or km/kg

Engine: The displacement volume of the engine in cc.

Power: The maximum power of the engine in bhp.

Seats: The number of seats in the car.

New_Price: The price of a new car of the same model.

Price: The price of the used car in INR Lakhs.

### Price was our response vector which we need to predict by devloping a machine learning model. 

## The notebook contains a lot of data_preprocessing step ans a very important technique of mean encodeing is also demonstrated inside,
## which proved to be very important in improving the score and acheiving a better rank on leaderboard.

## Finally in last section of the notebook I've used gradient boosting machine and xgboost to predict the cost.
### I acheived a final rank of 24 using this solution among approx 400 participating candidates,it was a great learning experience for me.

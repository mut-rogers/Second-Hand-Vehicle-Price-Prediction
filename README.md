## PROJECT: SECOND-HAND VEHICLE PRICE PREDICTION MODEL 

### 1. Problem Statement 
In the Kenyan Second-hand vehicle market, subjetive pricing is a commong issue. There is no standard approach to pricing second-hand vehicles. 

Hence, prices tend to varry from one deaier to another and the difference may be significant. This calls for a data-driven solution that will provide transparency of prices.


### 2. Project Goal
Build a robust Machine Learning model (Price Prediction Model) that can help both buyers and sellers make informed decisions and reduce market inconsitences.


### 3. Success Metrics
Primary metrics include: MAE, RMSE, R2 Score 

 - Mean Absolute Error (MAE) - Will be used to measure the average magnitude of errors between the predicted price and the actual price. MAE will treat all errors equally, therefore, it may not be sensitive to large errors. A lower MAE will be considered as better.

 - Root Mean Squared Error (RMSE) - Will be used to measure the avarage difference between the predicted prices and the actual prices. RMSE will square the errors, therefore, it will be sensitive to large errors. RMSE will be considered in the place of Mean Squared Error (MSE) as taking the square-root of the squared errors ensure that the metric is in the same units as the dataset. A lower RMSE will be considered as a good performance.

### 4. Data Sources 
Sources of data will include;

 Car Dealer Website: URL - https://www.kaiandkaro.com/vehicles?availability=available&availability=sell_on_behalf&model__make__vehicle_type=Automobile 

    Key features that will be collected include;

        1. Year of Manufactor (YOM) 
        2. Current Location
        3. Availability
        4. Drive 
        5. Mileage 
        6. Engine Size 
        7. Fuel Type 
        8. Horse Power 
        9. Hourse Power 
        10. Transmission 
        11. Torque 
        12. Aspiration 
        13. Acceleration (0-100 Kph) 

    Other key features that will be considered in case available include; 

    Trimming, Sound System, Power Windows, Seat Material, Air Conditioning, Steering Controls, Auto Start and Stop, Cigarette Lighter Port,
    Isofix Child Seat Anchors, FM Radio with BT AUX And USB, Keyless Entry  Push Button Start, Running Costs, and Safety Features.

### 5. Acquisiting Strategy
 - Target: Second Hand car online marketplace.
 - Goal: Acquire a structured dataset for the above described features.
 - Key Fields: See above 
 - Extraction & Methodology: This will be completed in a two-stage process described below;
        - Discovery: Extracting of vehicle URLS
        - Detailing: Visiting each unique vehicle URL to extract key vehicle details.
 - Tools: 
        - Python
        - BeautifulSoup
        - Selenium 
        - Pydantic (for data validation) 
        - SQL Alchemy 



### 5. Preparing Data 
### 6. Selecting and Training the Model
### 7. Evaluating and Fine Tuning
### 8. Deployment and Monitoring
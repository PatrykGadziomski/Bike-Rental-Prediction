# Bike Rental Prediction

The following project at the Stuttgart Media University is a student project to predict the rental of bicycles. To achieve this, basic and advanced methods of data science were used with a focus on regression.<br>

## Content

The project consists of three parts:
1. **Data Exploration**
    - Descriptive Statistics vs. Diagrams
    - Quality Issues
    - Analysis and Comments
2. **Data Preparation and Baseline ML Model**
    - Basline ML Model
    - Preprocessings & Evaluations
    - Final ML Model
3. **ML Models Optimization**
    - Basline ML Model
    - Optimizations
        - Algorithms
        - Hyperparameter Tuning
        - Feature Selection
    - results documentation and visualizations

## Data

To predict the rental of bycycles, we use a structured dataset describing bike sharing data. The method used is regression. The used data consists of 732 rows and 18 columns with 15 features and 3 labels. For our case, the main label to be used is `cnt` (number of bike rentals per day).

| #  | Attribute | Description |
| --- | --- | --- |
| 1  | instant | record index |
| 2  | dteday | date |
| 3  | season | season (1:winter, 2:spring, 3:summer, 4:fall) |
| 4  | yr | year |
| 5  | mnth | month (1 to 12) |
| 6  | holiday | wheter day is holiday or not |
| 7  | weekday | day of the week |
| 8  | workingday | if day is neither weekend nor holidayis 1, otherwise is 0 |
| 9  | weathersit | weather situtation:<br>1: Clear, Few clouds, Party cloudy, Partly cloudy<br>2: Mist + Clouds, Mist + Broken clouds, Mist + Few clouds, Mist<br>3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds<br>4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog|
| 10 | temp | Temperature |
| 11 | atemp | Feeling temperatur |
| 12 | hum | Humidity |
| 13 | windspeed | Wind speed |
| 14 | leaflets | Number of distributed leaflets (for marketing purposes) |
| 15 | price reduction | Day with price reduction (yes = 1, no = 0) |
| 16 | casual | count of casual users |
| 17 | registered | count of registered users |
| 18 | cnt | count of total rental bikes including both casual and registered |



<br>
*For task-specific documentation: See the documentations in each folder.*
# Bike Sharing Demand Prediction

## Project Description
This project aims to predict the total count of bikes rented during each hour using historical data. The dataset contains hourly rental data spanning two years. The training set consists of the first 19 days of each month, while the test set comprises the 20th to the end of the month.

## Data Fields
- **datetime**: hourly date + timestamp
- **season**: 1 = spring, 2 = summer, 3 = fall, 4 = winter
- **holiday**: whether the day is considered a holiday
- **workingday**: whether the day is neither a weekend nor holiday
- **weather**:
  - 1: Clear, Few clouds, Partly cloudy
  - 2: Mist + Cloudy, Mist + Broken clouds
  - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds
  - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- **temp**: temperature in Celsius
- **atemp**: "feels like" temperature in Celsius
- **humidity**: relative humidity
- **windspeed**: wind speed
- **casual**: number of non-registered user rentals initiated
- **registered**: number of registered user rentals initiated
- **count**: number of total rentals

## Project Steps

### 1. Dataset Importing
- Install and configure Kaggle API
- Download the dataset from Kaggle
- Extract the dataset files

### 2. Data Description
- Detailed feature description to understand the data fields

### 3. Importing Necessary Libraries
- Import libraries like `numpy`, `pandas`, `matplotlib`, and `seaborn`

### 4. Data Loading and Preprocessing
- Load the dataset
- Check for and handle null values
- Check for and handle duplicate values
- Handle data types and columns

### 5. Model Training and Evaluation
- Further steps would include data preprocessing, feature engineering, model training, and evaluation.

## Usage
1. **Clone the repository:**

   ```bash
   git clone https://github.com/Garry864/bike-sharing-demand-prediction.git
   ```
2. Ensure you have the necessary libraries installed
3. Run the notebook to reproduce the results




## License
This project is licensed under the MIT License.

---

Please let me know if there are specific sections or additional details you'd like to include!

# House Sales in King County, USA - Data Analysis Project

## Overview
This project focuses on analyzing house sales data in King County, USA. The dataset includes various features such as price, number of bedrooms, bathrooms, square footage, and more. The goal of this project is to perform exploratory data analysis (EDA), data wrangling, and model development to gain insights into the factors influencing house prices in King County.

## Project Structure
The project is structured into several modules, each focusing on a different aspect of the data analysis process:

1. **Importing Data Sets**: Loading the dataset and understanding its structure.
2. **Data Wrangling**: Cleaning and preparing the data for analysis.
3. **Exploratory Data Analysis (EDA)**: Exploring the data to uncover patterns and insights.
4. **Model Development**: Building predictive models to estimate house prices.
5. **Model Evaluation and Refinement**: Evaluating the models and refining them for better performance.

## Dataset
The dataset used in this project is named `House_Sales_in_King_Count_USA-20231003-1696291200.jupyterlite (3) (1).ipynb`. It contains 21 columns with various features related to house sales, such as:
- `price`: The price of the house.
- `bedrooms`: Number of bedrooms.
- `bathrooms`: Number of bathrooms.
- `sqft_living`: Square footage of the living space.
- `sqft_lot`: Square footage of the lot.
- `floors`: Number of floors.
- `waterfront`: Whether the house has a waterfront view.
- `view`: The quality of the view.
- `condition`: The condition of the house.
- `grade`: The overall grade of the house.
- `sqft_above`: Square footage above ground.
- `sqft_basement`: Square footage of the basement.
- `yr_built`: The year the house was built.
- `yr_renovated`: The year the house was renovated.
- `zipcode`: The zipcode of the house.
- `lat`: Latitude of the house.
- `long`: Longitude of the house.
- `sqft_living15`: Average square footage of the living space of the 15 nearest neighbors.
- `sqft_lot15`: Average square footage of the lot of the 15 nearest neighbors.

## Key Steps
1. **Data Import and Initial Exploration**:
   - Load the dataset using pandas.
   - Display the first few rows of the dataset.
   - Check the data types of each column.
   - Generate a statistical summary of the dataset.

2. **Data Wrangling**:
   - Drop unnecessary columns (`id` and `Unnamed: 0`).
   - Handle missing values in the `bedrooms` and `bathrooms` columns by replacing them with the mean values.
   - Perform data cleaning and transformation as needed.

3. **Exploratory Data Analysis (EDA)**:
   - Analyze the distribution of house prices.
   - Explore the relationship between different features and house prices.
   - Visualize data using matplotlib and seaborn to identify trends and patterns.

4. **Model Development**:
   - Split the data into training and testing sets.
   - Build predictive models using linear regression and polynomial regression.
   - Evaluate the models using appropriate metrics.

5. **Model Evaluation and Refinement**:
   - Compare the performance of different models.
   - Refine the models by tuning hyperparameters and selecting the best features.
   - Validate the models using cross-validation techniques.

## Dependencies
The project uses the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage
To run the project, follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Open the Jupyter notebook `House_Sales_in_King_Count_USA-20231003-1696291200.jupyterlite (3) (1).ipynb` and execute the cells to perform the analysis.

## Results
The analysis provides insights into the factors that influence house prices in King County. The predictive models developed can be used to estimate house prices based on various features. The project also includes visualizations that help in understanding the data distribution and relationships between different variables.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments
- The dataset used in this project is publicly available and can be found [here](https://www.kaggle.com/harlfoxem/housesalesprediction).
- Special thanks to the open-source community for providing the tools and libraries used in this project.

## Contact
For any questions or suggestions, please feel free to contact the project maintainer at [your-email@example.com](mailto:your-email@example.com).

# capstone

## By: Andy Asher

## Report
The report for this project can be found at the following: [Overleaf Reports](https://www.overleaf.com/read/vqfygrfdhbwr#e4e223)

## Data
Data was gathered from a mixture of publicly available census data relating to suspected overdose risk factors and private data held by harm reduction activists/advocates relating to the location of fatal overdose incidents. 

Before analyzing, the data was cleaned, processed, and combined here: [Ready Data](https://github.com/andyakiva/capstone/blob/main/ReadyData.csv)

This was done by removing attributes that were irrelevant to this project, summarizing the number of incidents per zip code, and removing zip codes with missing data before combining the data together.

## Virtual Environment Set-Up: Installation Instructions

Before setting up the virtual environment, ensure you have Python and pip installed:

Python: You can download it from python.org.
pip: Typically installed automatically with Python. You can check by running pip --version in your terminal.

Setting Up the Virtual Environment:
Clone the Repo and Navigate to Your Project Directory in VSCode:

Create the Virtual Environment:

python3 -m venv myenv

Activate the Virtual Environment:

myenv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

## Exploratory Data Analysis

This project puts together visualizations for each of the factors and their frequency of ocurrance, maps showcasing the distribution of fatal overdoses by zip code, and a heatmap demonstrating the correlation of each factor to each other.

## ML 

This project develops three predictive data models: linear regression, polynomial regression, MLP Neural Net.

## Results

All four models performed similarly in predicting the number of fatal overdoses per thousand residents of a zip code.
At the more accurate end, each model achieved a MAPE of less than .5 or 50 percent and greater than .3 or 30
percent. This is generally considered a reasonable forecast, and with all actual values being 81 or under (median of
17 and mean of 22.78), small variations constitute a much larger percentage than of most typical data sets.
In general, the neural net performed equivalently to both the linear and polynomial regression models. Upon
repeated trialing, the NN was occasionally able to substantially out perform other models, but it was also much more
prone to wide variation and occasionally performed substantially worse than other models.



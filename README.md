# Python-week-6-Assignment

Assignment: Exploring Python Libraries

### Objectives:

- Gain practical experience with installing and using Python libraries.
- Discover the functionalities offered by different libraries for common tasks.
- Combine library functions to create a mini-program.

### Tasks:

#### Library Installation:

- Use pip to install the following libraries (if not already installed):
- numpy
- pandas
- matplotlib.pyplot (usually imported as plt)

### NumPy Fundamentals:
- Create a NumPy array named temperatures containing 10 random floating-point numbers representing daily temperatures.
- Calculate the average, minimum, and maximum temperatures using appropriate NumPy functions.

### Data Analysis with Pandas:
- Create a Pandas DataFrame named weather_data with columns for date (datetime objects), temperature (from the NumPy array), humidity (integers between 30 and 80), and wind_speed (floats between 0 and 15). You can generate random values for humidity and wind speed.
- Display the first 5 rows of the DataFrame.
- Group the data by month and calculate the average temperature for each month.

### Data Visualization with Matplotlib:

- Create a line plot using plt.plot to visualize the daily temperatures.
- Add labels (x-axis: "Day", y-axis: "Temperature") and a title ("Daily Temperatures").
- Display the plot using plt.show().

### Bonus Challenge: Mini-Weather App
- Enhance the script to allow the user to input a desired month.
- Use conditional statements (e.g., if statements) to display the average temperature for the chosen month, retrieved from the DataFrame.

### Explanation:
- pip is the package installer for Python.expand_more Use pip install <library_name> to install libraries.
- numpy provides powerful array manipulation capabilities.expand_more
- pandas is essential for data analysis tasks like creating DataFrames and manipulating data.expand_more
- matplotlib.pyplot offers various plotting functions for data visualization.

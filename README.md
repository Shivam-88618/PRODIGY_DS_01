This Python program generates a random dataset of 200 samples, containing demographic information (gender and age). It then visualizes the distribution of these demographic variables using bar charts and histograms. The purpose of this script is to demonstrate basic data visualization techniques using Python's pandas, numpy, matplotlib, and seaborn libraries.

Features
Generates a random dataset with gender and age information.
Visualizes the distribution of gender using a bar chart.
Visualizes the distribution of age using a histogram.
Dependencies
To run this program, you'll need the following Python libraries:

pandas
numpy
matplotlib
seaborn

pip install pandas numpy matplotlib seaborn

Usage
Set Up the Environment: Ensure you have Python installed along with the required libraries.

Run the Script: Execute the script to generate the random dataset and visualize it.

python script_name.py

View the Output: The program will display two plots:
A bar chart showing the distribution of gender.
A histogram showing the distribution of age.
How It Works
Dataset Generation:

The dataset consists of 200 samples.
Each sample contains a randomly selected gender ('Male', 'Female', 'Other').
The age is randomly generated, ranging from 18 to 70.
Data Visualization:

Gender Distribution: A bar chart is created to show how many samples fall into each gender category.
Age Distribution: A histogram is used to display the frequency of different age groups within the dataset.
Customization
Number of Samples: You can change the n_samples variable to generate more or fewer samples.
Gender Distribution: The probability distribution for genders can be adjusted using the p parameter in the np.random.choice function.
Age Range: You can change the range of ages by modifying the parameters of the np.random.randint function.
Example Output
Gender Distribution
A bar chart will be displayed showing the count of each gender in the generated dataset.
Age Distribution
A histogram will be displayed showing the frequency distribution of ages within the dataset.

Author
This script was created as a basic example of data visualization techniques in Python.

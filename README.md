# FIFA-21-Players-Data-Analysis-and-Visualization
Welcome to this data analysis and visualization project! In this project, we will be exploring the 'FIFA 21 Players' dataset which comprises a rich variety of information about soccer players from around the world. 

Here are your tasks outlined in detail:

Data Cleaning: The initial dataset contains some unnecessary and redundant information. The first task is to clean and prepare it for analysis. In doing so:
- Remove the 'Unnamed: 0' column from the dataset.

- Removing the Newline Characters.

- Look for columns which contain star ('★') characters. Remove these characters from all such columns.

- Fill in the missing values using an appropriate method.

- In the 'Value', 'Wage', and 'Release Clause' columns, remove the '€', 'K', and 'M' characters and convert the currency value to 'int'. For eg, "M" in value column is Million, so multiply the row values by 1,000,000, etc.

Data Visualization: After the data has been cleaned and prepared, use appropriate data visualization methods to represent the data as follows:
- Create a Pie Chart to display the preferred foot ('Left' or 'Right') among the FIFA 21 players.
- Use a Bar Plot to represent the top 3 FIFA 21 players.
- Visualize the best FIFA teams from 100 players based on the 'OVA' score using a Bar Plot.
- Use a Bar Plot to display the top 10 most valuable FIFA teams.
- Create a Scatter Plot to show players who are highly valuable but still underpaid

# FIFA-21-Player-Modelling
In this Machine Learning Project, we will create our own supervised Machine Learning (ML) model. We will use the full FIFA21 Dataset and we will identify players that are above average.

We will use the column "Overall" with a treshold of 75 to define players that are 'Valuable'. This will become our target output which we need for a supervised ML model. Because we use the "Overall" as our target output, we cannot use "Overall" in our features.

This project will provide a comprehensive overview of your abilities in machine learning, from understanding the problem, choosing the right model, training, and optimizing it.

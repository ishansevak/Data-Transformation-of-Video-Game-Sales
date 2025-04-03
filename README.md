# Data-Transformation-of-Video-Game-Sales
We will be using python and sql to get the answer for Video game sales data given in the dataset
## Getting Started
- We Got the dataset of Video game sales over the years
- Load the data in Sql
- Set up python for the code
## Running the tests
1. Setting Up the Environment
- Installed and imported the necessary Python libraries (pandas, pymysql, sqlalchemy)
- Established a Python and MySQL server connection by setting up a database engine.
- Ensured that the dataset containing video game sales was correctly structured and accessible.
2. Extracting the Dataset
- The dataset was queried from MySQL and loaded into a dataframe for analysis.
- This step helped us understand the structure of the dataset, including column names and data types.
3. Analyzing Global Sales Before and After 2005
- Used SQL’s GROUP BY and AVG() functions to calculate the average global sales for games released before and after 2005.
- Grouped the sales data into two categories: Pre-2005 and Post-2005.
- This approach allowed us to efficiently compute and compare the sales trends over time.
4. Creating the Pre/Post-2005 Column
- We created a new column in the dataset that labeled records as "pre-2005" or "post-2005".
- Instead of manually adding a column and iterating over rows, we used SQL’s CASE statement to categorize the games in a single step.
## Deployment
- Use Mysql Workbench with dataset already uploaded.
- Connect any Python software to sql engine and get the dataset
- Ready to deploy the codes.
## Authors
Ishan Sevak
## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
## Acknowledgments
- Prof. Omar al-trad
- My teammates

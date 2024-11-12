# PostgreSQL Olympic Medal Analysis

This project demonstrates the use of PostgreSQL to analyze the medal statistics of various countries in the Summer Olympics.

## Project Overview

The main objective of this project is to retrieve and analyze the summary statistics of medal counts for China, South Korea, and Japan in the Summer Olympics since the year 2000. The analysis focuses on the following key aspects:

1. **Total Gold Medals by Year**: Retrieve the total number of gold medals won by each country in each year.
2. **Maximum Medals by Country**: Determine the maximum number of medals (across all medal types) won by each country.

## SQL Query Breakdown

The SQL query provided in this project performs the following steps:

1. Alias the "Summer_Medals" table as "Country_Medals".
2. Select the Year, Country, and a COUNT of the medals as "Medals".
3. Filter the data to only include countries in the set ('CHN', 'KOR', 'JPN').
4. Further filter the data to only include 'Gold' medals where the Year is greater than or equal to 2000.
5. Group the results by Year and Country.
6. Select the Country, Year, and Medals columns.
7. Use the MAX() function to find the maximum number of medals for each country, partitioned by the Year.

## Usage

To use this project, you will need access to a PostgreSQL database with the "Summer_Medals" table. Update the SQL query in the provided file with the appropriate table and column names for your data.

## Contributing

If you have any suggestions or improvements for this project, feel free to submit a pull request. We welcome contributions to enhance the analysis and the accompanying documentation.

## License

This project is licensed under the [MIT License](LICENSE).

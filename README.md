# Data1202
An exemplary repository for all the files that we have done in Data 1202.

## Project Description
This project explores Walmart's retail sales data to uncover trends and insights. The data is stored in a MySQL database and analyzed using Python libraries like Pandas and Matplotlib. Through data extraction, transformation, and visualization, we aim to understand key sales metrics and patterns.

## Getting Started
These instructions will help to set up the project on any local machine for development and testing.
 
### Prerequisites
You need to install the following dependencies:
```sh
pip install pymysql
pip install pandas
pip install sqlalchemy
pip install matplotlib
```
 
### Installing
Follow these steps to set up the project:
1. Clone the repository:
   ```sh
   git clone https://github.com/your/project.git
   ```
2. Navigate to the project directory:
   ```sh
   cd project_directory
   ```
3. Install required Python packages:
   ```sh
   pip install -r requirements.txt
   ```
4. Set up MySQL database connection using SQLAlchemy and PyMySQL.
5. Load the Walmart dataset (`WalmartRetailSalesF.csv`) into MySQL.
 
## Running the Tests
### End-to-End Tests
These tests ensure data is properly loaded and analyzed:
```sql
SELECT * FROM mytable.ap;
```
 
### Coding Style Tests
To maintain code quality, run:
```sh
pylint your_script.py
```
 
## Deployment
To deploy this project on a live system:
- Ensure MySQL database is running.
- Deploy the Python script for automated data processing.
- Use Matplotlib to generate visual reports.
 
## Built With
- **Pandas** - Data manipulation
- **SQLAlchemy** - Database connection
- **Matplotlib** - Data visualization
- **PyMySQL** - MySQL connector
 
## Authors
- **Debopriya Datta* - Initial work
 
## License
This project is licensed under the MIT License - see the `LICENSE.md` file for details.
 
## Acknowledgments
- Inspired by Walmart sales data analysis.
- Thanks to open-source contributors for maintaining essential Python libraries.

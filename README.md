# ETL Pipeline Projects

This repository contains the code and project files for the Data Engineering specialization's Peer Graded assignment. The project focuses on building an ETL (Extract, Transform, Load) pipeline using Python to process data from various sources.

## Overview

The ETL pipeline follows the following steps:

1. **Extract**: Data is extracted from multiple sources, including CSV files, JSON files, and XML files. The `extract()` function is responsible for extracting data from these sources and storing it in a pandas DataFrame.

2. **Transform**: The extracted data is then transformed using the `transform()` function. This function performs operations such as converting currencies, rounding values, and renaming columns. The transformation process ensures that the data is in the desired format for further processing.

3. **Load**: The transformed data is ready to be loaded into a database or used for analysis. The specific loading mechanism depends on the requirements of the project.


## Repository Structure

The repository is organized as follows:

- `API_Engineer_Peer_Review_Assignment_Extract.ipynb`: This Jupyter Notebook file contains the code for the `extract()` function. The function is responsible for extracting data from various sources and returning a pandas DataFrame.

- `ExtractTransformLoad_V2.ipynb`: This Jupyter Notebook file contains the code for the `extract()`, `transform()` and `load()` function. The function applies ETL to the data.

- `Webscraping_Engineer_Peer_Review_Assignment.ipynb`: This Jupyter Notebook file contains the code for the `extract()` function. The function is responsible for extracting data from various websites by using `Webscraping` and returning a pandas DataFrame.

## Usage

To use the code in this repository, follow these steps:

1. Clone or download the repository to your local machine.

2. Open the Jupyter Notebook files (`API_Engineer_Peer_Review_Assignment_Extract.ipynb`, `ExtractTransformLoad_V2.ipynb`, `Webscraping_Engineer_Peer_Review_Assignment.ipynb`) in a Jupyter Notebook environment.

3. Review the code and ensure that all necessary dependencies are installed. Install any missing dependencies using the appropriate package manager (e.g., pip).

4. Modify the code as needed to fit your specific requirements or project.

5. Execute the code cells to run the functions and perform the data extraction, transformation, and loading steps.

## Dependencies

The code in this repository may require the installation of the following dependencies:

- pandas: Used for data manipulation and DataFrame operations.
- numpy: Used for numerical computations and array operations.
- requests: Used for making HTTP requests to retrieve data from APIs.
- json: Used for working with JSON data.
- xml.etree.ElementTree: Used for parsing and processing XML data.

Ensure that these dependencies are installed in your Python environment before running the code.

## Credits

This project is part of the Data Engineering specialization's Peer Graded assignment. It was created by **Abdul Hanan Nawaz** for educational purposes.

For more information, please visit:
- Website: [www.hanannawaz.com](https://www.hanannawaz.com)
- Email: [hanannawaz0@gmail.com](mailto:hanannawaz0@gmail.com)
- GitHub: [github.com/Hanan-Nawaz](https://github.com/Hanan-Nawaz)
- LinkedIn: [linkedin.com/in/abdulhanan0](https://linkedin.com/in/abdulhanan0)

## License

This repository is licensed under the [MIT License](LICENSE). Feel free to use the code and adapt it to your needs.

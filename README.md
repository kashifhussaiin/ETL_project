# ETL Project

This project demonstrates an ETL (Extract, Transform, Load) process using Python and PostgreSQL. The project includes a dataset, a Jupyter notebook with the ETL script, and a requirements file for dependencies.

## Project Structure

```
ETL_project/
├── data/
│   └── dataset.csv          # The dataset used in the ETL process
├── notebook/
│   └── ETL.ipynb            # Jupyter notebook with the ETL script
└── requirements.txt         # Dependencies required for the project
```

## Dataset

- **Path**: `data/dataset.csv`
- **Description**: The Credit Card Eligibility Dataset: Determining Factors is a comprehensive collection of variables aimed at understanding the factors that influence an individual's eligibility for a credit card. This dataset encompasses a wide range of demographic, financial, and personal attributes that are commonly considered by financial institutions when assessing an individual's suitability for credit.

Each row in the dataset represents a unique individual, identified by a unique ID, with associated attributes ranging from basic demographic information such as gender and age, to financial indicators like total income and employment status. Additionally, the dataset includes variables related to familial status, housing, education, and occupation, providing a holistic view of the individual's background and circumstances.

## Jupyter Notebook

- **Path**: `notebook/ETL.ipynb`
- **Description**: The Jupyter notebook contains the entire ETL script. This notebook demonstrates how data is extracted, transformed, and loaded into a PostgreSQL database.

## Requirements

- **Path**: `requirements.txt`
- **Description**: This file contains all the Python dependencies required to run the ETL script. You can install the dependencies using the following command:

  ```sh
  pip install -r requirements.txt
  ```

## Getting Started

### Prerequisites

- Python 3.x
- PostgreSQL
- Jupyter Notebook

### Setup

1. **Clone the repository**:

   ```sh
   git clone https://github.com/kashifhussaiin/ETL_project.git
   cd ETL_project
   ```

2. **Install the dependencies**:

   ```sh
   pip install -r requirements.txt
   ```

3. **Set up PostgreSQL**:

   - Ensure PostgreSQL is installed and running.
   - Create a new database:

     ```sh
     psql -U postgres -c "CREATE DATABASE test;"
     ```

4. **Configure the database connection**:

   - Update the database configuration in the `ETL.ipynb` notebook with your PostgreSQL credentials.

### Running the ETL Process

1. **Open the Jupyter notebook**:

   ```sh
   jupyter notebook notebook/ETL.ipynb
   ```

2. **Run the notebook**:

   - Follow the instructions in the notebook to run each cell. The notebook will guide you through the ETL process, from extracting data from the CSV file to loading it into the PostgreSQL database.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to reach out:

- GitHub: [kashifhussaiin](https://github.com/kashifhussaiin)
- Email: kashifhussain.fj@gmail.com

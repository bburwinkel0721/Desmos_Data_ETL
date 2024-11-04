# Desmos Assessment CSV ETL

This Jupyter notebook is designed to transform CSV files exported from Desmos assessments into a cleaner format, making it easier for further analysis and processing in various spreadsheet software.

## Features

- **CSV Transformation**: Effectively transforms the original CSV file to remove unnecessary data and streamline the content for better usability.

- **Clean Output**: Outputs a new cleaned CSV file that can be easily imported into any spreadsheet software for additional processing and analysis.

- **Compatibility**: The cleaned CSV file is compatible with a variety of software, ensuring seamless integration into your data workflows.

This notebook provides a straightforward solution for refining Desmos assessment data, allowing you to focus on analysis without the clutter of irrelevant information.

## Run Instructions

### Prerequisites

1. **Install Python and Jupyter Notebook**  
   Ensure you have Python (version 3.8 or higher is recommended) and Jupyter Notebook installed. To install them, open your terminal and run:
   ```bash
   pip install jupyter
2. **Install Required Libraries**
   This notebook uses the pandas, numpy, and glob libraries. If these libraries are not already installed, run:
   ```bash
   pip install pandas numpy glob

### Setup Instructions
1. **Download the Project Repository**
   Go to your GitHub repository link and download or clone the project files to your local machine.

2. **Locate the resource Folder**
   Inside the project directory, there’s a folder named resource. This is where you’ll place the assessment data file downloaded from Desmos.

### Running the Notebook
1. **Download CSV from Desmos**
   Download the CSV file containing your assessment data from Desmos.

2. **Place CSV in resource Folder**
   Move or copy the CSV file into the resource folder in the project directory. The notebook will access files from this location.

3. **Launch Jupyter Notebook**
   Open a terminal in your project directory and start Jupyter Notebook by running:

   ```bash
   jupyter notebook

4. **Open the Notebook File**
   In Jupyter’s file browser, open the notebook file (e.g., ETL.ipynb).

5. **Run the Notebook**
   Run all cells in the notebook by selecting Cell > Run All or by running each cell individually.

### Output
After the notebook completes running, it will save a cleaned version of your original CSV file in the resource folder. This cleaned file will be ready to import into any spreadsheet software for further processing.
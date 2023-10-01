# Structures_part_II (Python)
# Astronaut Candidate Selection Program

Overview
This program is designed to assist in the selection of the best candidates for an astronaut program. It utilizes a DataFrame and the pandas library to analyze candidate data. 
The program calculates the Body Mass Index (BMI), the average of their evaluations, and generates a file containing the candidates who meet specific requirements. 
The criteria for selection are a BMI between 18.5 and 24.9 and an average evaluation score greater than or equal to 87. Various methods, including filtering and calculation of averages, are used within the DataFrame to identify suitable candidates.

Requirements
To run this program, you'll need the following dependencies:

Python 3.x
pandas library (install using pip install pandas)
Usage
Clone this repository to your local machine.

git clone https://github.com/pvaldessancy/astronaut_selection.git
Navigate to the project directory.

cd astronaut_selection
Run the program.

python astronaut_selection.py
The program will load the candidate data from a DataFrame, calculate BMI, evaluate averages, and generate a file with the selected candidates.

Data
The candidate data is in a file resumen_resultados_astronautas.csv. 

Output
The program will generate a file, astronautas_calificados.csv, containing the list of candidates who meet the specified criteria. This file will include candidate information such as name, BMI, and evaluation average.

Configuration
You can adjust the selection criteria and data source within the astronaut_selection.py script. Feel free to modify the BMI thresholds, evaluation score threshold, and data loading process to suit your specific requirements.

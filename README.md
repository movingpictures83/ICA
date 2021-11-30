# ICA
# Language: R
# Input: TXT (key, value pairs)
# Output: PREFIX
# Tested with: PluMA 1.1, R 4.0.0
# Dependency: ica_1.0.2

Independent Component Analysis (Hyvarinen and Oja, 2000)

The plugin accepts as input a TXT file with keyword, value pairs:
csvfile: Dataset
features: List of features (line by line)
categories: Sample categories (line by line)
variables: Number of variables to count
iterations: Number of iterations
tolerance: Tolerance level

Data will be output to a CSV file, with each sample and its x-y coordinates.
A plot will also be produced in a PDF file using the PREFIX



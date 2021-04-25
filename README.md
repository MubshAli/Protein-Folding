# PROTEIN PREDICTION

The goal was to predict the class of ~380 observations (proteins) in the test file. The data were messy, and had missing values. It was also not obvious how to include information from the additional file Protein_interactions.csv, into the training data.

## DATA PREPROCESSING

### INCOMPLETE RECORDS

We found incomplete records for training and testing data.

**Training data -> 5.21%**
**Testing data -> 19.37%**

Incomplete variables were also present.

- Chromosome
- Essential

### FEATURE ENGINEERING

- Sum of binary variables
  - Summarize the 442 binary variables by sum where True -> 1



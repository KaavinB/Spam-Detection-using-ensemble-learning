# Spam Classification Project

This repository contains code for a spam classification analysis using R. The provided code performs tasks such as data preprocessing, text cleaning, building a document-term matrix, dimensionality reduction, model training (SVM & Naive Bayes), ensemble prediction, and evaluation.

## Prerequisites

1. **RStudio Software**
   - Ensure you have RStudio installed and operational on your system.

2. **Package Installation**
   - Verify that the necessary R packages are available. You can install them using the `install.packages()` function within RStudio.
   - The required packages for this code include:
     - `tm`
     - `caret`
     - `wordcloud`
     - `SnowballC`
     - `ggplot2`
     - `RColorBrewer`
     - `e1071`

## Instructions for Executing the Code in RStudio

1. **Code Access**
   - Obtain the code snippet from this repository. The code file is named `Code.R`.

2. **RStudio Interface**
   - Open RStudio and navigate to the Editor pane.

3. **Code Input**
   - Paste the code from `Code.R` into the active window within the Editor pane.

4. **Line-by-Line Execution (Optional)**
   - For a more controlled execution process, you may choose to execute the code line by line.
   - Place your cursor at the beginning of the first line and press `Ctrl + Enter` (or `Cmd + Return` on Mac) to execute that specific line.
   - Repeat this process for each subsequent line of code.

## Data Requirements

- The code assumes the presence of a CSV file named `spam.csv` within your working directory.
- Ensure this file exists and contains the relevant data for spam classification.

## Project Structure

- `Code.R`: The main code file for executing the spam classification analysis.
- `spam.csv`: The dataset used for training and evaluating the models.
- `Instructions for Executing the Provided Code in RStudio.pdf`: Detailed instructions on how to execute the code in RStudio.

## Analysis Workflow

The code performs the following steps:
1. **Data Preprocessing**: Cleaning and preparing the data.
2. **Text Cleaning**: Removing unnecessary characters and formatting the text.
3. **Building a Document-Term Matrix**: Converting the text data into a matrix of term frequencies.
4. **Dimensionality Reduction**: Reducing the number of features for better model performance.
5. **Model Training**:
   - Support Vector Machine (SVM)
   - Naive Bayes
6. **Ensemble Prediction**: Combining the predictions from both models.
7. **Evaluation**: Assessing the model performance using accuracy and confusion matrix.

## Output

The output of the code provides insights into each of the individual steps mentioned above. The results include visualizations, model performance metrics, and detailed evaluations of the classification models.

## Contact

For any questions or issues, please contact kaavinbala2003@gmail.com.

---

Happy coding!


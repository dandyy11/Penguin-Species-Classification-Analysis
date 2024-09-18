# Penguin-Species-Classification-Analysis
Comprehensive analysis of the Palmer Penguins dataset using k-NN, classification trees, and random forests for species classification. Includes exploratory data analysis, model evaluation, and comparison of methods based on accuracy, misclassification rates, and Adjusted Rand Index (ARI).

### Dataset
Palmer Penguins Dataset: A dataset consisting of morphological measurements of penguins belonging to three species: Adelie, Chinstrap, and Gentoo. The features include bill length, bill depth, flipper length, and body mass.

### Objectives
1. **Exploratory Data Analysis (EDA):** Explore the dataset to understand the distributions, relationships, and differences between penguin species.
2. **Model Building:** Apply three classification methods—k-NN, Classification Trees, and Random Forests—to classify penguins based on their morphological measurements.
3. **Model Evaluation:** Evaluate the performance of each classification model using accuracy, misclassification rate, and Adjusted Rand Index (ARI).
4. **Method Comparison:** Compare the performance of the three classification methods to identify the most effective model for species classification.

### Repository Structure
- `Penguin_Classification_Analysis.Rmd` - R Markdown file containing the full analysis, including EDA, model building, and evaluation.
- `Detailed_Report.pdf` - PDF file providing a comprehensive report of the analysis and results.

### Findings
1. **k-Nearest Neighbors (k-NN):** Achieved an accuracy of 80.2% with a misclassification rate of 19.8%. Showed difficulties in distinguishing the Chinstrap species from others, indicated by a moderate ARI of 0.531.
2. **Classification Trees:** Improved performance with an accuracy of 95.05% and a misclassification rate of 4.95%. The classification tree effectively used features like flipper length and bill length, achieving a higher ARI of 0.883.
3. **Random Forests:** Outperformed other methods with an accuracy of 99.01% and a misclassification rate of 0.99%. Exhibited near-perfect classification capabilities, with a high ARI of 0.972, indicating strong agreement with the true labels.

### Conclusion
The analysis demonstrates that the Random Forest model is the most effective for classifying penguin species, with the highest accuracy and ARI among the methods tested. While the classification tree offers valuable insights into decision-making, the k-NN model, despite being less accurate, is useful for its simplicity and interpretability.


### How to Use
To reproduce the analyses, clone this repository and open the R Markdown files (`.Rmd`). You can knit these files in RStudio to generate the HTML or Markdown outputs.
```bash
# Clone the repository
https://github.com/dandyy11/Penguin-Species-Classification-Analysis.git

### Contact
For questions or suggestions, please contact Salman Imtiaz at salman.imtiaz414@gmail.com

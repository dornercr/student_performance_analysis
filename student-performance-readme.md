# Student Performance Analysis

## Overview
This project analyzes the Student Performance Dataset to predict academic success and identify key factors influencing student performance. Using logistic regression, we explore various features and their impact on a student's likelihood of passing.

## Dataset
The dataset used is the Student Performance Dataset, which includes various academic, social, and demographic factors of secondary school students. It's available [here](https://archive.ics.uci.edu/ml/datasets/Student+Performance).

## Key Files
- `student_performance_analysis.ipynb`: Jupyter notebook containing the full analysis
- `student-mat.csv`: The dataset used (Mathematics course)

## Requirements
- Python 3.7+
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

To install required libraries:
```
pip install -r requirements.txt
```

## Key Findings
Our analysis yielded some interesting and counterintuitive results:

1. The model achieved 72% overall accuracy.
2. Stronger predictors of passing:
   - Desire for higher education
   - Being male
   - Having paid extra classes
3. Negative associations (surprisingly):
   - Having a mother who is a teacher
   - Receiving family educational support
   - Receiving extra educational support from school
4. Past failures were a strong negative predictor of future performance.

## Model Performance
- Accuracy: 72%
- Recall for passing students: 87%
- Recall for non-passing students: 44%

## Visualizations
The repository includes two key visualizations:
1. Feature Importance Plot
2. Confusion Matrix

## Future Work
- Investigate the unexpected negative correlations with educational support.
- Explore non-linear models to capture complex relationships.
- Collect more data on non-passing students to balance the dataset.
- Conduct further analysis on gender-related factors influencing academic performance.

## Contributing
We welcome contributions and suggestions! Please open an issue or submit a pull request if you have ideas for improvements or additional analyses.

## License
This project is open source and available under the [MIT License](LICENSE).

## Contact
Name: Charles Dorner - Email: Charles R. Dorner III - LinkedIn: https://www.linkedin.com/in/charles-dorner-01873450/

Feel free to reach out with any questions or comments about this analysis!

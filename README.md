# Sales Prediction Analysis

This repository contains an analysis of a dataset that provides information about the advertising expenditures of a company on various platforms (TV, Radio, Newspapers) and the corresponding sales of a product. The analysis focuses on understanding the relationship between advertising expenditures and sales, as well as predicting sales using linear regression models.

## Dataset Description

### Attributes
- **TV:** Amount of money spent on advertising the product on television.
- **Radio:** Advertising expenditure on radio.
- **Newspaper:** Advertising cost spent on newspaper advertising.
- **Sales:** Number of units sold corresponding to the advertising expenditures on TV, Radio, and Newspapers.

## Analysis

The analysis is performed using a Jupyter notebook and covers the following aspects:

1. **Descriptive Statistics**
   - Calculating the average amount spent on TV advertising.

2. **Correlation Analysis**
   - Analyzing the correlation between radio advertising expenditure and product sales.

3. **Impact Analysis**
   - Determining which advertising medium has the highest impact on sales based on the dataset.

4. **Linear Regression**
   - Plotting a linear regression line that includes all variables (TV, Radio, Newspaper) to predict sales.
   - Visualizing the model's predictions against the actual sales values.

5. **Sales Prediction**
   - Predicting sales for a new set of advertising expenditures: $200 on TV, $40 on Radio, and $50 on Newspaper.

6. **Normalization**
   - Evaluating the performance of the linear regression model when the dataset is normalized.

7. **Subset Analysis**
   - Assessing the impact on sales prediction when only radio and newspaper advertising expenditures are used as predictors.

## Files

- `advertising_sales_data.csv`: The dataset in CSV format.
- `Sales Prediction Dataset.pdf`: PDF file with a detailed description of the dataset.
- `Sales_Prediction.ipynb`: Jupyter notebook containing the analysis.
- `Sales Prediction Analysis.pptx`: A PowerPoint presentation summarizing the insights.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) for providing the dataset.

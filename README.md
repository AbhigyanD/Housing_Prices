# Toronto Housing Price Estimator Project

This repository contains the work for our group project analyzing rental prices in Toronto using R. Our primary objective is to identify and interpret the significant property characteristics that influence rental prices. The analysis is conducted using a Multiple Linear Regression (MLR) framework and includes thorough validation of model assumptions, transformations, and statistical interpretations.

---

## Project Overview

Toronto's rental market is a challenging landscape due to soaring rents and low vacancy rates. This project investigates how factors such as the number of bedrooms, bathrooms, square footage, property type, and furnishing status affect rental prices. By understanding these determinants, we aim to provide insights that can inform policy decisions and market practices for a more equitable rental market.

### Key Objectives:
- Develop an Ordinary Least Squares (OLS) model to identify major drivers of rent.
- Validate MLR and linear regression assumptions.
- Use statistical tools like AIC, BIC, and R² to optimize model selection.
- Highlight limitations and areas for improvement in the model.

---

## File Descriptions

- **`introduction.md`**: Discusses the significance of the study and its alignment with prior research, including references to studies on rent control and hedonic pricing models.

- **`methods.Rmd`**: Contains the detailed methodology for assumption validation, transformations, and model selection using the all subsets regression method. Includes diagrams and plots illustrating the process.

- **`results.Rmd`**: Summarizes the findings, including transformed models, statistical tests, and residual analyses. Contains visualizations such as response vs. fitted graphs, Normal Q-Q plots, and VIF tables.

- **`final_model.R`**: Script for fitting the final selected model with the highest adjusted R² and lowest AIC/BIC values. Also includes diagnostic checks and partial F-tests for categorical predictors.

- **`poster.pdf`**: The visual representation of the project, summarizing objectives, methodology, findings, and conclusions.

- **`ethics.md`**: Discusses the ethical considerations in model selection and the rationale for choosing the all subsets regression method over automated alternatives like stepwise regression.

- **`bibliography.md`**: Lists academic references and studies cited in the project, including seminal works on rent control and determinants of house prices.

---

## Contributions

- **Dai**: R-code, Methods, Results, Ethics, Introduction Editing.
- **Abhigyan**: R-code, Introduction, Conclusion.
- **Uma**: Poster and clarity edits to ensure consistency between the report and the visual representation.

---

## Key Findings

- **Predictors**: Rental price is significantly influenced by square footage, number of bathrooms, bedrooms, property type, and furnishing status.
- **Transformations**: Log transformations improved normality and variance assumptions, though some deviations persisted.
- **Limitations**: Residual analysis highlighted unresolved assumption violations and multicollinearity among predictors.

---

## Acknowledgments

We extend our gratitude to previous studies and authors whose works have guided our analysis. This project was a collaborative effort, combining statistical analysis, data visualization, and writing skills to produce a comprehensive study on Toronto’s housing market.

---

For any questions or contributions, please contact any of the group members via this repository.

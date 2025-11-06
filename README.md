# Practical Machine Learning - Course Project

## Predicting the Quality of Weight Lifting Execution

### Overview
This project uses machine learning to predict how well people perform weight lifting exercises based on accelerometer data. The goal is to classify exercise execution into 5 categories:
- **Class A**: Correct execution
- **Classes B-E**: Common mistakes

### Files in This Repository
- `weight_lifting_prediction.Rmd` - R Markdown source file
- `weight_lifting_prediction.html` - Compiled HTML report (view this for results)
- `weight_lifting_prediction.R` - Standalone R script version
- `README.md` - This file

### Viewing the Analysis
The easiest way to view the analysis is to open `weight_lifting_prediction.html` in your web browser.

Alternatively, you can:
1. Clone this repository
2. Open `weight_lifting_prediction.Rmd` in RStudio
3. Click "Knit" to regenerate the HTML report

### Model Summary
- **Algorithm**: Random Forest with 10-fold cross-validation
- **Accuracy**: >99% on validation set
- **Out-of-sample error**: <1%
- **Predictors**: 52 sensor-derived features from belt, arm, forearm, and dumbbell accelerometers

### Reproducibility
All code is included in the R Markdown file. The analysis automatically downloads the data from the provided URLs, so you can reproduce the results by knitting the Rmd file.

### Requirements
```r
install.packages(c("caret", "tidyverse", "randomForest"))
```

### Data Source
The data for this project come from: http://groupware.les.inf.puc-rio.br/har

### Author
Coursera Practical Machine Learning Course Project

### Date
November 2025

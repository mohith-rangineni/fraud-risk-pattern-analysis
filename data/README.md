# Data Folder

## Dataset Information

This folder contains the fraud detection dataset used for analysis.

### Required Dataset

**Source:** [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

**Filename:** `creditcard.csv`

### Dataset Description

The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.

**Features:**
- `Time`: Number of seconds elapsed between this transaction and the first transaction in the dataset
- - `V1-V28`: Principal components obtained with PCA (anonymized features)
  - - `Amount`: Transaction amount
    - - `Class`: Response variable (1 = fraud, 0 = legitimate)
     
      - ### How to Download
     
      - 1. Visit the [Kaggle dataset page](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
        2. 2. Click "Download" (requires Kaggle account)
           3. 3. Extract the `creditcard.csv` file
              4. 4. Place it in this `data/` folder
                
                 5. ### Generated Files
                
                 6. After running the analysis notebook, the following files will be generated:
                 7. - `high_risk_transactions.csv` - Transactions flagged as high-risk by the scoring algorithm
                   
                    - ### File Structure
                    - ```
                      data/
                      ├── README.md                    # This file
                      ├── creditcard.csv               # Main dataset (download from Kaggle)
                      └── high_risk_transactions.csv   # Generated after analysis
                      ```

                      ### Note

                      The `creditcard.csv` file is not included in this repository due to its size (~150 MB). Please download it from Kaggle using the link above.

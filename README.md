# Spam Classification Using Logistic Regression

## Overview

This project involves developing a spam classification model to distinguish between spam and ham (non-spam) emails. The model uses Logistic Regression and TF-IDF vectorization to process and classify email messages.

## Dataset

The dataset used in this project is available at:

[Spam Classification Dataset]( https://drive.google.com/drive/folder...)

The dataset should be in CSV format with the following columns:
- `Category`: Indicates whether the message is 'spam' or 'ham'
- `Message`: Contains the text of the email message

## Project Structure



## Usage

1. **Prepare your data**: Ensure your dataset `mail_data.csv` is in the `data` directory and has the following format:

    ```
    Category,Message
    ham,Go until jurong point, crazy.. Available only ...
    spam,Free entry in 2 a wkly comp to win FA Cup fina...
    ```

2. **Run the Model Training**:
    - Modify `model.py` as needed.
    - Execute the script to train the model:

      ```bash
      python src/model.py
      ```

3. **Classify Emails**:
    - Modify `main.py` to include the email content you want to classify.
    - Run the classification script:

      ```bash
      python src/main.py
      ```
    


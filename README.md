# Venture Funding with deep learning
This project analyzes data from a csv source file containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Machine learning and Neural Networks features are applied to create a binary classifier model that will predict whether an applicant will become a successful business. The CSV file contains a variety of information about these businesses, including whether or not they ultimately became successful.

## Data Preparation: Sample data showing Applicant Data
<img width="1199" alt="Screenshot 2023-11-22 231618" src="https://github.com/ahcano/venture_funding_with_deep_learning/assets/141194281/612321e8-5e00-4599-9d04-98c9baebc3c1">

## Data Encoding: Only columns with data type "object" were selected and encoded into a binary classification model (sample image below)
<img width="1471" alt="Screenshot 2023-11-22 232039" src="https://github.com/ahcano/venture_funding_with_deep_learning/assets/141194281/fce8dca9-88ea-4f28-9682-23904d403766">

## Then the original dataframe's numerical values (IS_SUCCESSFUL, ASK_AMT, STATUS) were joined with the dataframe containing the encoded variables (sample image below)
<img width="1228" alt="Screenshot 2023-11-22 232623" src="https://github.com/ahcano/venture_funding_with_deep_learning/assets/141194281/8fe42113-40a9-4acf-b9c8-755cdbb1265c">

## Using the preprocessed data, model features (X) and target (y) datasets were created. The target dataset should be defined by the preprocessed DataFrame column “IS_SUCCESSFUL”. The remaining columns should define the features dataset.
<img width="529" alt="Screenshot 2023-11-22 232918" src="https://github.com/ahcano/venture_funding_with_deep_learning/assets/141194281/095ab39d-4e2e-406c-bf4c-e32a2ef50690">

## The features and target sets were split into training and testing datasets. 
<img width="480" alt="Screenshot 2023-11-22 233253" src="https://github.com/ahcano/venture_funding_with_deep_learning/assets/141194281/d66fa2e1-b580-42df-8fa1-e62dc6a09358">

## Using scikit-learn's StandardScaler , the features data was scaled to fit into the binary classification model 
<img width="333" alt="Screenshot 2023-11-22 233302" src="https://github.com/ahcano/venture_funding_with_deep_learning/assets/141194281/3488a65a-9c90-484e-ada2-154ec5c31041">

## Usage
The code was developed using Google Colab 

## Contributor
Ana Cano - Author  

## License
Copyright (c) 2011-2017 GitHub Inc. Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

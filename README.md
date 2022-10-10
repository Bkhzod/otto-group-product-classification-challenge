 # Otto group product classification
 ## Datasets
 sampleSubmission.csv 
 
 test.csv
 
 train.csv
 
 ## Description from Kaggle  
 The Otto Group is one of the world’s biggest e-commerce companies, with subsidiaries in more than 20 countries, including Crate & Barrel (USA), Otto.de (Germany) and 3 Suisses (France). We are selling millions of products worldwide every day, with several thousand products being added to our product line.

 A consistent analysis of the performance of our products is crucial. However, due to our diverse global infrastructure, many identical products get classified differently. Therefore, the quality of our product analysis depends heavily on the ability to accurately cluster similar products. The better the classification, the more insights we can generate about our product range.

For this competition, we have provided a dataset with 93 features for more than 200,000 products. The objective is to build a predictive model which is able to distinguish between our main product categories. The winning models will be open sourced.

## Evaluation
Submissions are evaluated using the multi-class logarithmic loss. Each product has been labeled with one true category. For each product, you must submit a set of predicted probabilities (one for every category).

## Submission Format
You must submit a csv file with the product id, all candidate class names, and a probability for each class. The order of the rows does not matter. The file must have a header and should look like the following:
![Untitled-1](https://user-images.githubusercontent.com/113719546/194911126-4dddeb09-1506-45d7-9085-b41302456ff3.jpg)

# My result 
Loss score in train.csv - 0.4897

Loss score in test.csv:

![Untitled-1](https://user-images.githubusercontent.com/113719546/194912915-6a588953-2d63-45ff-90ff-090fcf874965.jpg)

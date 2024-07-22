# Assignment-1: Food Recommendation System (FoodRecomendationTask)

## Objective
Develop a food recommendation system that suggests food items similar to the user's preferred food items using a given dataset.

## Dataset
You will be provided with a dataset containing information about various food items. The dataset will include attributes such as:
- Food ID
- Food Name
- Food Category
- Food Description/Info
- Food Tags
- Food Dietary
- Food Preparation Styles
- Food Presentation
- Food Concept
- Flavour Type
- Restaurant Name
- MealTime
- User Ratings


## Requirements

### Data Preprocessing:
- check out the food data[click here](./doc/Food%20Data.csv)
- Load and inspect the dataset.
- Handle missing values if any. [If required]
- Encode categorical variables (e.g., tags) [If required].

### Feature Engineering:
- Create meaningful additional features that can help in measuring the similarity between food items. [If required].

### User Preference Input:
- check out the User preferred food [click here](./doc/User%20Preferances.csv)
- Allow the user to input their preferred food item(s).
- Extract features of the user’s preferred food item(s) from the dataset.

### Similarity Measurement:
- Implement a similarity measurement algorithm (e.g., cosine similarity, Euclidean distance) to find similar food items.
- Calculate the similarity score between the user’s preferred food item(s) and all other food items in the dataset.

### Recommendation System:
- Based on the similarity scores, recommend the top N food items that are most similar to the user’s preferred food item(s).
- Display the recommended food items along with their details (e.g., Restaurant, Food Name, Ratings).

### Evaluation:
- Evaluate the recommendation system using appropriate metrics (e.g., Precision, Recall, F1-Score).
- Validate the effectiveness of the recommendations with a subset of user feedback if available.

## Submission
Submit the following:
- A Jupyter Notebook (.ipynb) file or a python file (.py) with the complete implementation.
- A report explaining the approach, techniques used, and evaluation results.

## Deadline
As Soon As Possible

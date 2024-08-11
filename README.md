# Product Recommendation System

## Introduction
This project demonstrates the development of a product recommendation system utilizing both popularity-based and collaborative filtering techniques. The goal is to suggest relevant products to users based on their past behavior and the behavior of other users. The dataset used in this project consists of user ratings for electronic products.

## Features
- **Popularity-Based Recommendations**: Recommends products to users based on the overall popularity of the items, without considering individual user preferences.
- **Collaborative Filtering**: Utilizes Singular Value Decomposition (SVD) to generate personalized recommendations based on user-item interactions.
- **Data Visualization**: Includes visualizations of rating distributions and user-product interactions.
- **Evaluation**: The collaborative filtering model is evaluated using Root Mean Square Error (RMSE) to measure its effectiveness.

## Dataset
The dataset comprises user ratings for electronic products, with columns representing user IDs, product IDs, and the corresponding ratings.

## Project Structure
1. **Importing Libraries**: Essential libraries for data manipulation, mathematical computations, and visualization are imported.
2. **Loading and Exploring the Dataset**: The dataset is loaded, explored, and cleaned by removing unnecessary columns.
3. **Data Preprocessing and Subsetting**: A subset of the data is taken for quicker processing, and the distribution of ratings is analyzed.
4. **Visualizing the Rating Distribution**: Visualization of the ratings distribution to understand user behavior.
5. **Identifying Unique Users and Products**: Exploration of the number of unique users and products, and identification of top users.
6. **Filtering Data for Collaborative Filtering**: Filtering of data to include users who have rated a minimum number of products.
7. **Creating a User-Item Matrix**: Construction of a user-item matrix used in recommendation models.
8. **Splitting the Data**: Data is split into training and testing sets for evaluation purposes.
9. **Building a Popularity-Based Recommendation Model**: A simple model is built based on product popularity.
10. **Generating Recommendations for Users**: Function to generate recommendations for specific users using the popularity-based model.
11. **Building a Collaborative Filtering Model**: A collaborative filtering model is developed using Singular Value Decomposition (SVD).
12. **Generating Personalized Recommendations**: Personalized recommendations are generated based on user behavior.
13. **Evaluating the Collaborative Filtering Model**: The collaborative filtering model is evaluated using RMSE.
14. **Generating Top-K Recommendations for a User**: Top-K recommendations are generated for specific users.

## Conclusion
This project successfully demonstrates the creation of a recommendation system using both popularity-based and collaborative filtering approaches. The collaborative filtering model, powered by SVD, provided personalized recommendations, and its effectiveness was evaluated using RMSE.

## How to Run
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/jerin-mx/smart-product-recommender.git
    ```
2. **Install Required Libraries**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Run the Notebook**:
    - Open the Jupyter Notebook and run the cells sequentially.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required Python libraries (as listed in `requirements.txt`)

## Future Enhancements
- **Integration with a web application**: Implement the recommendation system as a backend service in a web application.
- **Real-time Recommendations**: Enhance the system to provide real-time recommendations.
- **Incorporate More Features**: Include additional user and product features to improve recommendation accuracy.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

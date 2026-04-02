# Customer Segmentation using K-Means Clustering

## Problem Statement
The objective of this project is to segment customers into meaningful groups based on their purchasing behavior and characteristics. This helps businesses understand customer patterns and design targeted marketing strategies.

## Approach
- Applied K-Means clustering for unsupervised learning  
- Performed data preprocessing and feature scaling  
- Used the Elbow Method to determine the optimal number of clusters  
- Grouped customers based on similarity in features  

## Methodology
- Loaded and explored the dataset  
- Selected relevant features for clustering  
- Scaled features using standardization  
- Applied K-Means algorithm to form clusters  
- Visualized clusters using plots for interpretation  

## Results
- Successfully segmented customers into distinct groups  
- Identified patterns in spending and behavior  
- Visualized clusters to understand customer distribution  

## Key Observations
- Customers were grouped based on spending behavior and activity levels  
- Certain clusters represented high-value customers with higher engagement  
- Some clusters showed low spending and low interaction, indicating potential churn risk  
- Clear separation between clusters indicates effective feature selection and scaling  
- Cluster distribution suggests diversity in customer behavior patterns  

## Business Insights
- High-value customers can be targeted with premium offers and loyalty programs  
- Low-engagement customers can be re-engaged using discounts or personalized campaigns  
- Medium-value customers can be converted into high-value customers with targeted strategies  
- Segmentation helps in efficient resource allocation and marketing optimization  

## Tech Stack
- Python  
- Scikit-learn  
- NumPy  
- Pandas  
- Matplotlib  

## Project Structure
smart_cart.ipynb  
smartcart_customers.csv  
requirements.txt  

## How to Run

1. Clone the repository:
git clone https://github.com/Rajneel-Chavan/customer-segmentation-kmeans.git  
cd customer-segmentation-kmeans  

2. Install dependencies:
pip install -r requirements.txt  

3. Run the notebook:
jupyter notebook smart_cart.ipynb  

## Key Learnings
- Understanding of unsupervised learning techniques  
- Practical implementation of K-Means clustering  
- Importance of feature scaling in clustering algorithms  
- Using Elbow Method for selecting optimal clusters  
- Translating data clusters into business insights  

## Notes
- This project demonstrates customer segmentation using clustering techniques  
- Useful for business analytics, recommendation systems, and targeted marketing  

## Future Improvements
- Use advanced clustering techniques like DBSCAN or Hierarchical Clustering  
- Incorporate more features for better segmentation  
- Deploy as an interactive dashboard  

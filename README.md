# Customer Segmentation Analysis Via K-Means Clustering

Customer segmentation is a powerful technique used by businesses to better understand their customers and tailor their marketing strategies to specific groups. With the advent of big data and machine learning algorithms, businesses can now leverage customer segmentation to gain a competitive advantage and improve their bottom line. In this Python notebook, we'll explore how K-Means can be used for customer segmentation and how it can help businesses make better decisions.

The first step in any customer segmentation project is to gather and preprocess the data. Our dataset contains customer information such as gender, age, income, and spending score. The spending score is a metric that reflects how much a customer spends on average. In our case, the dataset contains 200 rows of data.

Once we have the data, we can begin exploring it to identify any patterns or trends. One way to do this is through clustering, a technique used to group similar data points together. K-Means is one of the most popular clustering algorithms used in customer segmentation. It works by partitioning the data into k clusters, where k is a user-defined parameter.

Before running K-Means, we need to determine the optimal number of clusters to use. To do this, we can use three methods: Within Cluster Sum of Squares (WCSS), The Average Silhouette Score, and The Calinski Harabasz Score. In our case, we used these methods to determine that five clusters would be the optimal number for our dataset.

Next, we applied K-Means to our dataset and visualized the results. Our analysis revealed four distinct clusters of customers, each with unique characteristics. We found that Cluster 1 consisted of high earning, low spending customers, Cluster 2 contained high earning, high spending customers, Cluster 3 consisted of low earning, high spending customers, and Cluster 0 consisted of low earning, low spending customers.

Based on these findings, we recommended that the company invest in increasing the spending of the high earning, low spending customers in Cluster 1. These customers are the most profitable for the business, and by increasing their spending, the company can improve its bottom line. We also recommended keeping the high earning, high spending customers in Cluster 2 happy, as they are already spending a lot and are likely to remain loyal to the company. Cluster 3 requires a watchful eye, as these customers are high spenders but have a low income. Finally, we recommended investing in increasing the spending of the low earning, low spending customers in Cluster 0, as they represent a growth opportunity for the company.

In conclusion, customer segmentation is a powerful technique that can help businesses make better decisions and improve their bottom line. With the help of machine learning algorithms like K-Means, businesses can gain valuable insights into their customer base and tailor their marketing strategies to specific groups. Our analysis revealed four distinct clusters of customers, each with unique characteristics and recommendations for how the company can improve its business. By following these recommendations, the company can increase its profitability and stay ahead of the competition.

## Contributing

Contributions to this project are always welcome! If you find any bugs or issues with the script or want to suggest improvements, please feel free to open an issue or pull request.

## Credits
This project was created by [SahSofts](https://github.com/SahSofts/) and is licensed under the [MIT License](https://opensource.org/licenses/MIT)


## Contact

If you have any questions or feedback about this project, please contact [SahSofts](https://www.linkedin.com/in/aibyazeemali/)

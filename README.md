# customer-segmentation
Investigating customer segmentation using RFM analysis and K-Means clustering
* Overview
  
My Bachelor's thesis involved investigating customer segmentation using RFM analysis and K-Means clustering using Python. I utilized the "OnlineRetail" dataset to analyze purchasing behavior and identify customer segments based on recency, frequency, and monetary value.


* Goals
  
Gain business insight on monthly product sales.
Acquire business insights into monthly customer expenditure.
Mitigate risks in determining the optimal location, timing, method, and target audience for marketing a product, service, or brand.
Improve marketing efficiency by targeting specific customer segments based on their unique characteristics, a goal achieved through a Python project employing k-means clustering for customer segmentation.

* Dataset

  https://archive.ics.uci.edu/dataset/352/online+retail

  * Insights
 
    ![image](https://github.com/user-attachments/assets/c17eeb2b-a815-45c6-9a2b-ddff8d64913a)
    
![Screenshot (1188)](https://github.com/user-attachments/assets/bb7e3e8b-2ffd-4e70-8a8a-395164b28092)

![Screenshot (1189)](https://github.com/user-attachments/assets/eb465210-59d8-4fd0-ae15-ee345e24dc79)

* RFM Analysis

RFM (Recency, Frequency, Monetary) analysis is a customer segmentation technique based on purchasing behavior. This method categorizes customers according to how recently they’ve made a purchase, how frequently they buy, and the total amount they’ve spent. By analyzing these factors, businesses can tailor their services more effectively and identify key customer segments to enhance profitability.

Recency indicates how long it’s been since a customer’s last purchase. Frequency measures how often a customer makes purchases. Monetary value represents the total amount a customer has spent.

RFM analysis helps managers target marketing efforts more precisely, ensuring that customers receive personalized services. For instance, it can identify high spenders who may have only purchased once or determine whether frequent buyers are recent customers. These insights enable more effective promotional campaigns and better customer service.

To perform RFM analysis, we will:

Recency: Calculate the number of days since each customer’s last purchase.
Frequency: Count the total number of orders placed by each customer.

* Calculating the total RFM score combined.

RFM_Score = R_quartile + F_quartile + M_quartile

![Screenshot (1190)](https://github.com/user-attachments/assets/8b6c2a1d-89c2-4bb2-8929-3aaced6fe255)

* Modeling Data: RFM Quantiles

To segment the RFM metrics, we divide each metric—Recency, Frequency, and Monetary—into quantiles, assigning a score ranging from 1 to 4. In this scoring system, 1 represents the highest value (best performance), while 4 represents the lowest.

The overall RFM score, or Overall Value, is then calculated by combining these individual scores, providing a comprehensive measure of each customer's value based on their purchasing behavior.

* Modeling Data: K-Means Clustering

K-Means clustering is an unsupervised machine learning algorithm that groups unlabeled data points into 𝐾 distinct clusters. Through multiple iterations, the algorithm assigns each data point to a single cluster, ensuring that all points within a cluster share similar characteristics. This method is effective for identifying natural groupings in data, allowing for more targeted analysis and decision-making.

![image](https://github.com/user-attachments/assets/7b877ad9-9566-428e-bfeb-7ba9456758d0)
![image](https://github.com/user-attachments/assets/9b515027-c8cc-4d60-ba73-92dcd9876806)
![image](https://github.com/user-attachments/assets/46bda854-3829-45ad-ac41-7cc2fd9cf1fc)
![image](https://github.com/user-attachments/assets/5fc6e965-9b95-4264-8abe-d7e7a44d6976)
![image](https://github.com/user-attachments/assets/a7251a30-7c9a-4bf4-a1fd-9202c8d47815)




<h1 class="major">Customer segmentation</h1>
                  									<h3>Problem Statement</h3>
									<blockquote>Customer segmentation is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers.

Customer segmentation helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.
</blockquote>
																		<h3>Proposed Solution</h3>
									<blockquote>Using the KMeans algorithm, I have conducted customer segmentation after preprocessing the data with StandardScaler and reducing dimensionality with PCA. This approach enables the business to understand customer needs and behaviors better, facilitating targeted product modifications and marketing strategies for different customer segments. </blockquote>
         <h3>Dataset Description</h3>
         <blockquote>The dataset is downloaded from Kaggle. It contains information of 2240 customers, with 29 attributes each.
         Link to the original dataset: https://www.kaggle.com/imakash3011/customer-personality-analysis
         </blockquote>
									<h3>Conclusion</h3>
									<blockquote>
                    
**Cluster 1:**
- Smaller part of the customers (about 20%)
- Medium income group
- Everyone have at least 1 children
- Are very sensitive to items with discount
- Usually buys non-essential items (wine + gold)

**Cluster 2:**
- Bigger cluster (about 44%)
- Smaller income group
- Don't spend a lot of money
- Contains most of the people without a high-education
- Is a little younger than the average of the dataset

**Cluster 3:**
- About 36% of the customers
- High income group
- Almost everybody have 0 or 1 children.
- Spend a lot of money
- Don't buy a lot of things with discount

The more actionable information is that relation between the customers and the % of items bought with discount:

We could see that people in the cluster 1 buys a lot of non-essential items, and are very sensitive to discount.
On the other hand, people in the cluster 3 doesn't respond very well to discounts.
Therefore, **it might be a good idea to concentrate efforts to send special offers to the people in the cluster 1 (and don't send to cluster 3).**

Also, customers from the **cluster 3** spend more money, therefore **they are our most valuable customers**. It's worth doing an extra effort to make them happy!
</blockquote>
 

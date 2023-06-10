# crypto_investments

## background
Financial advisory firms want to propose a novel approach to assembling investment portfolios that are based on cryptocurrencies. Instead of basing proposals on only returns and volatility, other factors can be included that might impact the crypto market—leading to better performance for your portfolio.
This notebook is a prototype for submitting your crypto portfolio proposal.

This notebook uses unsupervised learning to cluster cryptocurrencies by their performance in different time periods. The results are plotted to visually show the performance. A CSV file of price change data of cryptocurrencies in different periods is used for the analysis.

Conclusion:
After visually analyzing the original dataset and the (PCA) reduced dataset, both have an optimal value of k=4 for the number of clusters. However, the clusters for the PCA reduced dataset appear more closely grouped, which could indicate that PCA reduced the data dimensions while maintaining the structure of the original dataset.


![market_data_browse](https://github.com/fonzeon/crypto_investments/assets/7315911/2aefca64-94a4-461c-9090-da74e4f4a8ec)
![elbow_curve_original](https://github.com/fonzeon/crypto_investments/assets/7315911/395eae81-b5ad-49a1-9e2d-98be1e8b60c4)
![clusters_original](https://github.com/fonzeon/crypto_investments/assets/7315911/88bd1aab-d3b7-443f-b693-dfaf9b965abf)
![elbow_pca](https://github.com/fonzeon/crypto_investments/assets/7315911/f93c235a-a614-4300-ae44-9576c598293c)
![clusters_pca](https://github.com/fonzeon/crypto_investments/assets/7315911/625a9979-d4e7-4aa2-8899-df68ae2bff10)
![clusters_composite](https://github.com/fonzeon/crypto_investments/assets/7315911/bdf09415-5fd2-4992-a83b-0eafce2668ce)

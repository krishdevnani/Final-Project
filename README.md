In this project we are conducting an experimental research on whether there is a correlated relationship between Tax revenue as a percentage of GDP and the portion of Government expenditure that is derived from tax revenue. To accurately evaluate this stability value, a comprehensive understanding of the relationship between tax revenue and government expenditure is essential.

The data extraction was facilitated through the Wikipedia API, utilizing snippets of information based on the page's title or text location. The dataset focuses on the tax revenue to GDP ratio for various countries

Our approach involved applying the K-Means clustering algorithm to categorize countries into distinct groups based on their tax revenue and government expenditure as a percentage of GDP. We chose three clusters to represent low, medium, and high economic health, aiming to offer a nuanced understanding of the economic landscape.

Applying K-Means clustering would focus on the identified features (Continent and Country), and reveal the similarities of distinct groups, as it is formed by the algorithm based on the features and the patterns it identifies in the data. 

This framework was used to examine the similarities and differences between the dataset's features, as it classified the countries into values 0, 1, and 2 ("low," "medium," and "high").

Based on the results obtained, it can be concluded that our program can accurately predict the fiscal stability of a country by using two indicators: tax revenue and government expenditure. 

For the program’s demonstration two countries were utilized: Denmark and the United Arab Emirates. It was predcted that Denmark would be classified as "cluster 2" due to its high tax rate and the UAE would belong to "cluster 0" since it does not have an income tax. Therefore, our program is able to identify trends among various countries.  

In the future, it is reccomended to consider additional indicators to measure the level of fiscal stability. These include accounting for a country’s level of debt, a country’s budget balance, the foreign exchange reserves, and also the availability of natural resources. It is also recommended to incorporate more years during the analysis allowing the program to identify trends over time.

In regards to limitations, the program scraped data from Wikipedia using a Wikipedia API. Wikipedia has historically had issues in regards to the reliability of the content presented on their platform. Therefore, using alternative sources would be more ideal. 

In addition, it is assumed during this experiment that collecting tax revenue was an essential indicator of measuring a country’s level of fiscal stability. However, it should be noted that there are numerous countries through which revenue can be generated. This assumption cannot be made for all countries across the world. 


Note: Specific instructions regarding the how the code is run is included as comments in the final_code.ipynb file

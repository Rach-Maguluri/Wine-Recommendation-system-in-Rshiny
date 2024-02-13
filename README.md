# Wine-Recommendation-system-in-Rshiny

# Introduction

The Wine Recommendation App is a user-centric web application developed using R Shiny, designed to enhance customer satisfaction by providing personalized wine suggestions. Leveraging integrated datasets of wine reviews and facts, the app offers a tailored selection experience, dynamically adjusting options based on user inputs to recommend wines that align with individual tastes and preferences. With features for filtering by ratings, brand, quantity, and weight, and providing direct links for purchase, this application streamlines the wine selection process, ensuring a customized and interactive user experience.

### Application Summary
The Wine Recommendation App is a user-friendly web application built using R Shiny, a framework for creating interactive web applications in R. The application integrates two key datasets: wine reviews and wine facts, which contain comprehensive information about various wines, including reviews, ratings, brand names, quantities, and weights. These datasets are merged on a common column (id), ensuring a rich database for the recommendation engine. A new sub data set wine data was created which had only the necessary variables for the app. 

### Variables Chosen 
Name, quantity.x, quantity.y, brand.x, brand.y, reviews.rating.x, reviews.rating.y, sourceURLs.x, sourceURLS.y, weight.x, weight.y, reviews.text.x, reviews.text.y

### Why these variables?
The variables for the Wine Recommendation App were chosen to enhance the recommendation engine and user experience:

1. Name: Essential for identifying and recommending specific wines.
2. Quantity (x, y): Offers insight into available sizes, catering to diverse user needs.
3. Brand (x, y): Enables brand-based preferences, enriching the selection process.
4. Reviews Rating (x, y): Reflects quality and popularity, guiding informed choices.
5. Source URLs (x, y): Facilitates direct purchase, improving user convenience.
6. Weight (x, y): Addresses logistical considerations like shipping and handling.
7. Reviews Text (x, y): Provides qualitative insights from other consumers, aiding decision-making.

## Solving the Wine Company's Challenges

The Wine Recommendation App addresses several key challenges faced by the wine company:
1.	Ease of Use: The intuitive UI design ensures that users of all technical abilities can navigate the application and find their preferred wines without difficulty.
2.	Engagement and Retention: The engaging UI and personalized recommendations encourage users to explore different wines, thereby increasing user engagement and retention.
3.	Direct Purchase Links: The inclusion of source links to buy the recommended wines simplifies the purchasing process, potentially increasing sales for the wine company.

1. This is how the Wine Recommendation App looks after the code in R shiny is run
   
   ![The Preview of the system](https://github.com/Rach-Maguluri/Wine-Recommendation-system-in-Rshiny/blob/main/pc1.png)

2. The users can choose the filter – Rating first. And then, they can choose the Brand of wine from the drop-down menu that contains all the possible Brands.

   ![2](https://github.com/Rach-Maguluri/Wine-Recommendation-system-in-Rshiny/blob/main/p2.png)

3.	Once the Brand is selected, the corresponding quantity of the wine, and weight of the wine bottle are updated in their respective drop-down lists.

    ![3](https://github.com/Rach-Maguluri/Wine-Recommendation-system-in-Rshiny/blob/main/p3.png)


Some wine bottles have quantity options to choose from and the weight of the wine bottle. Below are some examples.
Jim Beam has different options for the quantity and the weight of the wine bottle.

4.	Now, once the user has chosen the rating, brand, quantity, and weight of the wine bottle, they shall now be able to see the Name of the recommended wine, respective reviews, and the Source URLs to purchase the product. 

    ![4](https://github.com/Rach-Maguluri/Wine-Recommendation-system-in-Rshiny/blob/main/p4.png)

5. This is how the system looks like and functions.
   
   ![Final System](https://github.com/Rach-Maguluri/Wine-Recommendation-system-in-Rshiny/blob/main/p5.png)



The Wine Recommendation App's server logic is designed to dynamically update the selection options based on user inputs and provide recommendations accordingly. The application performs the following functions:


*Filters wines based on the user's selected rating and updates the brand choices to match the rated wines.
*Updates quantity and weight choices based on the selected brand, ensuring that the recommendations are precise.
*Processes the user's selections upon clicking the submit button and displays the recommended wine name, relevant reviews, and clickable source links for purchase.
*The application also handles edge cases, such as when no data matches the user's selections, by requiring that at least one row of data is present to display the recommendations.


## Conclusion

The Wine Recommendation App prototype represents a significant step towards enhancing the consumer experience in wine selection. By leveraging personalized recommendations and an intuitive interface, the app addresses the wine company's need for an innovative solution to engage and educate its customers. Future enhancements could include deploying the app online for the public to use, more advanced filtering options, integration with social media for sharing recommendations, and user accounts for tracking preferences and past selections.





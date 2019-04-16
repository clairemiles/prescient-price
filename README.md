## Prescient Price: Using Machine Learning to Predict the Price of Airbnb Listings 
<img src='homes.png'> 

### Problem Statement:
Today’s world is more connected than ever. With increasingly long nonstop flights, spontaneous translation apps, and social media friendships spawning worldwide, it’s easier than ever to be a global citizen. One company catalyzing connections is Airbnb, which provides a service that allows property owners to rent their houses, apartments, or rooms in their hometowns, offering tourists a unique way to lodge in a new city - one that is arguably more authentic than lounging at a luxury resort.

By creating these home-away-from-homes, Airbnb has skyrocketed in popularity for those looking to live like locals and be more culturally connected to their destination. It’s in Airbnb’s best interest for its listings to be the best they can be, not only to crete an optimal user experience, but also to maximize the prices of their listings. Therefore, it’s very useful to know what goes into a successful listing, and to be able to predict the price of a listing from its attributes. This will help Airbnb increase its revenue and help hosts optimize the value of their listings by predicting their success.
 
### Inquiry:
How can we predict an Airbnb listing price based on other information about that listing?

### Dataset Description:
I used data from [Inside Airbnb](http://insideairbnb.com/get-the-data.html), an independent, non-commercial project that collects public data from the travel and accomodations company Airbnb. Data is collected monthly from major cities and metropolitan regions around the world, and includes information about that city’s listings, reviews, and calendar data. I focused on data about Airbnb listings and the reviews for those listings. The listings data contains almost 100 columns of attributes for each listing, including number of bedrooms and bathroom, square footage, amenities provided, host information, etc. The reviews data includes the text of the reviews left for each listing. The information between the two datasets can be linked using provided ID numbers.

### Project Plan
This project includes notebooks for all stages in the process: 0) data collection, 1) data cleaning, 2) data plotting and prelimiary exploration, 3) feature creation and machine learning modeling. Using numpy, pandas, matplotlib/seaborn, scikit-learn, and vaderSentiment I crafted a ML-ready dataset from several messy, human-collected csv files, crafted features from non-numeric data, and explored and evaluated several tree-based ML regression models including random forests, gradient boosting, and XGBoost.

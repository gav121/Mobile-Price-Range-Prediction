# Mobile-Price-Range-Prediction
**INTRODUCTION:**

Price is the most effective marketing and business attribute. The very first question of the customer concerns the price of the goods. All customers are concerned at first and think “Whether he would be able to buy something with the given specifications or not”. So estimating the price at home is the basic purpose of the job. This document is only the first step towards the above goal.
Artificial intelligence – making a machine able to answer questions intelligently – is a very large field of engineering today. Machine learning gives us the best techniques for artificial intelligence like classification, regression, supervised and unsupervised learning and many more. There are various tools available for machine learning tasks like MATLAB, Python etc. We can use any of the classifiers like Decision tree , Naïve Bayes and many more. Different types of feature selection algorithms are available to select only the best features and minimize the dataset. This reduces the computational complexity of the problem. Since this is an optimization problem, many optimization techniques are also used to reduce the dimensionality of the dataset.

**PROBLEM STATEMENT:**
Maximize: The sales of Mobile 
Minimize: Minimise the price of Mobile with the features.

**DATA SUMMARY:**

Battery_power - Total energy a battery can store in one time measured in mAh
Blue - Has bluetooth or not
Clock_speed - speed at which microprocessor executes instructions
Dual_sim - Has dual sim support or not
Fc - Front Camera mega pixels
Four_g - Has 4G or not
Int_memory - Internal Memory in Gigabytes
M_dep - Mobile Depth in cm
Mobile_wt - Weight of mobile phone
N_cores - Number of cores of processor
Pc - Primary Camera mega pixels
Px_height - Pixel Resolution Height
Px_width - Pixel Resolution Width
Ram - Random Access Memory in Mega
Touch_screen - Has touch screen or not
Wifi - Has wifi or not
Sc_h - Screen Height of mobile in cm
Sc_w - Screen Width of mobile in cm
Talk_time - longest time that a single battery charge will last when you are
Three_g - Has 3G or not
Wifi - Has wifi or not
Price_range - This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).





**CONCLUSIONS:**

From The EDA We Get That The Feature ‘RAM’ Is The Most Relative Feature With Our Dependable Feature ‘Price Range’. More RAM Capacity Will Increase The Price Of The Mobile.
By Implementing All The Models We Have Found That Gradient Boosting Has The Best Score Of 91.2% Followed By Logistic Regression of 91.1% And Random Forest Of 89%.
By Appling Hyper Parameter Tuning We Get The Score Of Gradient Boosting Of 92%.
The Battery Power And Pixel Height Also Positively Correlated With Price Range That Means It Will Also Create Some Impact To The Calculation.

So We Can Conclude That The Best For This Dataset Is Gradient Boosting With Hyper Parameter Tuning, Which Can Be Used For Future Prediction Of The DataSet. 

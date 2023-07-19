# Mobile-Price-Range-Prediction-Classification-Project

This data science project aimed to predict mobile phone price ranges based on their specifications using machine learning algorithms. The dataset consisted of various features related to mobile phones such as battery capacity, RAM, internal memory, camera quality, and other hardware specifications. 

The dataset was split into training and testing sets and several machine learning algorithms such as Logistic Regression, Decision Tree, Random Forest, and Support Vector Machines (SVM) were applied to the training set. The Random Forest algorithm was chosen as the final model due to its high accuracy and F1-score. The project concluded that predictive modeling can be an effective approach for mobile price range detection and highlighted the importance of data preprocessing and feature engineering for improving model accuracy.

In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

Data Description -

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

Ram - Random Access Memory in Mega Bytes

Sc_h - Screen Height of mobile in cm

Sc_w - Screen Width of mobile in cm

Talk_time - longest time that a single battery charge will last when you are

Three_g - Has 3G or not

Touch_screen - Has touch screen or not

Wifi - Has wifi or not

Price_range - This is the target variable with value of3

0(low cost),

1(medium cost),

2(high cost) and

3(very high cost).

Thus our target variable has 4 categories so basically it is a Multiclass classification problem.

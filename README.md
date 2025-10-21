# Machine-learning-workshop

Swiggy Delivery Time Prediction 🚴‍♀
A Machine Learning web application built using Streamlit that predicts the estimated delivery time for Swiggy orders based on various real-world factors such as weather, traffic, delivery agent details, and more. Users can enter details about the delivery, and the trained ML model will output the expected delivery time in minutes.

Project Overview
This project demonstrates an end-to-end machine learning solution — from data preprocessing and model training to deploying an interactive web app with Streamlit. The app takes multiple delivery-related inputs from the user and predicts the estimated delivery time in minutes using a pre-trained model. This provides practical insight into real-world delivery operations and helps understand factors affecting delivery times.

Tech Stack
Python
Streamlit (interactive web interface)
Pandas (data manipulation)
Scikit-learn / Pickle (machine learning model)
Features
✅ Interactive web interface using Streamlit ✅ Accepts multiple input parameters including weather, traffic, vehicle type, order type, and more ✅ Predicts delivery time in minutes ✅ Uses a pre-trained machine learning model (model.pkl) ✅ Based on a real-world dataset (swiggy_cleaned.csv)

How to Run the Project
Clone the Repository:
git clone https://github.com/your-username/swiggy-delivery-time-prediction.git
cd swiggy-delivery-time-prediction
Install Dependencies:
pip install streamlit pandas scikit-learn
Run the Streamlit App:
streamlit run app.py
Enter Input Values: Fill in the fields such as Age, Rating, Weather, Traffic, Vehicle Condition, Order Type, Type of Vehicle, Number of Deliveries, Festival, City Type, City Name, Day of the Week, Weekend Indicator, Pickup Time, Order Hour, Order Time of Day, and Distance. Click Predict to see the estimated delivery time.
Input Features
Feature	Description
Age	Delivery agent’s age
Rating	Average rating of the delivery agent
Weather	Current weather conditions
Traffic	Traffic density during delivery
Vehicle Condition	Condition of the delivery vehicle
Type of Order	Category of food ordered
Type of Vehicle	Bike, scooter, motorcycle, etc.
Multiple Deliveries	Number of deliveries in one trip
Festival	Indicates if it’s a festive day
City Type	Urban / Semi-Urban / Rural
City Name	Delivery location
Order Day of Week	Day when order was placed
Is Weekend	1 if weekend, else 0
Pickup Time Minutes	Time taken to pick up the order
Order Time Hour	Hour of the order placed
Order Time of Day	Morning / Afternoon / Evening / Night
Distance	Distance between restaurant and delivery point
Example Prediction Output
After entering the inputs:

Age: 1
Rating: 1
Weather: sunny
Traffic: high
Vehicle Condition: 2
Type of Order: snack
Type of Vehicle: motorcycle
Multiple Deliveries: 1
Festival: no
City Type: urban
City Name: INDO
Order Day of Week: saturday
Is it Weekend: 0
Pickup Time Minutes: 1
Order Time Hour: 1
Order Time of Day: morning
Distance: 1
The predicted delivery time output is:

“The delivery Time is 43.0 mins”

Credits
This project was developed during the Machine Learning Hands-on Workshop (Basics to Deployment) by Innomatics Research Labs, Dilsukhnagar, Hyderabad.

I also participated in a 5-day Machine Learning Hands-on Workshop conducted by Innomatics Research Labs, Hyderabad, where I gained extensive practical experience in building end-to-end machine learning solutions. During this workshop, I worked on real-world datasets, performing data cleaning, preprocessing, feature engineering, handling missing values, and transforming data for model training. I built and evaluated multiple machine learning models using Python and Scikit-learn, learned about hyperparameter tuning, model evaluation metrics, and ways to optimize model performance. The workshop also provided hands-on experience with Pickle for saving and loading trained models, and with Streamlit for deploying models as interactive web applications. This experience helped me strengthen my understanding of real-world machine learning workflows, gain confidence in designing and deploying ML models, and directly apply these skills to develop this Swiggy Delivery Time Prediction project.

Future Improvements
Integrate Google Maps API for dynamic distance calculation
Deploy on Streamlit Cloud or Hugging Face Spaces
Add visualization for feature importance

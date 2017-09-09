
Problem statement: 

To cement an API of location-based alert systems. On arriving within a certain radius of a certain destination determined by GPS, relevant alerts may be triggered on smart which may serve multiple purposes: to wake up a sleeping user, to serve as a reminder system, trigger changes in other applications via associated permissions, etc. This may be extended to further services on the smart phone activated/deactivated on arriving at said location, and is also scalable from individuals to business entities.

Use of Cognitive Services: Cognitive Services may be deployed in various ways for the following purposes: 
-To enable a custom decision making API in events such as the time period between the setting of the alert and arrival at destination is a large amount of time: the API would serve to intelligently automate time-outs of GPS service so as to conserve battery life. 
-To deploy a recommender system in the case of oft-frequented locations: The user's log of details of the app's usage may be fed to a model that would intelligently provide suggestions for setting alerts in case of these locations.

Commit history:

(1) The first commit is for a logistic regressor/neural network written to process a pattern of user input and detect user preferences. This would be extended further to an online learning model, wherein every confirmation/declination of the app's suggestion is taken as a new data point and fed into the optimization algorithm associated with the model. 
(2) The second commit is an Android Studio snippet to generate notifications according to events. In this case, the event would be arriving within a certain radius of a user-input destination, according to GPS. 
(3) The third commit is an extension of the application of the Google Maps API. The code uses the search bar as provided in the API to choose the destination in order to finally set the alert.
(4) The fourth commit is a rework of the Google Maps API interface, with more optimization and efficiency.


